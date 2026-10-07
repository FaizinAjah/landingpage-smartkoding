# 🌟 Smart Koding Academy — Landing Page & Platform Program Kelas

[![Website](https://img.shields.io/badge/Status-Live-success?style=for-the-badge&logo=google-chrome)](https://github.com/FaizinAjah/landingpage-smartkoding)
[![GitHub License](https://img.shields.io/badge/License-MIT-amber?style=for-the-badge)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-Semantik-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-Vanilla-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

Website landing page resmi dan portal informasi program kelas pemrograman untuk **Smart Koding Academy**, sebuah akademi koding dan laboratorium praktikum web development di **Kota Pasuruan, Jawa Timur**. Dibimbing langsung oleh Senior Software Engineer praktisi industri perbankan nasional (eks Bank BNI & SPE Solution).

---

## 🚀 Fitur & Halaman Proyek

Proyek ini dibangun secara modular, semantik, dan responsif dari layar smartphone (mobile-first) hingga desktop monitor besar:

| Halaman | File | Deskripsi |
| :--- | :--- | :--- |
| **Beranda Utama** | [`index.html`](index.html) | Landing page utama lengkap dengan kalkulator biaya dinamis, showcase kurikulum 12 minggu, terminal editor kode interaktif, profil mentor, dan ulasan siswa. |
| **Katalog Kelas** | [`kelas.html`](kelas.html) | Katalog lengkap seluruh program kelas dengan filter kategori (*Web, Lab Offline, Bootcamp Online, Event*). |
| **Web Tingkat Lanjut** | [`program-web-lanjut.html`](program-web-lanjut.html) | Landing page khusus kelas intensif PHP 8.3 & Laravel 11, REST API, arsitektur MVC, database MySQL, dan deployment cloud VPS. |
| **Kelas Offline Lab** | [`program-offline-lab.html`](program-offline-lab.html) | Landing page praktikum tatap muka di laboratorium komputer Pasuruan dengan PC spek tinggi (Core i7, RAM 16GB, Dual Monitor) dan batas 10 siswa/sesi. |
| **Online Live Bootcamp** | [`program-online-bootcamp.html`](program-online-bootcamp.html) | Landing page belajar fleksibel dari mana saja dengan 100+ video kurikulum, sesi review mingguan Google Meet, dan Discord VIP 24/7. |
| **Event & Workshop Gratis** | [`program-workshop-event.html`](program-workshop-event.html) | Landing page webinar & workshop gratis developer, tiket digital RSVP pass, dan bedah arsitektur backend perbankan. |

---

## 🎨 Desain & Teknologi (Tech Stack)

- **Semantic HTML5 & Accessibility (a11y)**: Menggunakan landmark semantik (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<time>`, `<details>`, `<summary>`, `<footer>`) serta atribut ARIA untuk pembaca layar.
- **Vanilla CSS3 Design System**:
  - Palet warna cerah bertema *Sun-Yellow & Amber Gold* (`#FFC400`, `#FFD600`, `#F59E0B`, `#D97706`).
  - *Fluid Typography* menggunakan fungsi `clamp()` agar judul dan teks proporsional di seluruh resolusi layar (320px s/d 4K).
  - Efek modern: Glassmorphism header, radial mesh gradient background, bento grid layout, dan micro-interaction animations.
  - Tipografi: *Plus Jakarta Sans* & *JetBrains Mono* via Google Fonts.
- **Vanilla JavaScript**:
  - Navigasi dropdown & drawer mobile menu interaktif.
  - Kalkulator investasi biaya SPP interaktif.
  - Filter kategori program instan.
  - Sticky floating quick-action bar untuk perangkat seluler.

---

## 📁 Struktur Direktori

```text
landingpage-smartkoding/
│
├── index.html                   # Beranda utama Smart Koding Academy
├── kelas.html                   # Katalog semua program kelas
├── program-web-lanjut.html      # Landing page kelas Web Lanjut (Laravel 11)
├── program-offline-lab.html     # Landing page kelas Offline Lab Pasuruan
├── program-online-bootcamp.html # Landing page kelas Online Live Bootcamp
├── program-workshop-event.html  # Landing page Event & Workshop Gratis
├── rahmat-ramadhan-putra.png    # Aset foto profil instruktur utama
└── README.md                    # Dokumentasi repositori
```

---

## 💻 Cara Menjalankan Proyek Secara Lokal

Tidak memerlukan instalasi runtime atau package manager (*zero build steps*):

1. **Clone repository ini:**
   ```bash
   git clone https://github.com/FaizinAjah/landingpage-smartkoding.git
   ```
2. **Masuk ke direktori:**
   ```bash
   cd landingpage-smartkoding
   ```
3. **Buka di browser:**
   - Cukup klik dua kali pada file `index.html`, atau
   - Buka menggunakan ekstensi **Live Server** di VS Code.

---

## 🌐 Publikasi Online (GitHub Pages)

Anda dapat mengaktifkan **GitHub Pages** gratis agar landing page ini dapat diakses publik:
1. Buka repository di GitHub &rarr; **Settings** &rarr; **Pages**.
2. Di bagian **Build and deployment**, pilih branch `master` (atau `main`) dengan folder `/ (root)`.
3. Klik **Save**. Dalam 1-2 menit website akan live di:
   ```text
   https://faizinajah.github.io/landingpage-smartkoding/
   ```

---

## 👨‍💻 Kontributor & Lisensi

- **Author / Developer**: [FaizinAjah](https://github.com/FaizinAjah)
- **Akademi**: Smart Koding Academy — Pasuruan, Jawa Timur
- **Lisensi**: Proyek ini dirilis di bawah lisensi [MIT](LICENSE).
