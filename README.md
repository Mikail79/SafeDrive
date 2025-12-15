# SafeDrive – AI Co-Driver untuk Deteksi Kelelahan Pengemudi

## 1. Judul Proyek

**SafeDrive: Sistem Deteksi Keselamatan Pengemudi Mobil Berbasis Android**

## 2. Anggota Tim DegorPrimo

- Arya Bima Setyono (Ketua)
- Muhammad Hilman Ansory
- Muhammad Mikail Alfasya
- Mikhail Trupathy Setiawan

## 3. Deskripsi Singkat Proyek

SafeDrive adalah aplikasi mobile berbasis **Android** yang berfungsi sebagai untuk membantu meningkatkan keselamatan berkendara. Aplikasi ini memanfaatkan kamera depan perangkat dan teknologi **computer vision** untuk memantau kondisi wajah pengemudi secara real-time, khususnya tingkat kewaspadaan melalui analisis mata dan keberadaan wajah.

Dengan pendekatan _real-time face landmark detection_, SafeDrive mampu memberikan peringatan dini ketika terdeteksi tanda-tanda kelelahan atau kantuk pada pengemudi. Sistem ini dirancang sebagai solusi preventif untuk mengurangi risiko kecelakaan lalu lintas yang disebabkan oleh faktor kelelahan.

## 4. Penjelasan Masalah yang Diangkat

Kelelahan dan kantuk pengemudi merupakan salah satu penyebab utama kecelakaan lalu lintas, terutama pada perjalanan jarak jauh atau berkendara di malam hari. Banyak pengemudi tidak menyadari bahwa tingkat kewaspadaan mereka telah menurun hingga kondisi menjadi berbahaya.

Permasalahan utama yang diangkat dalam proyek ini adalah **kurangnya sistem peringatan dini yang bersifat personal dan real-time** untuk mendeteksi kondisi kantuk pengemudi. SafeDrive hadir untuk menjawab masalah tersebut dengan menyediakan sistem monitoring otomatis yang mampu memberikan notifikasi dan peringatan suara ketika kondisi berbahaya terdeteksi.

## 5. Teknologi yang Digunakan

- **React Native (CLI)** – pengembangan aplikasi mobile
- **TypeScript** – bahasa pemrograman utama
- **react-native-vision-camera** – akses kamera real-time
- **ML Kit / MediaPipe Face Landmarker** – deteksi wajah dan landmark
- **Android SDK & Gradle** – build dan deployment Android
- **Node.js & npm** – manajemen dependensi

## 6. Panduan Instalasi

### Prasyarat

- Node.js (disarankan versi LTS)
- npm atau yarn
- Android Studio (termasuk Android SDK dan Emulator)
- JDK 17 atau versi yang direkomendasikan React Native
- Perangkat Android fisik (disarankan untuk pengujian kamera)

### Langkah Instalasi

1. Clone repository ini:

   ```bash
   git clone https://github.com/username/safedrive.git
   cd safedrive
   ```

2. Install dependensi:

   ```bash
   npm install
   ```

3. Masuk ke direktori Android dan pastikan dependensi native terpasang:

   ```bash
   cd android
   ./gradlew clean
   cd ..
   ```

4. Pastikan permission kamera telah dikonfigurasi pada `AndroidManifest.xml`.

## 7. Cara Menjalankan Aplikasi

1. Hubungkan perangkat Android atau jalankan Android Emulator.

2. Jalankan Metro bundler:

   ```bash
   npx react-native start
   ```

3. Jalankan aplikasi pada Android:

   ```bash
   npx react-native run-android
   ```

4. Setelah aplikasi terbuka, berikan izin kamera.

5. Arahkan kamera ke wajah pengemudi untuk mulai melakukan deteksi.

6. Aplikasi akan memberikan:

   - Peringatan teks dan suara jika mata tertutup dalam durasi tertentu.
   - Peringatan jika wajah tidak terdeteksi dalam waktu lama.

---

_Dokumen README ini dapat dikembangkan lebih lanjut sesuai kebutuhan proyek dan kompetisi/hackathon yang diikuti._
