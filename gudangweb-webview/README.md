# GudangWeb Android WebView

Project Android WebView sederhana untuk membuka:

- https://www.gudangweb.com

## Fitur

- Launcher icon memakai file ikon yang dilampirkan pengguna
- WebView full screen
- Pull to refresh
- Tombol back mengikuti histori halaman
- Mendukung upload file dasar dari input web
- Menangani link non-http(s) ke aplikasi eksternal bila tersedia

## Konfigurasi utama

- App name: `GudangWeb`
- Package name: `com.gudangweb.app`
- Min SDK: 24
- Target SDK: 35
- Bahasa: Kotlin

## Cara build APK di Android Studio

1. Buka folder project ini di Android Studio.
2. Tunggu Gradle sync selesai.
3. Jalankan:
   - **Build > Build APK(s)** untuk APK debug, atau
   - **Build > Generate Signed Bundle / APK** untuk APK release.

Output debug umumnya berada di:

- `app/build/outputs/apk/debug/app-debug.apk`

## Catatan

- Project ini belum menyertakan file `gradle-wrapper.jar`, jadi build langsung lewat `./gradlew` mungkin belum bisa sampai wrapper dibuat ulang oleh Android Studio atau Gradle lokal.
- Untuk rilis Play Store, gunakan signing key milik Anda sendiri dan siapkan kebijakan privasi jika diperlukan.
