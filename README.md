# السلماني - Flutter v3 + GitHub Actions CI

### الجديد في النسخة v3:
- شاشة تسجيل دخول.
- Dashboard بعد تسجيل الدخول.
- شاشة إضافة شحنة كاملة:
  - نوع الشحنة ووسيلة النقل.
  - إضافة مواقع تسليم متعددة (placeholder text).
  - سعر البضاعة.
  - تاريخ الشحنة وتاريخ الوصول.
- GitHub Actions Workflow لبناء APK تلقائي.

### كيفية الاستخدام:
1. ارفع الملفات على GitHub Repository جديد.
2. Push إلى فرع `main` → GitHub Actions سيبني APK.
3. بعد نجاح Workflow → افتح **Actions → Run الأخير → Artifact باسم `alsalmani-apk`** لتحميل APK.
4. استبدل مواقع التسليم بمواقع Google Maps باستخدام API Key لاحقًا.
