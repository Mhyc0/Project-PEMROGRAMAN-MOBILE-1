# Jam App ⏱️

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

**Jam** adalah aplikasi manajemen waktu modern untuk Android yang dirancang dengan antarmuka **Dark Mode** yang elegan. Aplikasi ini menggabungkan fitur Timer, Stopwatch presisi tinggi, dan dukungan multi-bahasa dalam satu paket yang ringan.

## ✨ Fitur Unggulan

### 1. ⏳ Timer Cerdas
* **Input Roda Angka (Picker):** Memilih jam, menit, dan detik dengan antarmuka *scrolling* yang besar dan intuitif.
* **Quick Presets:** Tombol cepat untuk waktu umum (10, 15, 30 menit).
* **Visual Countdown:** Tampilan angka besar saat hitung mundur dimulai dengan UI yang bersih.

### 2. ⏱️ Stopwatch "Abadi" (Background Support)
* **Tetap Berjalan di Background:** Menggunakan logika `SharedPreferences` dan `SystemClock`, stopwatch tetap menghitung waktu dengan akurat **meskipun aplikasi ditutup atau HP di-restart**.
* **Presisi Milidetik:** Menampilkan waktu hingga satuan milidetik (Format `MM:SS:ms`).
* **Anti-Reset:** Tidak akan kembali ke 0 kecuali tombol Reset ditekan secara eksplisit.

### 3. 🌍 Auto Localization (Multi-bahasa)
* Aplikasi otomatis mendeteksi pengaturan bahasa di HP pengguna.
* **Indonesia:** Menampilkan sapaan "Selamat Datang".
* **Inggris/Global:** Menampilkan sapaan "Welcome".
* Tidak memerlukan izin lokasi (GPS), sehingga hemat baterai dan menjaga privasi.

### 4. 🎨 Desain Modern
* **Full Dark Mode:** Nyaman di mata dan hemat baterai untuk layar AMOLED.
* **Typography:** Menggunakan font **Poppins** untuk tampilan yang profesional dan mudah dibaca.
* **Adaptive Icon:** Ikon aplikasi yang responsif dan modern.

---

## 🛠️ Teknologi yang Digunakan

* **Bahasa:** Java
* **Layout:** XML (ConstraintLayout, LinearLayout)
* **Komponen UI:** NumberPicker, TextView, Button (Material Design)
* **Penyimpanan Lokal:** SharedPreferences (untuk menyimpan state Stopwatch)
* **Threading:** Handler & Runnable (untuk update UI realtime)

---


