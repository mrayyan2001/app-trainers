# أسئلة مقابلات Data Science

## أسئلة حول البيانات (Data Questions):

### شو الفرق بين Structured Data و Unstructured Data؟

- Structured Data: بيانات مرتبة بجداول، زي البيانات الموجودة بقاعدة بيانات SQL.
- Unstructured Data: بيانات ما إلها شكل محدد زي الصور، الفيديوهات، أو النصوص الكبيرة، وبتحتاج أدوات خاصة للتعامل معها.

### شو هو Data Cleaning؟

- هي عملية ترتيب وتنظيف البيانات، زي إزالة الأخطاء، ترتيب البيانات، أو التعامل مع Missing Data عشان تكون جاهزة للتحليل.

### كيف تتعامل مع Missing Data؟

- ممكن أحذف الـ Rows أو Columns اللي فيها Missing Data إذا كانت مش كثيرة. إذا كانت مهمة، بعوضها باستخدام Mean، Median، أو Mode حسب طبيعة البيانات.

### شو الفرق بين Overfitting و Underfitting؟

- Overfitting: لما النموذج يتعلم كل تفاصيل Training Data لدرجة إنه ما يشتغل منيح مع Testing Data.
- Underfitting: لما النموذج ما يتعلم كفاية، فبيكون ضعيف سواء على Training Data أو Testing Data.

### كيف تتعامل مع Imbalanced Data؟

- باستخدام تقنيات زي Oversampling (SMOTE)، UnderSampling.

---

## أسئلة تحليل البيانات (Data Analysis):

### شو الفرق بين Descriptive Statistics و Inferential Statistics؟

- Descriptive Statistics: زي Mean و Standard Deviation لتلخيص البيانات.
- Inferential Statistics: بيخليني أستنتج معلومات عن Population كبيرة باستخدام Sample صغيرة.

### إيش هو p-value؟

- رقم بيوضح إذا كانت النتيجة معنوية أو بس صدفة. إذا الـ p-value أقل من 0.05، معناته في علاقة معنوية بين المتغيرات.

### شو الفرق بين Correlation و Causation؟

- Correlation: لما يكون في علاقة بين متغيرين، بس مو شرط يكون واحد سبب الثاني.
- Causation: لما يكون واحد من المتغيرات هو السبب المباشر للتأثير على الثاني.

### شو هو A/B Testing؟

- تجربة بنقارن فيها بين نسختين (A و B) من منتج أو ميزة، وبنختار الأفضل بناءً على النتائج.

---

## أسئلة تعلم الآلة (Machine Learning):

### شو الفرق بين Supervised Learning و Unsupervised Learning؟

- Supervised Learning: النموذج بتدرب على بيانات ومعاها Labels، زي تصنيف الصور.
- Unsupervised Learning: النموذج بتدرب على بيانات بدون Labels، زي Clustering.

### شو هي أشهر خوارزميات Machine Learning؟

- Classification: Logistic Regression، Decision Trees، SVM.
- Regression: Linear Regression، Polynomial Regression.
- Clustering: K-Means، Hierarchical Clustering.

### كيف تختار أفضل نموذج للبيانات؟

- باستخدام Metrics زي Accuracy، Precision، Recall، أو F1 Score حسب طبيعة المشكلة.

### شو هي تقنيات Dimensionality Reduction؟

- PCA (Principal Component Analysis).
- LDA (Linear Discriminant Analysis).

### شو هو Cross-Validation؟

- تقنية لتقييم أداء النموذج عن طريق تقسيم البيانات لمجموعات تدريب واختبار متعددة.

---

## أسئلة البرمجة وتحليل البيانات:

### شو هي أشهر المكتبات في علم البيانات؟

- **Pandas**: لمعالجة وتحليل البيانات زي DataFrames.
- **NumPy**: للعمليات الرياضية والمصفوفات.
- **Matplotlib**: لإنشاء الرسوم البيانية والتصورات البسيطة.
- **Seaborn**: لتصميم رسوم بيانية إحصائية متقدمة.
- **Scikit-learn**: لتعلم الآلة
- **TensorFlow** و **PyTorch**: لتطوير النماذج العميقة.

### شو التقنيات المستخدمة بالBig Data؟

- تقنيات زي Hadoop و Spark.

### كيف تتعامل مع Time Series Data؟

- باستخدام مكتبات زي statsmodels أو Prophet وتحليل الاتجاهات الموسمية.

---

## أسئلة متعلقة بالنشر (Deployment):

### شو الخطوات الأساسية لنشر نموذج Machine Learning؟

1. تدريب النموذج.
2. تقييم الأداء.
3. حفظ النموذج (Model Serialization).
4. نشره كـ API باستخدام Flask أو FastAPI.
5. مراقبة الأداء بعد النشر.

### شو الفرق بين Batch Processing و Real-Time Processing؟

- Batch Processing: معالجة البيانات دفعة واحدة.
- Real-Time Processing: معالجة البيانات فور وصولها.

---
