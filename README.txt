SHUNCENG INVENTRA - Android WebView project

Project ini membungkus Google Apps Script Web App yang diberikan menjadi aplikasi Android.
Package: com.shunceng.inventra
App label: SHUNCENG INVENTRA
Minimum Android: 6.0 (API 23)

CARA MEMBUAT APK:
1. Instal Android Studio di komputer.
2. Ekstrak folder SHUNCENG_INVENTRA_APK_Project.zip.
3. Android Studio > Open > pilih folder SHUNCENG_INVENTRA_APK_Project.
4. Tunggu Gradle Sync selesai. Jika diminta, izinkan Android Studio mengunduh Android SDK / Gradle.
5. Pilih Build > Build Bundle(s) / APK(s) > Build APK(s).
6. Setelah selesai, klik "locate" pada notifikasi Build. File biasanya ada di:
   app/build/outputs/apk/debug/app-debug.apk
7. Pindahkan APK ke HP Android dan instal. Jika diminta, izinkan "Install unknown apps"
   untuk aplikasi File Manager / browser yang digunakan.

CATATAN:
- HP harus terhubung internet.
- APK ini memuat URL Apps Script yang disediakan pengguna.
- Data tetap berada di Google Sheets sesuai backend Apps Script.
- Untuk membagikan APK ke banyak pengguna, buat signed release APK melalui
  Build > Generate Signed Bundle / APK.
- Jika proses login Google ditolak di WebView oleh kebijakan Google, diperlukan
  penyesuaian alur autentikasi atau pembukaan login melalui browser eksternal.
- Perubahan kode website Apps Script tetap diperbarui dari server; APK tidak perlu
  dibuat ulang untuk perubahan konten web, selama URL tetap sama.
