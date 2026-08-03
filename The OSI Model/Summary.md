# 08 - OSI Model & The 7 Layers (מודל ה-OSI ו-7 השכבות)



---

## 🇺🇸 English Summary

The **OSI (Open Systems Interconnection) Model** was created by **ISO** to establish an open, standardized framework for computer networking. It ensures devices from different vendors can communicate seamlessly across networks.

The model divides network communication into **7 distinct layers**:
- **Data Encapsulation:** When sending data, it moves down from Layer 7 to Layer 1, wrapping data with headers/trailers at each layer.
- **Data Decapsulation:** When receiving data, it moves up from Layer 1 to Layer 7, stripping headers/trailers at each layer.

---

### 💻 1. Software Layers (Layers 7, 6, 5)

* **Layer 7: Application Layer**
  * Provides network interface services directly to end-user applications.
  * *Protocols:* HTTP/HTTPS (Web browsing), FTP (File transfer), SMTP (Email), DNS, DHCP.
* **Layer 6: Presentation Layer**
  * Handles **Translation** (ASCII/Unicode to Binary), **Data Compression** (reducing file size), and **Encryption/Decryption** (SSL/TLS).
* **Layer 5: Session Layer**
  * Establishes, maintains, and terminates sessions between applications.
  * Handles **Authentication**, **Authorization**, and **Session Management** (caching data for smooth reconnects). Supports Simplex, Half-Duplex, and Full-Duplex communication.

---

### 🚚 2. Transport & Network Layers (Layers 4, 3)

* **Layer 4: Transport Layer**
  * **Segmentation:** Breaks large application data into smaller **Segments** with sequence numbers for reassembly.
  * **Flow Control:** Adjusts data transmission speed to match receiver capacity.
  * **Protocol Selection:**
    * **TCP (Transmission Control Protocol):** Connection-oriented, reliable, guarantees delivery via Acknowledgments (ACKs), slower (e.g., File Download, Email, Web).
    * **UDP (User Datagram Protocol):** Connectionless, unreliable, extremely fast, no ACKs (e.g., VoIP, Live Video Streaming, Online Gaming).
* **Layer 3: Network Layer**
  * **Logical Addressing:** Attaches Source and Destination **IP Addresses** to form a **Packet**.
  * **Routing:** Determines the best physical path across networks using routing protocols (e.g., OSPF, RIP, BGP).

---

### 🔌 3. Hardware & Physical Layers (Layers 2, 1)

* **Layer 2: Data Link Layer**
  * **Physical Addressing:** Uses 48-bit **MAC Addresses** (Media Access Control) burned into the NIC.
  * **Framing:** Encloses IP packets into **Frames** with a Layer 2 Header (MACs) and Trailer.
  * **Error Detection:** Uses algorithms like **CRC (Cyclic Redundancy Check)** in the trailer to detect frame corruption during transmission.
* **Layer 1: Physical Layer**
  * Converts binary bits (0s and 1s) into physical signals over the network medium:
    * Electrical pulses (Copper / UTP cables)
    * Light pulses (Fiber optics)
    * Radio frequencies (Wireless / Wi-Fi)

---

## 🇮🇱 סיכום בעברית

מודל ה-**OSI (Open Systems Interconnection)** פותח על ידי ארגון **ISO** כדי ליצור תקן עולמי אחיד לתקשורת מחשבים. המודל מבטיח שמכשירים של יצרנים שונים יוכלו לתקשר ביניהם ללא בעיות.

המודל מחלק את כל תהליך התקשורת ל-**7 שכבות מוגדרות**:
- **Encapsulation (עטיפת נתונים):** בצד השולח, המידע יורד משכבה 7 לשכבה 1, ובכל שכבה מתווספת כותרת (Header) או סיומת (Trailer).
- **Decapsulation (פירוק עטיפה):** בצד המקבל, המידע עולה משכבה 1 לשכבה 7, ובכל שכבה מופשטות הכותרות עד להצגת המידע באפליקציה.

---

### 💻 1. שכבות התוכנה (שכבות 7, 6, 5)

