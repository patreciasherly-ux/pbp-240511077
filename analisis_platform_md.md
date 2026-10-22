# Analisis Komparatif Platform & Refleksi

## A. Tabel Analisis Komparatif Platform

| Aspek | Web | Desktop | Mobile |
| :--- | :--- | :--- | :--- |
| **Bahasa Utama** | HTML, CSS, JavaScript, TypeScript, PHP, Python | C#, C++, Java, Python, Swift | Java, Kotlin (Android), Swift (iOS), Dart (Flutter) |
| **Arsitektur** | Client-Server (Browser sebagai client, backend server via REST/GraphQL API) | Monolithic atau Client-Server lokal/terdistribusi (native OS API) | Client-Server (Aplikasi mobile sebagai client, backend via REST/gRPC API) |
| **Cara Distribusi** | Melalui URL / Domain (diakses langsung menggunakan web browser) | Installer (.exe, .msi, .dmg, .deb) atau melalui Application Store | App Store resmi (Google Play Store, Apple App Store) atau file APK/IPA |
| **Keunggulan** | Multi-platform tanpa instalasi, pembaruan aplikasi secara terpusat dan real-time | Akses penuh ke hardware/OS, performa sangat tinggi, dapat berjalan offline penuh | Sangat portabel, mendukung sensor hardware bawaan (GPS, kamera, accelerometer, push notification) |
| **Keterbatasan** | Sangat bergantung pada koneksi internet dan batasan kapabilitas browser | Pengembangan multi-platform relatif rumit, harus diinstal manual per perangkat | Ukuran layar terbatas, keterbatasan daya baterai/memori, serta proses review store yang ketat |
| **Contoh Aplikasi** | Trello, Canva, Figma, Google Docs | Visual Studio Code, Spotify Desktop, Adobe Photoshop | WhatsApp Mobile, Gojek, Instagram, TikTok |

## B. Referensi
1. **Mozilla Developer Network (MDN).** *Web technology for developers*. https://developer.mozilla.org/
2. **Android Developers.** *Guide to app architecture*. https://developer.android.com/topic/architecture
3. **Microsoft Learn.** *Desktop application development documentation*. https://learn.microsoft.com/en-us/visualstudio/desktop/

## C. Refleksi

Dari ketiga platform yang dipelajari, platform **Web** merupakan platform yang paling menarik bagi saya untuk dipelajari lebih dalam. Hal ini disebabkan oleh fleksibilitas dan aksesibilitas platform web yang sangat tinggi, di mana aplikasi dapat diakses oleh siapa saja tanpa memerlukan proses instalasi yang rumit. Selain itu, ekosistem pengembangan web berkembang sangat pesat dengan tersedianya berbagai *framework* modern yang memudahkan pembuatan antarmuka responsif dan interaktif.

Tantangan terbesar yang saya hadapi saat melakukan *setup environment* adalah mengonfigurasi variabel lingkungan (*environment variables* / PATH) untuk Java JDK dan Git agar dapat dikenali oleh sistem operasi secara global. Selain itu, ukuran unduhan tools seperti Android Studio yang cukup besar memakan waktu serta sumber daya penyimpanan yang signifikan pada perangkat saya.

Untuk mengatasi tantangan tersebut, saya berencana mengikuti panduan dokumentasi resmi secara teliti dalam mengonfigurasi jalur PATH sistem. Terkait kendala kapasitas penyimpanan dan ukuran instalasi Android Studio, saya akan memanfaatkan perangkat *physical device* (HP Android) melalui fitur *USB Debugging* sebagai pengganti emulator, sehingga beban memori dan ruang penyimpanan pada komputer dapat dikurangi secara optimal.