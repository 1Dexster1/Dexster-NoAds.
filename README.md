<div align="center">
  <img src="fastlane/metadata/android/en-US/images/icon.png" width="128" height="128" alt="Dexster NoAds Icon">
  <h1>Dexster NoAds</h1>
  <p><strong>Smart, privacy-first DNS ad blocker for Android.</strong></p>
  <p>Blocks ads, trackers, malware, and phishing domains locally on your device.</p>

  <a href="https://github.com/1Dexster1/Dexster-NoAds./releases">
    <img src="https://img.shields.io/github/v/release/1Dexster1/Dexster-NoAds.?label=Latest%20Release" alt="Latest Release">
  </a>
  <a href="https://github.com/1Dexster1/Dexster-NoAds./releases">
    <img src="https://img.shields.io/github/downloads/1Dexster1/Dexster-NoAds./total?label=Downloads" alt="Downloads">
  </a>
</div>

---

## English

### What is Dexster NoAds?

Dexster NoAds is an Android app that filters DNS requests locally using a VPN-based engine (or Root Proxy mode if root is available).  
It blocks advertising, tracking, and malicious domains before they load, while keeping your data on your phone.

### Main Features

- System-wide ad and tracker blocking (VPN mode, no root required)
- Optional Root Proxy mode (iptables-based) for rooted devices
- DNS security filtering (malware, phishing, harmful domains)
- DNS-over-HTTPS (DoH) and custom DNS providers
- Per-app bypass/whitelist support
- Custom block/allow domain rules
- Real-time DNS logs and quick search/filtering
- Profile-based protection and scheduling options
- Auto-update checks and in-app update prompt
- Material 3 UI, dark/light theme, dynamic colors
- Multi-language UI

### Download

- **GitHub Releases (recommended):**  
  https://github.com/1Dexster1/Dexster-NoAds./releases
- **F-Droid:**  
  https://f-droid.org/packages/app.pwhs.dexster
- **IzzyOnDroid:**  
  https://apt.izzysoft.de/packages/app.pwhs.dexster

### Which APK should I install?

- `arm64-v8a`: Most modern Android phones
- `armeabi-v7a`: Older 32-bit devices
- `x86_64`: Emulator / specific devices
- `universal`: Works everywhere (larger size)

### Updates

- The app checks for new releases from this public repository:
  `1Dexster1/Dexster-NoAds.`
- You can update by installing the newest APK over the existing app (same signature required).

### Screenshots

<div align="center">
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width="180" alt="Screenshot 1">
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width="180" alt="Screenshot 2">
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" width="180" alt="Screenshot 3">
  <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width="180" alt="Screenshot 4">
</div>

### Build (for developers)

Requirements:

- Android Studio (latest)
- JDK 17+
- Android SDK 36
- Go + gomobile

Basic commands:

```bash
./gradlew buildGoTunnel
./gradlew assembleDebug
```

### License

This project is licensed under **GPL-3.0**.  
See [LICENSE](LICENSE).

---

## العربية

### ما هو Dexster NoAds؟

Dexster NoAds هو تطبيق أندرويد لحجب الإعلانات والمتتبعات عبر فلترة DNS محليًا على جهازك.  
التطبيق يعمل بدون روت عبر وضع الـ VPN المحلي، ويوجد أيضًا وضع Root Proxy للأجهزة التي فيها روت.

### أهم المميزات

- حجب إعلانات وتتبع على مستوى النظام بالكامل
- حماية من نطاقات خبيثة (تصيد، برمجيات ضارة، مواقع خطرة)
- دعم DNS-over-HTTPS وDNS مخصص
- قواعد مخصصة للحجب/السماح (Whitelist/Blocklist)
- استثناء تطبيقات معينة من الفلترة
- سجل DNS مباشر مع بحث وتصفية
- أوضاع حماية متعددة وجدولة
- فحص تحديثات التطبيق وتنبيه عند وجود إصدار جديد
- واجهة حديثة (Material 3) مع وضع ليلي/نهاري
- دعم لغات متعددة

### التحميل

- **من GitHub Releases (الأفضل):**  
  https://github.com/1Dexster1/Dexster-NoAds./releases
- **F-Droid:**  
  https://f-droid.org/packages/app.pwhs.dexster
- **IzzyOnDroid:**  
  https://apt.izzysoft.de/packages/app.pwhs.dexster

### أحمّل أي نسخة APK؟

- `arm64-v8a`: مناسب لمعظم الهواتف الحديثة
- `armeabi-v7a`: للأجهزة القديمة 32-bit
- `x86_64`: غالبًا للمحاكيات وبعض الأجهزة
- `universal`: تعمل على كل الأجهزة لكن حجمها أكبر

### طريقة التحديث

- التطبيق يسحب آخر إصدار من الريبو البابلك:
  `1Dexster1/Dexster-NoAds.`
- حدّث بتثبيت الـ APK الجديد فوق النسخة الحالية (بنفس التوقيع).

### ملاحظات مهمة

- التطبيق لا يعمل كسيرفر خارجي، كل الفلترة تتم محليًا على الهاتف.
- للحصول على أفضل نتيجة، فعّل التطبيق دائمًا واستبعده من تحسين البطارية.

---

## Links

- Releases: https://github.com/1Dexster1/Dexster-NoAds./releases
- Issues: https://github.com/1Dexster1/Dexster-NoAds./issues
- Maintainer: https://github.com/1Dexster1
