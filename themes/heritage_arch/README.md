# القوس التراثي

## النسخة الحالية
- Theme version: 10
- Layout schema: extended-v1

## v10
- دعم fontRole وfontWeight لكل عنصر.
- weekday والشهور يستخدمان خط المسجد/الثلث الموجود داخل التطبيق كـ fallback.
- الساعة تستخدم دور clock.
- اليوم/السنة يستخدمان دور date.
- جهزت مسارات منفصلة للخطوط المستقبلية:
  - fonts/clock.ttf
  - fonts/prayer_time.ttf
  - fonts/prayer_name.ttf
  - fonts/prayer_english.ttf
  - fonts/date.ttf
  - fonts/weekday.ttf
- إذا الملفات غير موجودة، التطبيق يرجع تلقائيًا للخطوط الداخلية بدون Crash.
- لا يوجد اسم الشركة أو ALRBEA TIMES داخل الثيم.
