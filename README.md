# My CCNA Journey

Welcome to my CCNA learning journey.

This repository documents my progress while studying networking fundamentals and preparing for the Cisco CCNA certification.

## Repository Goals

- Build a solid networking foundation
- Practice troubleshooting methodology
- Learn through Packet Tracer labs
- Document networking concepts
- Connect networking knowledge with real-world Technical Support and Application Support scenarios

## Topics Covered

- OSI Model
- TCP/IP
- LAN / WAN
- Switching
- Routing
- VLANs
- Subnetting
- DNS
- DHCP
- NAT
- IPv4 / IPv6
- Packet Tracer Labs
- Troubleshooting Scenarios

New content is added after every study session.

# 🌐 My CCNA & IT Learning Journey (המסע שלי ללימוד רשתות ו-CCNA)

Welcome to my personal study repository! Here, I document my progress based on the **IT Dose** CCNA curriculum. This repository blends foundational networking concepts with practical troubleshooting skills, focusing on how these concepts apply to **Application Support Engineering**.

ברוכים הבאים לתיקיית הלימודים האישית שלי! כאן אני מתעד את ההתקדמות שלי על בסיס קורס ה-CCNA של ערוץ **IT Dose**. תיקייה זו משלבת מושגי יסוד ברשתות יחד עם תרגול מעשי, תוך התמקדות בחיבור של מושגים אלו לעולם ה-**Application Support (תמיכת אפליקציות)**.

---

## 📌 Syllabus & Video Breakdown (סילבוס וחלוקה לפי סרטונים)

---

### 🎬 Part 1: Intro to CCNA vs. Network+ 
* **Hebrew Title:** הכל על CCNA והשוואה network+
* **Core Topic:** Understanding Cisco certifications and comparing CCNA with CompTIA Network+.
* **נושא מרכזי:** הבנת עולם ההסמכות של סיסקו והשוואה בין CCNA ל-Network+ של קומפטיה.

#### 🔑 Key Terms (מושגי מפתח):
* **CCNA (Cisco Certified Network Associate):** Cisco's associate-level networking certification.
  * *בעברית:* הסמכת רשתות ברמת מתחילים/ביניים של חברת סיסקו.
* **Network+:** A vendor-neutral networking certification by CompTIA.
  * *בעברית:* הסמכת רשתות כללית וניטרלית (לא קשורה ליצרן ספציפי) של חברת CompTIA.
* **Vendor-Neutral (Vendor-Free):** Certification or technology not restricted to a single brand.
  * *בעברית:* ניטרלי ליצרן - טכנולוגיה או הסמכה שאינה מוגבלת לחברה או מותג ספציפי.
* **Cisco Packet Tracer:** A network simulation tool used for hands-on practice.
  * *בעברית:* כלי סימולציה והדמיית רשתות של סיסקו המשמש לתרגול מעשי.

#### 💡 Application Support Connection (הקשר לתמיכת אפליקציות):
When supporting enterprise applications, you must understand the underlying network environment. Knowing whether an enterprise uses Cisco infrastructure (vendor-specific protocols) or standard general routing (vendor-neutral) helps you isolate if application communication issues are caused by network-level blocks.
בעבודה כתומך אפליקציות, עליך להבין את סביבת הרשת שעליה האפליקציה רצה. הבנה האם הארגון משתמש בתשתית Cisco (פרוטוקולים ייחודיים) או בניתוב סטנדרטי כללי (Vendor-neutral) תסייע לך לבודד האם בעיות תקשורת באפליקציה נובעות מחסימות ברמת הרשת.

---

### 🎬 Part 2: Network Basics & Cabling
* **Hebrew Title:** מה הן רשתות וסוגי כבלים IT
* **Core Topic:** Network definition, resources/hardware sharing, backup, and physical media (copper vs. fiber).
* **נושא מרכזי:** הגדרת הרשת, שיתוף משאבים וחומרה, גיבויים, ומדיית העברה פיזית (נחושת מול סיבים אופטיים).

