# القوس التراثي

## النسخة الحالية
- Theme version: 4
- Schema version: 1
- Theme number: 1
- Layout schema: extended-v1

## الملفات
- manifest.json
- thumbnail.webp
- assets/portrait.webp — 1080×1920
- assets/landscape.webp — 1920×1080
- layout/layout.json
- dist/heritage_arch.masjidtheme

## v4
تمت مطابقة layout.json مع المفاتيح التي يقرأها محرك Al-Masjid الحالي فعليًا:
- timeConfig.clockShowAmPm
- timeConfig.prayerShowAmPm
- timeConfig.amPmFontSizeSp
- layouts.landscape / layouts.portrait
- prayerTable.rowSpacingDp
- prayerTable.rowGapAfter
- prayerTable.gapDp
- countdown compact
- weekday كعنصر مستقل

تم حذف المفاتيح التي لا يقرأها المحرك حاليًا مثل contentDirection وdateArea وgapSize.

ملاحظة تقنية:
المحرك الحالي يقوم بقراءة x/y/w/h من JSON لكنه لا يطبّق bounds على Compose حتى الآن؛ لذلك المواضع المحفوظة هنا جاهزة للمحرك عند اكتمال تطبيقها في MainScreen.
