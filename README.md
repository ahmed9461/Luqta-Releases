# Luqta — Windows releases

This public repository distributes Luqta Windows installers and update assets only. Source code, development history, credentials, sessions, and user data are not published here.

Download **LuqtaDesktop-win-x64-Setup.exe** from [the latest release](https://github.com/ahmed9461/Luqta-Releases/releases/latest). Windows x64 only; the installer includes the runtime.

## التثبيت والتحديث

حمّل ملف **LuqtaDesktop-win-x64-Setup.exe** من أحدث إصدار، ثم ثبّته وافتح Luqta. المستخدم الجديد يدخل كود التفعيل الخاص به.

لمستخدمي النسخة القديمة 1.1.0: اختر خروج من أيقونة Luqta، وأزل تثبيت النسخة القديمة مع إبقاء `%LOCALAPPDATA%\Luqta`، ثم ثبّت الإصدار الجديد تحت حساب Windows نفسه. هذا الانتقال اليدوي مطلوب مرة واحدة.

التحديث العادي يُنزّل في الخلفية ويُطبّق بعد الخروج الآمن. التحديث الكبير يعرض تنزيل الآن، ونسبة التنزيل الفعلية، ثم تحديث لإعادة التشغيل بأمان. تبقى الجلسة والإعدادات والصور المعلقة في مجلد بيانات منفصل.

## WhatsApp

يدعم Luqta ربط حساب WhatsApp عبر QR وإرسال اللقطات مباشرة إلى محادثة أو مجموعة تختارها. افتح «إعدادات الإرسال»، اختر WhatsApp، واربط الحساب ثم احفظ وجهة الإرسال. تبقى طريقة الإرسال السابقة متاحة.

**Alt + C** يلتقط الشاشة فقط، و**Alt + S** يرسل آخر لقطة جاهزة. تُحفظ جلسة الحساب محليًا بشكل محمي، ولا يحتاج الإرسال فتح متصفح أو نافذة WhatsApp.

Update metadata is authenticated with RSA-PSS/SHA-256, and packages are verified before application. A trusted Windows Authenticode publisher certificate is not currently available. Never disable Windows security for installation.

GitHub's automatic source archives contain only this release README, not the private application source. Download the installer asset to use Luqta.
