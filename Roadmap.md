# Oracle APEX ERP Developer কোর্স: সম্পূর্ণ রোডম্যাপ

**মেয়াদ:** ১২ মাস (প্রতিদিন ৩–৪ ঘণ্টা)
**লক্ষ্য:** একদম নতুন থেকে শুরু করে গার্মেন্টস/RMG ইন্ডাস্ট্রির জন্য Oracle APEX দিয়ে ERP বানাতে পারা
**টুল:** Oracle Database (Free / XE), SQL Developer, apex.oracle.com (ফ্রি workspace)

---

## ধাপ ১: কম্পিউটার ও ডাটাবেসের বেসিক (মাস ১)

### সপ্তাহ ১–২
- [ ] কম্পিউটার, অপারেটিং সিস্টেম, ফাইল ম্যানেজমেন্টের বেসিক
- [ ] সফটওয়্যার, ওয়েব অ্যাপ্লিকেশন আর ডাটাবেস কী
- [ ] Client–Server ধারণা
- [ ] Oracle Database Free/XE আর SQL Developer ইনস্টল করা
- [ ] apex.oracle.com-এ ফ্রি workspace খোলা

### সপ্তাহ ৩–৪
- [ ] টেবিল, রো, কলাম
- [ ] Data Type: VARCHAR2, NUMBER, DATE, CLOB, BLOB
- [ ] Primary Key, Foreign Key, Unique, Not Null, Check Constraint
- [ ] Relationship: One-to-One, One-to-Many, Many-to-Many
- [ ] ER Diagram আঁকা (draw.io দিয়ে)
- [ ] Normalization: 1NF, 2NF, 3NF

**প্র্যাকটিস:** একটা লাইব্রেরি ম্যানেজমেন্ট সিস্টেমের ER Diagram বানানো।

---

## ধাপ ২: Oracle SQL (মাস ২–৩)

### মাস ২: বেসিক SQL
- [ ] CREATE, ALTER, DROP, TRUNCATE (DDL)
- [ ] INSERT, UPDATE, DELETE, MERGE (DML)
- [ ] COMMIT, ROLLBACK, SAVEPOINT (TCL)
- [ ] SELECT, WHERE, ORDER BY, DISTINCT
- [ ] Operator: AND, OR, NOT, IN, BETWEEN, LIKE, IS NULL
- [ ] Single Row Function:
  - [ ] Character: UPPER, LOWER, SUBSTR, INSTR, LENGTH, TRIM, REPLACE, LPAD, RPAD
  - [ ] Number: ROUND, TRUNC, MOD
  - [ ] Date: SYSDATE, ADD_MONTHS, MONTHS_BETWEEN, LAST_DAY, NEXT_DAY
  - [ ] Conversion: TO_CHAR, TO_DATE, TO_NUMBER
  - [ ] General: NVL, NVL2, NULLIF, COALESCE, DECODE, CASE

### মাস ৩: অ্যাডভান্সড SQL
- [ ] Aggregate Function: SUM, AVG, COUNT, MIN, MAX
- [ ] GROUP BY, HAVING
- [ ] JOIN: Inner, Left, Right, Full Outer, Self, Cross
- [ ] Subquery: Single row, Multi row, Correlated
- [ ] Set Operator: UNION, UNION ALL, INTERSECT, MINUS
- [ ] View, Materialized View
- [ ] Sequence, Synonym
- [ ] Index (B-Tree, Bitmap, Function-based)
- [ ] Analytic Function: ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD, SUM() OVER
- [ ] Hierarchical Query: CONNECT BY, START WITH
- [ ] PIVOT, UNPIVOT
- [ ] WITH Clause (CTE)

**প্র্যাকটিস:** HR স্কিমার (EMPLOYEES, DEPARTMENTS) উপর ১০০টা কোয়েরি লেখা।
**সার্টিফিকেশন (ঐচ্ছিক):** Oracle Database SQL Certified Associate (1Z0-071)

---

## ধাপ ৩: PL/SQL (মাস ৪–৫)

### মাস ৪: PL/SQL বেসিক
- [ ] PL/SQL Block Structure (DECLARE, BEGIN, EXCEPTION, END)
- [ ] Variable, Constant, %TYPE, %ROWTYPE
- [ ] IF-ELSIF-ELSE, CASE
- [ ] LOOP, WHILE LOOP, FOR LOOP
- [ ] Implicit ও Explicit Cursor
- [ ] Cursor FOR Loop, Parameterized Cursor
- [ ] Exception Handling: Predefined, User-defined, RAISE_APPLICATION_ERROR

