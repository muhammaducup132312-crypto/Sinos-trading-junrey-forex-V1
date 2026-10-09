EDGELOG ANDROID — PROYEK APK PRIBADI GRATIS

Ini adalah proyek Android native berbasis Activity + WebView lokal. Aplikasi membuka aset HTML yang dibundel di APK; bukan website online dan tidak membutuhkan internet saat digunakan. Data jurnal disimpan oleh localStorage WebView di perangkat.

CARA BUILD (gratis, membutuhkan Android SDK/Gradle):
1. Unggah folder proyek ini ke repository GitHub pribadi/public.
2. Buka tab Actions, pilih "Build EdgeLog APK", lalu tekan Run workflow.
3. Setelah selesai, buka hasil run dan unduh artifact "EdgeLog-Android-APK".
4. Ekstrak artifact ZIP, lalu instal app-debug.apk di Android. Jika diminta, izinkan instalasi dari sumber ini.

Alternatif: buka folder ini melalui Android Studio pada komputer yang sudah memiliki Android SDK, lalu jalankan Gradle task :app:assembleDebug.

Tidak ada backend, API, akun pengguna, iklan, pembayaran, atau koneksi trading. Source project disediakan agar bisa dibuild gratis. APK belum dikompilasi di lingkungan pembuatan ini karena Android SDK tidak tersedia.
