تشغيل النظام على iPhone وAndroid — Local Only

خصوصية البيانات:
- لا يوجد إرسال أو مزامنة أو قاعدة بيانات مركزية.
- كل مفتش يرى فقط ما هو محفوظ على جهازه.
- الصور وGPS والتوقيع والتقارير تبقى محلياً على الجهاز.
- GitHub Pages يستضيف ملفات التطبيق فقط.

رفع الملفات إلى GitHub Pages:
1) أنشئ Repository جديداً، مثلاً: field-inspection
2) ارفع محتويات هذه الحزمة كما هي إلى جذر الـRepository:
   index.html
   manifest.webmanifest
   sw.js
   icons/
3) من Settings > Pages اختر:
   Deploy from a branch
   Branch: main
   Folder: / (root)
4) احفظ وانتظر ظهور رابط HTTPS.
5) افتح الرابط من Safari على iPhone أو Chrome على Android.
6) اسمح بالكاميرا والموقع عند الطلب.
7) iPhone: Share > Add to Home Screen
   Android: Menu > Add to Home screen / Install app

مهم:
- لا تفتح index.html كملف محلي على iPhone؛ استخدم رابط HTTPS.
- حذف بيانات Safari/Chrome أو حذف بيانات الـWeb App قد يمسح التقارير المحلية.
- احفظ التقرير النهائي PDF/صورة بعد كل تفتيش إذا كان مطلوباً كنسخة رسمية.