#### 🔑 Key Terms (מושגי מפתח):
* **End Devices:** Devices where data originates or terminates (PCs, Phones, Printers).
  * *בעברית:* רכיבי קצה - מכשירים שבהם המידע נוצר או מתקבל (מחשבים, טלפונים, מדפסות).
* **Network Media:** The physical channels carrying data (Cables, Wireless radio waves).
  * *בעברית:* מדית רשת - הערוץ הפיזי שדרכו עובר המידע (כבלים או גלים אלחוטיים).
* **Twisted Pair:** Common copper cables (Cat 5e, Cat 6) used in local networks. Max length is 100 meters.
  * *בעברית:* זוג שזור - כבלי נחושת נפוצים ברשתות מקומיות. מרחק מקסימלי לשידור תקין הוא 100 מטרים.
* **Fiber Optics:** High-speed glass cables transmitting data as light pulses.
  * *בעברית:* סיבים אופטיים - כבלי זכוכית מהירים מאוד המעבירים מידע באמצעות פולסים של אור.
* **NIC (Network Interface Card):** Hardware that translates computer binary (0s and 1s) into physical signals (electricity, light, radio).
  * *בעברית:* כרטיס רשת - חומרה המתרגמת את שפת המחשב (ביטים) לאותות פיזיים (חשמל, אור, רדיו).
* **Network Protocol:** A set of rules that devices must agree on to communicate (e.g., IP).
  * *בעברית:* פרוטוקול רשת - סט חוקים מוסכם המאפשר למכשירים שונים לדבר ביניהם (למשל IP).

#### 💡 Application Support Connection (הקשר לתמיכת אפליקציות):
App slow downs are often blamed on application bugs, but they can be caused by the physical layer! For example, if a database server is connected via a faulty NIC or copper cable over 100 meters, packet loss will occur, causing application queries to timeout.
איטיות באפליקציה מיוחסת לעיתים קרובות לבאגים בקוד, אך היא יכולה להיגרם מהשכבה הפיזית! לדוגמה, אם שרת בסיס הנתונים מחובר דרך כרטיס רשת (NIC) תקול או כבל נחושת שעובר את ה-100 מטרים, ייווצר אובדן מידע (Packet Loss) שיגרום לשאילתות באפליקציה לקרוס (Timeout).

---

### 🎬 Part 3: Casting Types & Duplex modes
* **Hebrew Title:** סוגי הקאסטינג וההבדל בניהם broadcast وال multicast وال unicast وال half-duplex وال full-duplex
* **Core Topic:** Unicast, Multicast, Broadcast, and physical duplex modes (Simplex, Half, Full).
* **נושא מרכזי:** סוגי שידור מידע (חד-נתיב, קבוצתי, לכולם) ומצבי דופלקס (חד-כיווני, דו-כיווני לסירוגין, דו-כיווני מלא).

#### 🔑 Key Terms (מושגי מפתח):
* **Unicast (1-to-1):** Sending data from one sender to one specific receiver.
  * *בעברית:* יוניקאסט (חד-נתיב) - שליחת מידע ממקור אחד ליעד ספציפי אחד.
* **Multicast (1-to-Many):** Sending data to a specific group of devices (e.g., WhatsApp groups).
  * *בעברית:* מולטיקאסט (רב-נתיב) - שליחת מידע לקבוצה מוגדרת של מכשירים.
* **Broadcast (1-to-All):** Sending data to all devices in the network.
  * *בעברית:* ברודקאסט (שידור היצף / לכולם) - שליחת מידע לכל המכשירים הקיימים ברשת.
* **Simplex:** One-way communication only (e.g., Television, Radio).
  * *בעברית:* סימפלקס (חד-כיווני) - תקשורת בכיוון אחד בלבד (כמו טלוויזיה או רדיו).
* **Half-Duplex:** Two-way communication, but NOT at the same time (e.g., Walkie-Talkie).
  * *בעברית:* חצי דופלקס - תקשורת דו-כיוונית אך לא בו-זמנית (כמו מכשיר קשר / ווקי-טוקי).