### মাস ৫: অ্যাডভান্সড PL/SQL
- [ ] Procedure (IN, OUT, IN OUT Parameter)
- [ ] Function
- [ ] Package (Specification ও Body)
- [ ] Trigger: Row-level, Statement-level, BEFORE/AFTER, INSTEAD OF
- [ ] Collection: Associative Array, Nested Table, VARRAY
- [ ] BULK COLLECT, FORALL
- [ ] Dynamic SQL: EXECUTE IMMEDIATE
- [ ] Autonomous Transaction
- [ ] কাজে লাগে এমন Built-in Package: DBMS_OUTPUT, DBMS_SCHEDULER, UTL_FILE, APEX_MAIL

**প্র্যাকটিস:**
- স্টক IN/OUT হলে অটো ব্যালেন্স আপডেট করার Trigger
- স্যালারি হিসাব করার Package
- অডিট লগ রাখার Trigger

---

## ধাপ ৪: ওয়েবের বেসিক (মাস ৬, প্রথম অর্ধেক)

- [ ] HTML: ট্যাগ, ফর্ম, টেবিল
- [ ] CSS: Selector, Box Model, Flexbox
- [ ] JavaScript: Variable, Function, DOM, Event
- [ ] jQuery বেসিক (APEX-এ লাগে)
- [ ] JSON ফরম্যাট

---

## ধাপ ৫: Oracle APEX (মাস ৬–৮)

### মাস ৬ (দ্বিতীয় অর্ধেক): APEX বেসিক
- [ ] Workspace, Application, Page
- [ ] App Builder, Page Designer
- [ ] Region, Item, Button
- [ ] Shared Components কী
- [ ] Navigation Menu, Breadcrumb
- [ ] Theme, Template, Universal Theme

### মাস ৭: APEX মূল ফিচার
- [ ] Form (Single row, Master-Detail)
- [ ] Classic Report, Interactive Report, Interactive Grid
- [ ] List of Values (LOV): Static, Dynamic, Cascading LOV
- [ ] Validation
- [ ] Computation
- [ ] Process (PL/SQL Process, Form Process)
- [ ] Branch
- [ ] Dynamic Action (Change, Click, Set Value, Refresh, Execute JavaScript)
- [ ] Modal Dialog Page
- [ ] Collection (APEX_COLLECTION)

### মাস ৮: APEX অ্যাডভান্সড
- [ ] Chart: Bar, Line, Pie, Gauge
- [ ] Dashboard বানানো
- [ ] Calendar, Faceted Search, Cards
- [ ] Authentication: APEX Account, Custom Authentication
- [ ] Authorization Scheme (Role-based access control)
- [ ] Session State, Application Item, Substitution String
- [ ] Email পাঠানো (APEX_MAIL)
- [ ] Excel/CSV/PDF রিপোর্ট ডাউনলোড
- [ ] Data Load (Excel থেকে ডাটা ইমপোর্ট)
- [ ] Plugin ব্যবহার করা
- [ ] Application Export/Import, Deployment

**সার্টিফিকেশন (ঐচ্ছিক):** Oracle APEX Cloud Developer Certified Professional

---

## ধাপ ৬: REST API ও ইন্টিগ্রেশন (মাস ৯)

- [ ] REST API কী: GET, POST, PUT, DELETE
- [ ] ORDS (Oracle REST Data Services)
- [ ] APEX-এ RESTful Service বানানো
- [ ] REST Data Source (Web Source Module) দিয়ে বাইরের API থেকে ডাটা আনা
- [ ] APEX_WEB_SERVICE, APEX_JSON
- [ ] Postman দিয়ে API টেস্ট করা
- [ ] Database Link (এক ডাটাবেস থেকে আরেক ডাটাবেসে)

---

## ধাপ ৭: পারফরম্যান্স ও সিকিউরিটি (মাস ১০, প্রথম অর্ধেক)

- [ ] Explain Plan পড়া
- [ ] SQL Tuning, Index ঠিকমতো ব্যবহার করা
- [ ] Bind Variable
- [ ] PL/SQL Optimization
- [ ] SQL Injection প্রতিরোধ
- [ ] Session State Protection, Item Encryption
- [ ] Data Validation, Audit Trail
- [ ] User, Role, Privilege (GRANT, REVOKE)

---

