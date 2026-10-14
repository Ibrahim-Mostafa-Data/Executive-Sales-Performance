# 📊 Superstore Sales & Profitability Analytics Hub

![Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power_Query-F2C811?style=for-the-badge&logo=microsoft&logoColor=black)
![Power Pivot](https://img.shields.io/badge/Power_Pivot-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0176D3?style=for-the-badge&logo=salesforce&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

### 👤 Created By:
**Ebrahim Mustafa** — *Data Analyst & BI Analyst*

---

## 📌 نبذة عن المشروع (Project Overview)
يهدف هذا المشروع إلى تقديم تحليل شامل وعميق لبيانات المبيعات والأرباح لشركة **Superstore** (أكثر من 9,900 معاملة بيع بقيمة تجاوزت **2.29 مليون دولار**)[cite: 13, 14, 15, 16, 17]. 

تم بناء التقرير بالكامل باستخدام **Microsoft Excel** باتباع أحدث الممارسات الاحترافية لتطوير لوحات مؤشرات الأداء التفاعلية (Interactive Business Intelligence Dashboards)[cite: 14, 15, 16, 17]، مع بناء رحلة متكاملة للبيانات بدءاً من البيانات الخام، مروراً بـ Power Query و Power Pivot والتشارش التفاعلية، وحتى استخراج التوصيات الاستراتيجية[cite: 14, 15, 16, 17, 18, 19, 20, 21, 22].

---

## 🛠️ أدوات وتقنيات العمل (Tech Stack & Workflow)
* **Power Query:** لسحب البيانات الخام وتنظيفها وفصل الجداول المسطحة إلى نموذج أبعاد (Star Schema)[cite: 20, 21, 22].
* **Power Pivot & DAX:** لبناء العلاقات بين الجداول وصياغة المقاييس الحسابية المتقدمة (Dynamic DAX Measures)[cite: 18].
* **Pivot Tables & Summaries:** لتجميع البيانات الحسابية المعتمدة لتقديمها للشارتات والبطاقات[cite: 19].
* **Pivot Charts & Custom Visuals:** لإنشاء الرسوم البيانية المتنوعة وتربيطها بالسلايسرز التفاعلية (Slicers)[cite: 14, 15, 16, 17].

---

## 🚀 رحلة معالجة وتطوير البيانات (Data Pipeline Roadmap)

### 1️⃣ البيانات الخام (Raw Data)
* **الوصف:** جدول مسطح (Flat Table) يحتوي على كربكة وعشوائية في البيانات، تواريخ غير مضبوطة (`########`)، عدم وجود فصل بين الأبعاد والمبيعات، ومشاكل في التنسيقات[cite: 22].
![Raw Data](raw-data.png)

---

### 2️⃣ تنظيف وتجهيز البيانات (Data Cleaning & Power Query)
* **الوصف:** استيراد البيانات إلى **Power Query**، معالجة المشاكل وإعادة هيكلة جدول المعاملات، وتفكيك الجدول المسطح إلى نموذج أبعاد احترافي (**Star Schema**) يحتوي على 4 أبعاد رئيسية (`Fact_Sales`, `Dim_Customer`, `Dim_Product`, `Dim_Date`)[cite: 20, 21].
![Power Query Cleaning](power_query_cleaning.png)
![Power Query Dimensions](power-query-dimensions.png)

---

### 3
