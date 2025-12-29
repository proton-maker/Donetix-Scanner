# Donetix Scan

**Developer**: Rizky Alfi Syahrin

**Donetix Scan** is a high-performance, enterprise-grade mobile application designed for seamless event ticket validation and attendance management. Built with modern hybrid mobile technologies, it delivers a robust, offline-first scanning experience for Android devices.

## 🚀 Key Features

### 🎫 Advanced Ticket Scanning
*   **High-Speed Scanning**: Utilizes **Google ML Kit** for millisecond-latency barcode and QR code detection.
*   **Multi-Zone Support**: Configurable scanning for specific access rings/zones (e.g., Gate A, VIP Area).
*   **Duplicate Detection**: Intelligent prevention of double scans to ensure data integrity.
*   **Visual & Audio Feedback**: Instant success/error feedback with customizable audio cues.

### ⚡ Offline-First Architecture
*   **Resilient Operation**: Fully functional ticket validation without an active internet connection.
*   **Local Caching**: Encrypted local storage ensures the entire attendee database is available on-device.
*   **Smart Synchronization**: Background synchronization engine automatically pushes offline scans to the server once connectivity is restored.
*   **Retry Queue**: Robust queuing system guarantees no scan data is lost, even in unstable network conditions.

### 📊 Real-Time Event Management
*   **Live Data Sync**: Real-time integration with **Google Cloud Firestore** for up-to-the-second attendance stats.
*   **Dashboard Overview**: Instant visibility into scan counts, remaining tickets, and venue capacity.
*   **Scan Logs**: Comprehensive audit trails of all scan activities, including sync status and timestamps.
*   **Attendee Lists**: Searchable and filterable views of all registered attendees and their check-in status.

### 🔒 Enterprise Security
*   **Secure Authentication**: Role-based access control for scanners and event staff.
*   **Data Encryption**: Secure storage of sensitive attendee data on the device.
*   **Validated Access**: Server-side verification logic to prevent check-in fraud.

## 📱 Technology Stack

This application utilizes a powerful stack of modern technologies to ensure performance, scalability, and reliability:

*   **Framework**: [Ionic](https://ionicframework.com/) & [Angular](https://angular.io/)
*   **Native Runtime**: [Capacitor](https://capacitorjs.com/) (targeting Android)
*   **Database**: [Firebase Firestore](https://firebase.google.com/products/firestore) (Real-time NoSQL)
*   **Scanning Engine**: [Google ML Kit](https://developers.google.com/ml-kit)
*   **State Management**: RxJS & NgRx
*   **Offline Storage**: Ionic Storage & SQLite

## 📦 Release Information

This repository contains the source code for the Android native application.
*   **Platform**: Android
*   **Distribution**: APK / App Bundle

---

# 🇮🇩 Donetix Scan (Bahasa Indonesia)

**Pengembang**: Rizky Alfi Syahrin

**Donetix Scan** adalah aplikasi mobile kelas enterprise berkinerja tinggi yang dirancang untuk validasi tiket acara dan manajemen kehadiran yang mulus. Dibangun dengan teknologi mobile hybrid modern, aplikasi ini memberikan pengalaman pemindaian offline-first yang tangguh untuk perangkat Android.

## 🚀 Fitur Utama

### 🎫 Pemindaian Tiket Canggih
*   **Pemindaian Berkecepatan Tinggi**: Menggunakan **Google ML Kit** untuk deteksi barcode dan kode QR dengan latensi milidetik.
*   **Dukungan Multi-Zona**: Pemindaian yang dapat dikonfigurasi untuk ring/zona akses tertentu (misal: Gerbang A, Area VIP).
*   **Deteksi Duplikat**: Pencegahan cerdas terhadap pemindaian ganda untuk memastikan integritas data.
*   **Umpan Balik Visual & Audio**: Umpan balik instan sukses/gagal dengan isyarat audio yang dapat disesuaikan.

### ⚡ Arsitektur Offline-First
*   **Operasi Tangguh**: Validasi tiket berfungsi penuh tanpa koneksi internet aktif.
*   **Penyimpanan Lokal**: Penyimpanan lokal terenkripsi memastikan seluruh database peserta tersedia di perangkat.
*   **Sinkronisasi Cerdas**: Mesin sinkronisasi latar belakang secara otomatis mengirimkan hasil pemindaian offline ke server setelah konektivitas pulih.
*   **Antrean Percobaan Ulang (Retry Queue)**: Sistem antrean yang kuat menjamin tidak ada data pemindaian yang hilang, bahkan dalam kondisi jaringan yang tidak stabil.

### 📊 Manajemen Acara Real-Time
*   **Sinkronisasi Data Langsung**: Integrasi real-time dengan **Google Cloud Firestore** untuk statistik kehadiran terkini hingga detik terakhir.
*   **Tinjauan Dashboard**: Visibilitas instan ke jumlah pemindaian, sisa tiket, dan kapasitas lokasi.
*   **Log Pemindaian**: Jejak audit komprehensif dari semua aktivitas pemindaian, termasuk status sinkronisasi dan stempel waktu.
*   **Daftar Peserta**: Tampilan yang dapat dicari dan difilter dari semua peserta terdaftar dan status check-in mereka.

### 🔒 Keamanan Enterprise
*   **Autentikasi Aman**: Kontrol akses berbasis peran untuk pemindai dan staf acara.
*   **Enkripsi Data**: Penyimpanan aman data sensitif peserta di perangkat.
*   **Akses Tervalidasi**: Logika verifikasi sisi server untuk mencegah penipuan check-in.

## 📱 Stack Teknologi

Aplikasi ini menggunakan rangkaian teknologi modern yang kuat untuk memastikan kinerja, skalabilitas, dan keandalan:

*   **Framework**: [Ionic](https://ionicframework.com/) & [Angular](https://angular.io/)
*   **Runtime Native**: [Capacitor](https://capacitorjs.com/) (menargetkan Android)
*   **Database**: [Firebase Firestore](https://firebase.google.com/products/firestore) (Real-time NoSQL)
*   **Mesin Pemindaian**: [Google ML Kit](https://developers.google.com/ml-kit)
*   **Manajemen State**: RxJS & NgRx
*   **Penyimpanan Offline**: Ionic Storage & SQLite

## 📦 Informasi Rilis

Repositori ini berisi kode sumber untuk aplikasi native Android.
*   **Platform**: Android
*   **Distribusi**: APK / App Bundle

---
*© Donetix. Hak cipta dilindungi undang-undang.*