* **שכבה 7: שכבת היישום (Application Layer)**
  * מספקת ממשק רשת ישירות לאפליקציות המשתמש.
  * *פרוטוקולים נפוצים:* HTTP/HTTPS (גלישה), FTP (העברת קבצים), SMTP (דוא"ל).
* **שכבה 6: שכבת התצוגה (Presentation Layer)**
  * אחראית על **תרגום** (המרה מבינארי לתווים קריאים), **דחיסת נתונים** (הקטנת נפח הנתונים), ו**הצפנה/פענוח** (אבטחת מידע כגון SSL/TLS).
* **שכבה 5: שכבת השיחה (Session Layer)**
  * מנהלת את הדיאלוג והחיבור בין אפליקציות. אחראית על **אימות זהות (Authentication)**, **הרשאות (Authorization)**, ו**ניהול סשן (Session Management)** (שמירת מידע זמני לעבודה ללא אינטרנט).

---

### 🚚 2. שכבות התחבורה והרשת (שכבות 4, 3)

* **שכבה 4: שכבת התחבורה (Transport Layer)**
  * **סגמנטציה (Segmentation):** פירוק הנתונים למקטעים קטנים (**Segments**) והוספת מספרי סדרה כדי לאפשר הרכבה מחדש.
  * **בקרת זרימה (Flow Control):** התאמת קצב שליחת הנתונים ליכולת הקליטה של המקבל למניעת הצפה.
  * **בחירת פרוטוקול:**
    * **TCP:** פרוטוקול מבוסס חיבור, אמין, מבטיח הגעת מידע מלאה בעזרת אישורי קבלה (ACK), איטי יותר (מתאים להורדות, דוא"ל, גלישה).
    * **UDP:** פרוטוקול ללא אישור קבלה, מהיר מאוד, ללא מנגנון שחזור שגיאות (מתאים לשיחות וידאו, שידורים חיים, משחקים ברשת).
* **שכבה 3: שכבת הרשת (Network Layer)**
  * **כתובות לוגיות (IP Addressing):** הוספת כתובות IP מקור ויעד ליצירת חבילה (**Packet**).
  * **ניתוב (Routing):** בחירת המסלול האופטימלי להעברת הנתונים ברשת בעזרת פרוטוקולי ניתוב.

---

### 🔌 3. שכבות החומרה והפיזית (שכבות 2, 1)

* **שכבה 2: שכבת קישור הנתונים (Data Link Layer)**
  * **כתובות פיזיות (MAC Address):** שימוש בכתובת MAC בת 48 ביטים הצרובה בכרטיס הרשת (NIC).
  * **מיסגור (Framing):** אריזת ה-Packet לתוך מסגרת (**Frame**) והוספת כותרת פיזית וסיומת.
  * **זיהוי שגיאות (Error Detection):** שימוש באלגוריתם **CRC (Cyclic Redundancy Check)** בסיומת ה-Frame לגילוי שיבושים בשידור.
* **שכבה 1: השכבה הפיזית (Physical Layer)**
  * המרת הביטים (0 ו-1) לאותות פיזיים המועברים במדיה:
    * אותות חשמליים (כבלי נחושת UTP)
    * אותות אור (סיבים אופטיים)
    * גלי רדיו (תקשורת אלחוטית Wi-Fi)

---

## 🔑 Key Terms & Vocabulary (מילון מונחים)

| Term (English) | Hebrew Translation | Description / הגדרה |
| :--- | :--- | :--- |
| **OSI Model** | מודל ה-OSI | 7-layer theoretical framework for network communications |
| **Encapsulation** | עטיפת נתונים | Adding headers/trailers as data moves down Layers 7 to 1 |
| **Decapsulation** | פירוק עטיפה | Removing headers/trailers as data moves up Layers 1 to 7 |
| **Segment** | מקטע | Layer 4 Protocol Data Unit (PDU) |
| **Packet** | חבילה | Layer 3 Protocol Data Unit (PDU) containing IP addresses |
| **Frame** | מסגרת | Layer 2 Protocol Data Unit (PDU) containing MAC addresses & CRC |
| **MAC Address** | כתובת פיזית | 48-bit unique hardware identifier assigned to a NIC |
| **CRC (Cyclic Redundancy Check)** | בדיקת יתירות מחזורית | Error detection algorithm embedded in the Layer 2 trailer |
| **Flow Control** | בקרת זרימה | Managing transmission rate between sender and receiver |
| **TCP vs. UDP** | פרוטוקולי תחבורה | TCP is connection-oriented/reliable; UDP is fast/connectionless |

---

## 🛠️ Application Support Connection (חיבור לתמיכת אפליקציות)

Understanding the OSI model is vital for Application Support Engineers when troubleshooting issue sources:
1. **Application Layer (L7):** Is the web service/API returning HTTP 500 or 404 errors?
2. **Presentation Layer (L6):** Is there an SSL/TLS certificate mismatch or data parsing issue?
3. **Transport Layer (L4):** Is a firewall blocking specific TCP/UDP ports (e.g., port 443, 80, 3306)?
4. **Network Layer (L3):** Can the host ping the server IP, or is there a routing issue?
5. **Data Link / Physical Layer (L2/L1):** Is the cable damaged, or is there a duplicate MAC address?

---

## 📝 Practice Homework Scenario (שיעורי בית ותרחיש מעשי)

### Scenario:
A user reports that a live video streaming app buffers constantly, while file downloads from the same server complete without errors.

1. **Which Transport Layer protocol does live video streaming usually use and why?**
2. **If packet loss occurs on the network, how do TCP and UDP handle it differently?**

<details>
<summary><b>Click for Sample Solution / לחץ לצפייה בפתרון</b></summary>

1. Live streaming typically uses **UDP** because speed and real-time delivery are critical.
2. **TCP** retransmits lost packets using ACKs (ensuring 100% data integrity but causing delays/buffering), whereas **UDP** drops corrupted packets and continues sending the stream immediately without waiting for retransmission.
</details>
