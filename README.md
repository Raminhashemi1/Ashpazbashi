# آشپزباشی v0.2.2 — Final Test

این نسخه شامل:
- رابط فارسی و RTL
- Onboarding چهارمرحله‌ای
- ورود مهمان/محلی
- Trial ده‌روزه
- Paywall با پلن ماهانه، سالانه و مادام‌العمر (Demo)
- Home و جستجو
- دستور پخت و حالت آشپزی مرحله‌ای
- علاقه‌مندی‌ها
- Shopping List پایدار
- AI Chef محلی نمونه
- پروفایل و وضعیت اشتراک
- لوگوی طراحی‌شده آشپزباشی
- همان لوگو به‌عنوان Launcher Icon واقعی Android/iOS

## اجرا
این بسته source پروژه است. روی سیستمی که Flutter SDK نصب است:

```bash
flutter create . --platforms=android,ios
flutter pub get
dart run flutter_launcher_icons
flutter run
```

## ساخت APK
روی سیستمی که Flutter و Android SDK نصب است:

```bash
./build_android.sh
```

خروجی:
`build/app/outputs/flutter-apk/app-release.apk`

GitHub Actions نیز در `.github/workflows/android.yml` تنظیم شده است.