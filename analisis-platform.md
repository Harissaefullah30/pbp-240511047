# Tugas 1 - Eksplorasi Platform & Setup Environment

## 1. Analisis Komparatif Platform

Berikut adalah tabel perbandingan antara platform Web, Desktop, dan Mobile:

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa utama** | HTML, CSS, JavaScript | C++, C#, Java, Python | Kotlin, Swift, Java (Android), Dart |
| **Arsitektur** | Client-Server (Berjalan di atas protokol HTTP melalui browser) | Standalone (Aplikasi berjalan mandiri di atas sistem operasi perangkat) | Client-Server / Hybrid (Berjalan di OS mobile dengan optimasi memori) |
| **Cara distribusi** | Melalui Web Server (diakses via URL/Browser) | Melalui installer (file .exe, .msi, .dmg) atau App Store | Melalui App Store (Google Play Store, Apple App Store) |
| **Keunggulan** | Bisa diakses di mana saja tanpa perlu diinstal, asal ada internet. | Performa tinggi, akses hardware langsung, dan bisa berjalan tanpa internet. | Portabilitas tinggi, praktis dibawa ke mana-mana, dan akses langsung ke sensor (GPS, kamera). |
| **Keterbatasan** | Bergantung pada koneksi internet dan performa browser. | Perlu proses instalasi, kompatibilitas OS terbatas, dan update manual. | Layar kecil, boros baterai, dan memori terbatas. |
| **Contoh aplikasi** | Google Docs, YouTube | Visual Studio Code, Steam | TikTok, WhatsApp, Mobile Legends |

### Referensi:
1. MDN Web Docs. (2023). *Web technology for developers*. Mozilla. Diakses dari https://developer.mozilla.org/
2. Google Developers. (2024). *Android Platform Architecture*. Diakses dari https://developer.android.com/guide/platform
3. Microsoft Docs. (2024). *What is the .NET Desktop Runtime?*. Diakses dari https://learn.microsoft.com/

---

## 2. Refleksi

**1. Platform mana yang paling menarik untuk dipelajari? Mengapa?**
Menurut saya, platform Mobile adalah yang paling menarik untuk dipelajari. Alasannya karena pengguna smartphone saat ini sangat masif dan aplikasi mobile memiliki akses langsung ke fitur perangkat keras seperti kamera dan GPS. Tantangan dalam mendesain UI/UX untuk layar kecil dan mengoptimalkan performa di tengah keterbatasan memori perangkat juga membuat proses belajarnya menjadi sangat menantang dan relevan untuk masa depan.

**2. Apa tantangan terbesar saat setup environment?**
Tantangan terbesar yang saya alami saat setup environment adalah mengatur variabel path pada Java JDK. Awalnya, perintah `java -version` di Command Prompt tidak mengeluarkan hasil apa pun karena file Java yang terdeteksi hanyalah *shortcut* (javapath) dari Oracle, bukan JDK yang sebenarnya. Saya sempat merasa sedikit bingung dan panik, namun hal itu justru menyadarkan saya bahwa setup awal memang sangat membutuhkan ketelitian, terutama dalam hal konfigurasi PATH.

**3. Bagaimana rencana Anda mengatasi tantangan tersebut?**
Untuk mengatasinya, saya mempelajari kembali dokumentasi dan menginstal ulang JDK versi LTS (JDK 21). Saya memastikan opsi `Set JAVA_HOME variable` serta `Modify PATH variable` dicentang pada layar *Custom Setup*. Setelah itu, saya menutup dan membuka ulang Command Prompt agar sistem memuat variabel lingkungan yang baru. Ke depannya, saya akan lebih teliti lagi saat mengikuti setiap langkah instalasi agar alat pengembangan bisa langsung berjalan dengan baik.