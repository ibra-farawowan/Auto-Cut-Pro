# 🎬 Auto Cut Pro v1.1

**Auto Cut Pro** adalah aplikasi desktop berbasis C++ Native yang dirancang untuk mengotomatisasi proses *highlighting* video game. Aplikasi ini menggunakan kecerdasan buatan (OCR) untuk mendeteksi momen penting (seperti Kill Feed) dan memotong klip secara otomatis tanpa mengurangi kualitas video.

Dibuat untuk performa maksimal dengan penggunaan resource yang minim.

---

## 🌟 Fitur Utama

### 1. Deteksi Otomatis Berbasis AI
Menggunakan **PaddleOCR** untuk membaca teks dalam video secara akurat. Dilengkapi dengan algoritma pencocokan cerdas (*Fuzzy Matching*) sehingga nama player tetap terdeteksi meski hasil scan tidak 100% sempurna.

### 2. Editor "LossCut" yang Interaktif
Fitur player bawaan yang memungkinkan Anda meninjau hasil scan.
* **Timeline Interaktif:** Geser (scrub) timeline dengan mulus untuk melihat momen yang terdeteksi (ditandai dengan marker kuning).
* **Export Cepat:** Ekspor momen hanya dalam hitungan detik menggunakan teknik *Lossless Cut* (tanpa render ulang).

### 3. Performa Tinggi & Stabil
* **Native Win32 API:** Antarmuka (UI) dibangun dari nol tanpa framework berat, menghasilkan aplikasi yang sangat ringan.
* **Anti-Glitch:** Manajemen memori dan *rendering* grafis yang dioptimalkan untuk pengalaman pengguna yang mulus (bebas flickering/ghosting).

---

## 🔧 Teknologi yang Digunakan

* **Core:** C++ (Visual Studio)
* **UI:** Win32 API (Custom Dark Theme)
* **Vision:** OpenCV & OcrLite
* **Media:** libmpv & FFmpeg

---

## 💻 Cara Menggunakan

1.  Download file Installer dari menu **Releases**.
2.  Install aplikasi di PC Anda.
3.  Buka **Dashboard**, pilih video game Anda, dan atur area deteksi (ROI).
4.  Klik **Mulai Analisis**.
5.  Setelah selesai, buka tab **Hasil Scan** untuk meninjau dan menyimpan klip Anda.



---

**Dibuat oleh [Ibra Farawowan]**
