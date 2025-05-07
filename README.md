# 🗺️ Sicopy – Peta Lokasi Fotokopi Lengkap

**Sicopy** adalah aplikasi peta interaktif berbasis Leaflet.js untuk menampilkan lokasi tempat fotokopi di sekitar Sukapura dan sekitarnya. Sistem ini memungkinkan pengguna untuk:
- Menemukan lokasi fotokopi terdekat.
- Melihat rute dari posisi pengguna ke lokasi fotokopi manapun.
- Menyaring berdasarkan fasilitas (print, ATK, jilid, dll), jam buka, order online, dan rating.
- Menemukan fotokopi termurah berdasarkan harga.

---

## 🚀 Fitur Unggulan

- 📍 Deteksi lokasi pengguna (via Leaflet LocateControl)
- 🧭 Rute otomatis ke fotokopi (Leaflet Routing Machine)
- 🔎 Pencarian nama fotokopi
- 🎯 Filter berdasarkan:
  - Fasilitas (print, ATK, jilid, dll)
  - Jam buka
  - Ketersediaan order online
  - Rating minimal
- 🧾 Tabel hasil yang interaktif
- 🔄 Reset filter & reload peta ke awal

---

## 🧰 Teknologi yang Digunakan

- HTML, CSS, JavaScript
- [Leaflet.js](https://leafletjs.com/)
- [Leaflet Routing Machine](https://www.liedman.net/leaflet-routing-machine/)
- [Leaflet LocateControl](https://github.com/domoritz/leaflet-locatecontrol)
- JSON dataset lokasi fotokopi

---

## 📂 Struktur Folder

```bash
/
├── application/
│   └── views/
│       └── Maps/
│           └── index.php
├── assets/
│   └── leaflet/ (jika pakai lokal)
├── js/
│   └── photocopyLocations.js
├── data_fotokopi.json
└── README.md
```

---

## ⚙️ Cara Menjalankan

1. Clone repository:
   ```bash
   git clone https://github.com/NAMA_KAMU/sicopy-gis.git
   ```

2. Jalankan via browser lokal (XAMPP atau live-server)

---

## 📌 Catatan

- Aplikasi ini berjalan sepenuhnya di sisi klien (tidak butuh backend)
- Data lokasi bersifat statis, bisa diupdate di file `photocopyLocations.js`

---

## 📄 Lisensi

MIT License © 2025 – *Sicopy Team*