* **Full-Duplex:** Simultaneous two-way communication (e.g., Phone calls).
  * *בעברית:* דופלקס מלא - תקשורת דו-כיוונית המתרחשת בו-זמנית (כמו שיחת טלפון).

#### 💡 Application Support Connection (הקשר לתמיכת אפליקציות):
Many enterprise applications rely heavily on multicast (e.g., video streaming apps or financial trading platforms). If multicast routing is disabled on the network, the app won't function. Additionally, "Duplex Mismatch" (where a server is set to Full-Duplex and a switch is set to Half-Duplex) causes severe application latency and corrupted files during transfers.
אפליקציות ארגוניות רבות (כמו שידורי וידאו או מערכות מסחר פיננסיות) מסתמכות על מולטיקאסט. אם ניתוב המולטיקאסט חסום ברשת, האפליקציה לא תעבוד. בנוסף, חוסר התאמה בדופלקס (Duplex Mismatch - למשל שרת שמוגדר כ-Full ומתג שמוגדר כ-Half) גורם לאיטיות קשה באפליקציות וקבצים שנפגמים במהלך ההעברה.

---

### 🎬 Part 4: Network Types & Host Roles
* **Hebrew Title:**סוגי רשתות - Network Types ההבדל בין Domain  workgroup
* **Core Topic:** Geographic network classifications (LAN, WAN, SAN, etc.) and Workgroup (Peer-to-Peer) vs. Domain (Client-Server).
* **נושא מרכזי:** סיווג רשתות לפי טווח גאוגרפי וההבדל בין קבוצת עבודה (מחשב מול מחשב) לדומיין (לקוח-שרת).

#### 🔑 Key Terms (מושגי מפתח):
* **LAN (Local Area Network):** High-speed network covering a small geographical area (office, home).
  * *בעברית:* רשת מקומית (LAN) - רשת מהירה המכסה שטח גאוגרפי קטן (בית, משרד).
* **WAN (Wide Area Network):** Connects multiple LANs across cities or countries (e.g., the Internet).
  * *בעברית:* רשת מרחבית (WAN) - רשת המחברת בין רשתות מקומיות בערים או במדינות שונות (כמו האינטרנט).
* **SAN (Storage Area Network):** A dedicated high-speed network for backup and data storage.
  * *בעברית:* רשת אחסון ייעודית (SAN) - רשת מהירה נפרדת המיועדת רק לשמירה, גיבוי ואחזור מידע.
* **Peer-to-Peer / Workgroup:** Network where all devices have equal rights and manage themselves. No central server.
  * *בעברית:* עמית לעמית / קבוצת עבודה (Workgroup) - רשת שבה לכל המחשבים סמכות שווה ואין שרת מרכזי שמנהל אותם.
* **Client-Server / Domain:** Centrally managed network where a Server provides services and controls Client access.
  * *בעברית:* לקוח-שרת / דומיין (Domain) - רשת בעלת ניהול מרכזי שבה שרת ייעודי מספק שירותים ומנהל את הרשאות הלקוחות.

#### 💡 Application Support Connection (הקשר לתמיכת אפליקציות):
In modern IT, enterprise applications are rarely hosted on a single computer. They run in **Client-Server (Domain)** environments. As an App Support engineer, you will manage software licensing, database connections, and user authentication (Single Sign-On / SSO) that are validated by central servers (like Active Directory). Understanding Domain architecture is critical to troubleshooting login failures for users.
בעולם ה-IT המודרני, אפליקציות ארגוניות כמעט לעולם לא מותקנות על מחשב בודד. הן רצות בסביבת **לקוח-שרת (דומיין)**. כאנשי תמיכת אפליקציות, אתם תנהלו רישוי תוכנה, חיבורים לבסיסי נתונים, ואימות משתמשים (SSO / Active Directory) המנוהלים מרחוק ע"י שרתים מרכזיים. הבנת מבנה ה-Domain קריטית לפתרון תקלות התחברות (Login) של משתמשים באפליקציה.
