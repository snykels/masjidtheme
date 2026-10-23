# القوس التراثي

ثيم تراثي بألوان فحمية وعاجية ولمسات ذهبية.

## النسخة الحالية
- Theme version: 3
- Layout schema: extended-v1
- manifest.json: جاهز
- layout/layout.json: جاهز
- assets/portrait.webp: موجود 1080×1920
- assets/landscape.webp: موجود 1920×1080
- thumbnail.webp: موجود
- dist/heritage_arch.masjidtheme: يعاد بناؤه مع كل تحديث

## ملاحظات v3
- أضيف Layout مستقل للـ landscape والـ portrait بإحداثيات normalized من 0 إلى 1.
- Landscape: جدول الصلاة يسار، الساعة/التاريخ/العد التنازلي يمين.
- Portrait: الساعة والتاريخ بالأعلى، جدول الصلاة بالأسفل، والعد التنازلي بين العصر والمغرب.
- تمت إضافة weekday كعنصر مستقل.
- countdown يستخدم compact بدون progress.
- الساعة الرئيسية بدون AM/PM، وأوقات الصلاة مجهزة لإظهار AM/PM بشكل مستقل عند دعم المحرك.
- المفاتيح القديمة ما زالت موجودة كـ fallback للتوافق مع التطبيق الحالي.
- لا توجد خطوط خارجية داخل الحزمة حتى يكتمل دعم تحميل الخطوط من الثيم.

## الخلفيات
- assets/portrait.webp
- assets/landscape.webp

يجب على التطبيق اختيار الخلفية بناءً على اتجاه الـ layout النهائي بعد RotatedLayout، وليس اتجاه الجهاز الخام.
