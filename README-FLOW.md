# FLOW

نسخة مخصصة من Chris Titus Tech WinUtil، بمظهر أسود وبنفسجي وزر تبديل بين العربية والإنجليزية. تبدأ الواجهة بالعربية. تتوفر جميع وظائف النسخة الأصلية؛ لا تُطبّق تعديلات بمجرد فتح الواجهة.

## التشغيل

افتح `Start-FLOW.cmd` أو شغّل `FLOW.ps1` في PowerShell. ستُطلب صلاحيات المسؤول كما في المشروع الأصلي. زر **English / العربية** في الأعلى يبدّل لغة الواجهة خلال الجلسة، دون مسح الاختيارات.

## نطاق الترجمة

تُرجمت أقسام الواجهة والأزرار وأسماء التعديلات والإصلاحات والنصوص الثابتة لإنشاء ISO. أسماء البرامج والتقنيات تبقى كما هي. أوصاف البرامج والتلميحات التقنية المطولة ورسائل العمليات والتشخيص المولدة من المشروع الأصلي قد تظهر بالإنجليزية. تغيير اللغة يخص الجلسة الحالية.

## البناء والتطوير

شغّل `Build-FLOW.ps1` لإعادة بناء الملف التنفيذي من المصدر. عدّل `config/flowLanguages.json` للترجمة و`config/themes.json` للألوان. لا تعدّل `FLOW.ps1` أو `winutil.ps1` مباشرة. سجل التغييرات في `FLOW-CHANGES.md`.

## النشر بأمر مختصر

لم يُنشر رابط عام بعد. بعد توفير مستودع أو نطاق تملكه، يمكن استضافة الإصدار وبناء أمر التنزيل والتشغيل. لا يُستخدم رابط Chris Titus لتشغيل FLOW. التشغيل من ملف محلي يحتفظ بالنسخة المخصصة عند طلب صلاحيات المسؤول؛ التشغيل المحمّل في الذاكرة بدون صلاحيات مسؤول يتوقف برسالة بدل تنزيل النسخة الأصلية.

## Attribution

FLOW is an independent customized build of [Chris Titus Tech WinUtil](https://github.com/ChrisTitusTech/winutil), distributed under the original MIT license in `LICENSE`. It is not an official Chris Titus Tech release. Upstream documentation and support links describe upstream WinUtil. Original CTT PowerShell profile features retain their names because they install the original author's profile.

English: Launch `Start-FLOW.cmd`, accept the Windows administrator prompt, and use the top language button to select English. Build from source with `Build-FLOW.ps1`. Technical descriptions and runtime diagnostics remain in upstream English where no translation is supplied.
