# 💼 Enhanced Customer Segmentation & Cluster Analysis (RFM)

<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
</div>

## 📌 نبذة عن المشروع | Overview
مشروع متقدم في مجال ذكاء الأعمال وعلم البيانات، يهدف إلى تحليل سلوك المستهلكين وتقسيم عملاء المتاجر الإلكترونية إلى مجموعات تسويقية متجانسة. يعتمد المشروع على دمج التحليل الإحصائي التقليدي مع خوارزميات **التعلم غير الخاضع للإشراف (Unsupervised Learning)** لبناء استراتيجيات تسويقية مخصصة بناءً على القيمة الشرائية للعملاء.

---

## 🛠️ خط الإنتاج الهندسي ومعالجة البيانات | Data Pipeline

يتضمن المشروع تطبيقاً معيارياً لأقوى الأساليب الرياضية في تجميع البيانات:

1. **RFM Metrics Generation (بناء مؤشرات السلوك):**
   * حساب ثلاثة مؤشرات أساسية لكل عميل: **Recency** (حداثة آخر الشراء)، **Frequency** (معدل تكرار الشراء)، و **Monetary** (إجمالي حجم الإنفاق المالي).

2. **Advanced Data Scaling (تقييس البيانات):**
   * استخدام **RobustScaler** لتجهيز البيانات وتقييسها برمجياً لضمان تحييد تأثير القيم المتطرفة (Outliers) الناتجة عن تفاوت القوة الشرائية بين العملاء.

3. **Dimensionality Reduction (تقليص الأبعاد):**
   * تطبيق خوارزمية **PCA (Principal Component Analysis)** لتقليص أبعاد البيانات المعقدة وتبسيطها مع الحفاظ على أعلى نسبة تباين إحصائي ممكنة لتسهيل عملية التجميع البياني.

4. **Multi-Model Clustering (المقارنة بين الخوارزميات):**
   * تطبيق واختبار خوارزمية **K-Means Clustering** وتحديد العدد الأمثل للمجموعات عبر مقياس (Silhouette Score).
   * تطبيق خوارزمية **DBSCAN** المقاومة للضوضاء لمقارنة توزيع المجموعات وتحديد العملاء غير النمطيين في سلوك الشراء.

5. **Business Labeling (التصنيف التجاري):**
   * تحويل المجموعات الرياضية الناتجة إلى تصنيفات تجارية مفهومة لصناع القرار مثل: (High Value Loyal Customers, Inactive At Risk Customers, Growth Potential).

---

## 🚀 التقنيات المستخدمة | Tech Stack
* **Python** (لغة البرمجة الأساسية)
* **Pandas & NumPy** (لمعالجة المصفوفات وبناء الجداول الرياضية للأداء)
* **Scikit-Learn** (لتطبيق خوارزميات التجميع K-Means, DBSCAN وتهيئة RobustScaler, PCA)
* **Matplotlib & Seaborn** (لرسم المجموعات والتوزيعات البيانية ثلاثية الأبعاد)
