# 🤖 Biometric & Physical Performance AI System: Classification & Regression

> مشروع ذكاء اصطناعي متقدم (`Machine Learning & Deep Learning`) يهدف إلى التنبؤ بمستويات أداء اللياقة البدنية والدرجات (Classification) وتوقع مسافات الوثب الطويل (Regression) بناءً على القياسات الحيوية والجسدية.

---

## 🎯 1. Project Overview (نظرة عامة على المشروع)
يتناول هذا المشروع بناء نظام ذكاء اصطناعي متكامل يعتمد على مجموعة بيانات ضخمة تضم **13,392 سجلاً** و **12 متغيراً حيوياً** (تشمل العمر، الجنس، الوزن، نسبة الدهون، الضغط، مؤشرات القوة والمرونة). 
* **الهدف الأساسي (Classification Task):** بناء نموذج تصنيف ذكي للتنبؤ بفئة الأداء (Grades A/B/C/D) بدقة عالية.
* **الهدف الثانوي (Regression Task):** تطوير نموذج انحدار للتنبؤ بمسافة الوثب الطويل (`broad_jump_cm`) استناداً إلى مقاييس القوة البدنية.

---

## 🛠️ 2. Tech Stack & Methodology (الأدوات والمنهجية)
* **Python & Machine Learning Libraries:**
  * **Scikit-learn:** لتطبيق النماذج (`KNN`, `Decision Tree`, `SVM`, `Linear Regression`) وتقييم الأداء.
  * **Neural Networks (MLP Classifier & Regressor):** بناء شبكات عصبية متعددة الطبقات (`[128, 64]`) لتحقيق أفضل دقة.
  * **Pandas & NumPy & Seaborn:** لمعالجة البيانات، تحليل التوزيعات، كشف القيم الشاذة (`IQR Method`)، ورسم مصفوفات الارتباط والـ Confusion Matrix.

---

## 📈 3. Key Model Results & Performance (نتائج النماذج)

### 🔹 أ) مهمة التصنيف (Classification Results):
* **أفضل نموذج:** شبكة عصبية (`Neural Network [128,64]`) حققت:
  * **Test Accuracy:** `74.65%`
  * **F1-Score:** `0.7473`
  * **10-Fold CV Accuracy:** `0.7331 (±0.013)`
* **النموذج البديل القوي:** `SVM (RBF)` بدقة `71.67%`.

### 🔹 ب) مهمة الانحدار (Regression Results):
* **أفضل نموذج:** `MLP Regressor [128,64]` أو `SVR (RBF)`:
  * **$R^2$ Score:** `0.7887` (يفسر حوالي 79% من التباين في البيانات).
  * **RMSE:** `18.39 cm`

---

## 📸 4. Project Visualizations (من لقطات الداشبورد والتحليلات)

### 🔹 أ) توزيعات البيانات وتحليل القيم الشاذة:
![Data Distributions & Outliers](assets/distribution_outliers.png)

### 🔹 ب) مصفوفة الارتباط (Correlation Heatmap):
![Correlation Heatmap](assets/correlation_heatmap.png)

### 🔹 ج) مقارنة النماذج ومصفوفة الارتباك (Confusion Matrix):
![Model Comparison & Confusion Matrix](assets/model_comparison_confusion.png)

---

## 👨‍💻 Author (إعداد)
* **Osama Mohamed** - [GitHub Profile](https://github.com/Osama0Mohamed0DataAnalysis)
