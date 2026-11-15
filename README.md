# Tayaar Print Agent — Downloads

برنامج طيّار للطباعة: يُثبَّت على جهاز ويندوز في المستودع ويطبع البوالص والملصقات تلقائياً على الطابعات الموصولة به.

**[تحميل أحدث نسخة / Download the latest version](https://github.com/BetaLabApp/tayaar-print-agent-releases/releases/latest/download/TayaarPrintAgent-win-x64.zip)** — Windows 10/11, 64-bit

## التثبيت

1. فك ضغط المجلد كاملاً في مكان ثابت على جهاز المستودع (مثال: `C:\Tayaar`). يجب أن يبقى الملفان `TayaarPrintAgent.exe` و `SumatraPDF.exe` في نفس المجلد.
2. من لوحة طيّار: الإعدادات ← أجهزة الطباعة ← «إضافة جهاز»، فيظهر رمز الربط.
3. انقر بالزر الأيمن على `TayaarPrintAgent.exe` واختر «تشغيل كمسؤول»، ثم أدخل رمز الربط.
4. يعمل البرنامج تلقائياً مع تشغيل الجهاز، وتظهر أيقونته بجوار الساعة، وتظهر طابعات الجهاز في اللوحة خلال ثوانٍ.

عند أول تشغيل قد تظهر رسالة «Windows protected your PC»: اضغط «More info» ثم «Run anyway».

## Install

1. Extract the whole folder to a permanent location on the warehouse PC (e.g. `C:\Tayaar`). Keep `TayaarPrintAgent.exe` and `SumatraPDF.exe` in the same folder.
2. In the Tayaar dashboard: Settings → Print devices → "Add device" to get a pairing code.
3. Right-click `TayaarPrintAgent.exe` → "Run as administrator", then enter the pairing code.
4. The agent starts with Windows, shows a tray icon, and the PC's printers appear in the dashboard within seconds.

On first run Windows may show "Windows protected your PC": click "More info", then "Run anyway".

## Third-party software

The download bundles an unmodified copy of [SumatraPDF](https://www.sumatrapdfreader.org/) 3.5.2, used to print PDF documents silently. SumatraPDF is licensed under the GNU GPL v3; its licence text and notice are included in the `licenses` folder of the download, and its source code is available from the SumatraPDF project.