## ধাপ ৮: গার্মেন্টস/RMG ইন্ডাস্ট্রির জ্ঞান (মাস ১০, দ্বিতীয় অর্ধেক)

- [ ] গার্মেন্টসের পুরো ফ্লো: Buyer → Order → Sample → Production → Shipment
- [ ] **Merchandising:** Buyer, Style, Order, Costing
- [ ] **PI (Proforma Invoice)**, LC (Letter of Credit)
- [ ] **BOM (Bill of Materials):** কাপড়, সুতা, বোতাম, জিপার ইত্যাদির হিসাব
- [ ] **TNA (Time and Action):** অর্ডারের টাইমলাইন
- [ ] **Sample Development**
- [ ] **Planning:** লাইন প্ল্যানিং, ক্যাপাসিটি
- [ ] **Commercial:** Export, Import, LC, Shipment ডকুমেন্ট
- [ ] **Purchase:** Requisition, PO (Purchase Order)
- [ ] **Inventory/Store:** Fabric, Yarn, Accessories, Chemical, Finished Goods
- [ ] **Production:** Cutting, Sewing, Washing, Finishing
- [ ] **Yarn Dyeing, Textile**
- [ ] **Efficiency, Target vs Achievement, SMV**
- [ ] **Accounts:** Voucher, Ledger, Trial Balance বেসিক

---

## ধাপ ৯: রিয়েল প্রজেক্ট (মাস ১১–১২)

### প্রজেক্ট ১: Inventory Management System
- [ ] Item Master, Category, Unit, Supplier
- [ ] Receive (GRN), Issue, Transfer, Return
- [ ] Stock Balance রিপোর্ট
- [ ] Low Stock Alert

### প্রজেক্ট ২: Garments Order Tracking System
- [ ] Buyer, Style, Order Entry
- [ ] PI তৈরি
- [ ] BOM তৈরি
- [ ] TNA ট্র্যাকিং (কোন কাজ দেরি হচ্ছে দেখানো)
- [ ] Buyer-wise, Order-wise, Style-wise রিপোর্ট

### প্রজেক্ট ৩: Production Monitoring Dashboard
- [ ] Line-wise ঘণ্টাভিত্তিক প্রোডাকশন এন্ট্রি
- [ ] Target vs Achievement চার্ট
- [ ] Efficiency রিপোর্ট
- [ ] ম্যানেজমেন্টের জন্য Dashboard

### প্রজেক্ট ৪: Mini Garments ERP (সব একসাথে)
- [ ] Merchandising + Purchase + Inventory + Production মডিউল একসাথে
- [ ] Role-based login (Merchandiser, Store Keeper, Production Manager, Admin)
- [ ] Purchase Requisition → PO → Receive → Issue → Consumption ফ্লো
- [ ] REST API দিয়ে একটা ডাটা বাইরে দেখানো

---

## ধাপ ১০: জবের প্রস্তুতি (মাস ১২-এর শেষ দিকে)

- [ ] সব প্রজেক্ট apex.oracle.com-এ লাইভ রাখা
- [ ] GitHub-এ SQL/PL/SQL কোড আপলোড
- [ ] প্রতিটা প্রজেক্টের স্ক্রিনশট আর ছোট ডকুমেন্টেশন
- [ ] UAT, User Manual, Training ডকুমেন্ট লেখার প্র্যাকটিস
- [ ] CV-তে প্রজেক্টের লিংক দেওয়া
- [ ] SQL/PL/SQL ইন্টারভিউ প্রশ্ন প্র্যাকটিস
- [ ] LinkedIn প্রোফাইল আপডেট

---

## শেখার উৎস

| বিষয় | উৎস |
|---|---|
| SQL, PL/SQL | Oracle Live SQL (livesql.oracle.com), Oracle MyLearn |
| APEX | apex.oracle.com, Oracle APEX ডকুমেন্টেশন, Oracle MyLearn-এর APEX কোর্স |
| ভিডিও | YouTube-এ "Oracle APEX Tutorial", "Oracle PL/SQL Tutorial" |
| প্র্যাকটিস | HackerRank SQL, LeetCode Database |

---

## ক্যারিয়ার পথ

| সময় | পদ |
|---|---|
| ১ বছর শেখার পর | Trainee / Junior Oracle APEX Developer |
| ১–৩ বছর | Oracle APEX Developer |
| ৩+ বছর | Senior Oracle APEX / ERP Developer |
| ৫+ বছর | ERP Team Lead / Solution Architect |
