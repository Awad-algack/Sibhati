# سبحتي – SUBHATI

## تشغيل نسخة الويب
افتح `www/index.html` أو انشر مجلد `www` على استضافة صفحات ثابتة.

## بناء Android
يتطلب Node.js وJava/Android SDK. نفّذ:

```bash
npm install
npx cap add android
npx cap sync android
cd android
./gradlew assembleDebug
```

ملف APK التجريبي الناتج عادةً: `android/app/build/outputs/apk/debug/app-debug.apk`.

ملاحظة: لم يتم تنفيذ بناء APK في هذه الجلسة.
