# 🚧 Cybernetic Under Construction Page

Halaman penampung status sistem (*maintenance / holding page*) futuristik bertema *cybernetic blueprint* dengan animasi interaktif, simulasi *live terminal deployment log*, dan *real-time elapsed build timer*.

---

## ✨ Fitur Utama

- 🌀 **Animasi Perakitan Core Cybernetic**: Dua cincin geometris SVG berputar (*dual-speed counter-rotating rings*) mengelilingi modul inti kode dengan efek denyut bercahaya (*pulsing glow*).
- 📐 **Latar Belakang Blueprint Dinamis**: Animasi grid pola blueprint tanpa batas (*infinite moving grid*) dilengkapi aksen pencahayaan *ambient radial glow* berwarna neon cyan.
- 💻 **Simulasi Terminal Build Log**: Menampilkan runtutan proses kompilasi, migrasi, dan deployment sistem secara bertahap (*staggered typing effect*) lengkap dengan kursor berkedip (*blinking cursor*).
- ⏱️ **Live Elapsed Build Timer**: Penghitung durasi waktu pengerjaan/aktif sistem (*real-time stopwatch*) yang diperbarui setiap detik.
- 📱 **Responsif & Mobile Friendly**: Tata letak grid fleksibel yang beradaptasi sempurna untuk layar desktop, tablet, maupun smartphone.
- ⚡ **Ultra Ringan & Zero Build Step**: Dijalankan secara instan menggunakan HTML5, Vanilla JavaScript, CSS Keyframes, dan Tailwind CSS (CDN) tanpa memerlukan proses *bundling* atau *compile*.

---

## 🧰 Tech Stack

| Teknologi | Peran |
| :--- | :--- |
| **HTML5** | Struktur semantik halaman |
| **Tailwind CSS (CDN)** | Styling utilitas responsif |
| **Vanilla CSS3** | Animasi kustom (Keyframes & Blueprint Grid) |
| **JavaScript (ES6+)** | Logika simulasi terminal log & build timer |

---

## 🚀 Cara Menjalankan

Karena proyek ini tidak memerlukan dependensi eksternal ataupun proses build, Anda dapat menjalankannya dengan beberapa metode:

### 1. Langsung Melalui Browser
Cukup buka file `index.html` langsung menggunakan peramban web pilihan Anda:
```bash
# Linux / WSL (Buka dengan browser default)
wslview index.html
# atau buka path file:// langsung di Google Chrome / Edge
```

### 2. Menggunakan Local HTTP Server (Opsional)
Untuk pengujian dengan server lokal:

```bash
# Menggunakan Python 3
python3 -m http.server 3000

# Menggunakan Node.js npx serve
npx serve .
```
Akses halaman pada `http://localhost:3000`.

---

## 📁 Struktur Direktori

```text
website-under-constructions/
├── index.html        # Struktur antarmuka, style Tailwind, CSS animasi, & logika script
└── README.md         # Dokumentasi lengkap proyek
```

---

## ⚙️ Kustomisasi

Anda dapat menyesuaikan isi halaman dengan mengedit file `index.html`:

1. **Pesan Log Terminal**: Ubah array `logMessages` pada tag `<script>` untuk menyesuaikan tahapan proses sistem Anda.
2. **Identitas Administrator / Footer**: Ubah teks pada elemen `<footer>` (`SYS.ADM: YORYZIAR`).
3. **Judul & Deskripsi**: Sesuaikan teks pada elemen `<h1>` dan `<p>` di dalam tag `<main>`.

---

## 👤 Author

- **GitHub**: [@YoryZiar](https://github.com/YoryZiar)
