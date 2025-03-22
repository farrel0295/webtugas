# Laporan Tugas #1: Membangun Website Personal dengan HTML & CSS

## Deskripsi Proyek

Proyek ini merupakan pengembangan website personal portofolio Farrel Najdin Alfadillah dari Semarang Jateng. Website ini dirancang untuk menampilkan informasi pribadi, keterampilan, dan karya-karya yang telah dibuat.

### Tujuan
- Membuat website personal yang menarik dan profesional
- Menampilkan informasi diri dan portofolio secara terstruktur
- Menerapkan desain responsif untuk berbagai ukuran perangkat

### Fitur Utama
- Halaman About Me yang menampilkan informasi personal
- Halaman Portfolio yang menampilkan proyek-proyek yang pernah dikerjakan
- Halaman Contact dengan formulir kontak (non-fungsional, hanya desain)
- Mode gelap (dark mode) yang dapat diaktifkan pengguna
- Desain responsif untuk mobile dan desktop
- Animasi dan efek hover untuk meningkatkan interaktivitas

### Teknologi yang Digunakan
- HTML5 untuk struktur halaman
- CSS3 untuk styling dan layout
- JavaScript untuk interaktivitas (dark mode dan animasi)
- FontAwesome untuk ikon
- Google Fonts (Poppins) untuk tipografi

## Struktur Folder dan File

```
/
├── index.html                # Halaman utama (About Me)
├── portfolio.html            # Halaman portfolio
├── contact.html              # Halaman kontak
├── css/
│   └── style.css             # File CSS eksternal
├── js/
│   └── script.js             # File JavaScript
└── LAPORAN.md                # File laporan ini
```

## Implementasi

### HTML
- Menggunakan tag HTML5 semantik (`header`, `nav`, `main`, `footer`, `section`)
- Struktur yang bersih dan terorganisir
- Navigasi yang berfungsi antar halaman
- Formulir kontak (hanya desain)

### CSS
- Menggunakan CSS eksternal
- Implementasi layout dengan flexbox dan grid
- Desain responsif dengan media queries untuk mobile dan desktop
- Warna dan tipografi yang konsisten
- Efek hover dan animasi sederhana
- Implementasi dark mode dengan CSS variables

### JavaScript
- Fungsi toggle untuk dark mode
- Penyimpanan preferensi tema di localStorage
- Animasi scroll untuk meningkatkan user experience
- Handler form submission (hanya untuk tampilan)

## Fitur Responsive

Website ini responsif dan dapat diakses dengan baik pada berbagai ukuran layar:

### Desktop
- Layout penuh dengan semua elemen ditampilkan secara optimal
- Grid proyek dengan 2-3 kolom
- Navigasi horizontal di header

### Mobile
- Layout yang menyesuaikan untuk layar kecil
- Proyek ditampilkan dalam satu kolom
- Menu navigasi yang tetap mudah diakses
- Font size dan spacing yang disesuaikan

## Tantangan dan Solusi

### Tantangan
- Membuat desain yang konsisten di semua halaman
- Implementasi dark mode yang mulus
- Membuat layout yang responsif untuk semua ukuran layar

### Solusi
- Menggunakan CSS variables untuk konsistensi warna dan tema
- Implementasi localStorage untuk menyimpan preferensi tema
- Menggunakan media queries dan flexbox/grid untuk responsivitas

## Kesimpulan

Proyek website personal ini berhasil mengimplementasikan semua persyaratan yang diminta dalam tugas, termasuk:
- Struktur tiga halaman (index, portfolio, contact)
- Elemen HTML semantik
- Styling CSS eksternal dengan flexbox/grid
- Responsivitas untuk berbagai ukuran perangkat
- Fitur dark mode

Proyek ini juga memberikan pengalaman praktis dalam pengembangan website front-end dengan fokus pada desain yang bersih dan pengalaman pengguna yang baik.

---

*Website ini dikembangkan sebagai bagian dari Tugas #1: Membangun Website Personal dengan HTML & CSS.*
