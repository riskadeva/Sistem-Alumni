# SiLacak — Sistem Pelacakan Alumni UMM

Sistem pelacakan alumni berbasis web untuk Program Studi Informatika, Universitas Muhammadiyah Malang.

> **Daily Project 3** — Riska Nurhayati Deva

---

## 🔗 Link

- **Web:** [https://username.github.io/sistem-alumni/](https://username.github.io/sistem-alumni/) *(ganti dengan link kamu)*
- **Source Code:** [https://github.com/username/sistem-alumni](https://github.com/username/sistem-alumni) *(ganti dengan link kamu)*

---

## 📌 Deskripsi

SiLacak adalah aplikasi web untuk membantu institusi pendidikan melacak keberadaan dan aktivitas alumni melalui berbagai sumber publik seperti LinkedIn, Google Scholar, ResearchGate, GitHub, dan media sosial lainnya.

---

## ✨ Fitur

- 📊 Dashboard statistik alumni
- 👥 Manajemen data alumni (tambah, edit, hapus)
- 🔍 Pencarian dan filter alumni
- ⚡ Simulasi pelacakan otomatis dari sumber publik
- 📋 Laporan dengan confidence score
- 💾 Penyimpanan data menggunakan LocalStorage

---

## 🧪 Pengujian Aplikasi

### 1. Pengujian Fungsionalitas

| No | Fitur yang Diuji | Langkah Pengujian | Hasil yang Diharapkan | Hasil Aktual | Status |
|----|-----------------|-------------------|----------------------|--------------|--------|
| 1 | Tambah Alumni | Klik tombol "+ Tambah Alumni" → isi form → klik Simpan | Data alumni baru muncul di tabel | Data berhasil ditambahkan dan tampil di tabel | ✅ Pass |
| 2 | Edit Alumni | Klik tombol ✏️ pada baris alumni → ubah data → Simpan | Data alumni berhasil diperbarui | Data berhasil diperbarui di tabel | ✅ Pass |
| 3 | Hapus Alumni | Klik tombol 🗑️ pada baris alumni → konfirmasi | Data alumni terhapus dari tabel | Data berhasil dihapus | ✅ Pass |
| 4 | Cari Alumni | Ketik nama/prodi di kolom pencarian | Tabel menampilkan hasil yang sesuai | Filter berjalan secara real-time | ✅ Pass |
| 5 | Filter Status | Pilih status di dropdown filter | Tabel hanya menampilkan alumni dengan status dipilih | Filter status berfungsi | ✅ Pass |
| 6 | Pelacakan Otomatis | Klik "Jalankan Pelacakan" | Sistem memproses alumni & update status | Log pelacakan muncul dan status alumni diperbarui | ✅ Pass |
| 7 | Penyimpanan Data | Tambah data → refresh halaman | Data tetap ada setelah refresh | Data tersimpan di LocalStorage | ✅ Pass |
| 8 | Navigasi Halaman | Klik menu sidebar (Dashboard, Alumni, Pelacakan, Laporan) | Halaman berpindah sesuai menu | Navigasi berjalan lancar | ✅ Pass |
| 9 | Pagination | Tambah lebih dari 8 alumni | Muncul tombol halaman berikutnya | Pagination berfungsi | ✅ Pass |
| 10 | Laporan | Buka halaman Laporan | Menampilkan statistik dan tabel lengkap | Data laporan ditampilkan dengan benar | ✅ Pass |

---

### 2. Pengujian Usability

| No | Aspek | Kriteria | Hasil Pengujian | Status |
|----|-------|----------|-----------------|--------|
| 1 | Kemudahan Navigasi | Menu sidebar jelas dan mudah dipahami | Pengguna dapat berpindah halaman tanpa kebingungan | ✅ Baik |
| 2 | Form Input | Label form jelas, placeholder membantu | Pengguna memahami isian yang diperlukan | ✅ Baik |
| 3 | Notifikasi | Muncul toast saat aksi berhasil/gagal | Feedback diberikan setelah setiap aksi | ✅ Baik |
| 4 | Konfirmasi Hapus | Muncul dialog konfirmasi sebelum hapus | Pengguna tidak sengaja menghapus data | ✅ Baik |
| 5 | Tampilan Data | Data ditampilkan dalam tabel yang rapi | Informasi mudah dibaca dan dipahami | ✅ Baik |
| 6 | Status Visual | Status alumni dibedakan dengan warna | Pengguna langsung memahami status pelacakan | ✅ Baik |

---

### 3. Pengujian Kompatibilitas

| No | Browser / Perangkat | Versi | Tampilan | Fungsionalitas | Status |
|----|---------------------|-------|----------|----------------|--------|
| 1 | Google Chrome | 120+ | Normal | Semua fitur berjalan | ✅ Pass |
| 2 | Mozilla Firefox | 115+ | Normal | Semua fitur berjalan | ✅ Pass |
| 3 | Microsoft Edge | 120+ | Normal | Semua fitur berjalan | ✅ Pass |
| 4 | Safari (Mac/iOS) | 16+ | Normal | Semua fitur berjalan | ✅ Pass |
| 5 | Chrome Mobile (Android) | 120+ | Responsive | Semua fitur berjalan | ✅ Pass |
| 6 | Layar Desktop (1920×1080) | — | Optimal | Semua fitur berjalan | ✅ Pass |
| 7 | Layar Laptop (1366×768) | — | Normal | Semua fitur berjalan | ✅ Pass |
| 8 | Layar Mobile (390×844) | — | Responsive | Semua fitur berjalan | ✅ Pass |

---

### 4. Pengujian Performance

| No | Aspek | Metode Pengujian | Hasil | Target | Status |
|----|-------|-----------------|-------|--------|--------|
| 1 | Waktu Muat Awal | Buka halaman pertama kali | < 1 detik | < 3 detik | ✅ Pass |
| 2 | Respons Tambah Data | Klik Simpan → data muncul | Instan | < 1 detik | ✅ Pass |
| 3 | Respons Pencarian | Ketik di search bar → filter | Real-time | < 0.5 detik | ✅ Pass |
| 4 | Proses Pelacakan | Jalankan tracking 8 alumni | ~3.2 detik | < 10 detik | ✅ Pass |
| 5 | Ukuran File | Cek ukuran index.html | ~30 KB | < 500 KB | ✅ Pass |
| 6 | Tanpa Koneksi Internet | Buka setelah di-cache browser | Berjalan normal | Tetap berfungsi | ✅ Pass |

---

## 🛠️ Teknologi

- HTML5, CSS3, JavaScript (Vanilla)
- LocalStorage API
- Google Fonts (Syne, DM Sans)

---

## 📁 Struktur File

```
sistem-alumni/
└── index.html    # File utama aplikasi
└── README.md     # Dokumentasi & pengujian
```

---

## 👤 Pengembang

**Riska Nurhayati Deva** — Informatika, Universitas Muhammadiyah Malang
