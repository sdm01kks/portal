# Changelog — Portal Program Pemerintah
# SD Muhammadiyah 01 Kukusan

Semua perubahan signifikan pada portal ini dicatat di sini.
Format: `[Versi] - YYYY-MM-DD`

---

## [Unreleased]

### Menunggu File Referensi dari Admin:
- **Pendidikan Anti Narkoba** — halaman konten (`integrasi-kurikulum-antinarkoba.html`) belum dibuat; menunggu dokumen acuan dari BNN/Kemendikdasmen
- **Sekolah Model: Pembelajaran Mendalam & Koding-KA** — halaman konten belum dibuat; menunggu dokumen referensi dari Kemendikdasmen

### Direncanakan:
- Restrukturisasi format 5W+1H pada halaman program menjadi format naratif yang lebih kontekstual (What → Mengapa → Strategi → Siapa → Penerapan di Sekolah)
- Update header/nav individual program pages agar selaras desain baru
- Penambahan halaman "Tentang Portal"

---

## [0.2.0] - 2026-04-30

### 🔴 Kritis — Diperbaiki
- **LINK PUTUS**: Kartu program Juknis Keterampilan Menulis, Pendidikan Kebencanaan, dan Pendidikan Antikorupsi di halaman utama dan hub program menampilkan "Segera Hadir" padahal halaman sudah ada dan berisi konten lengkap. Tautan kini diperbaiki dan dapat diakses.

### ✅ Ditambahkan
- `CHANGELOG.md` — file log ini untuk mencatat seluruh perbaikan dan peningkatan portal
- Kartu program baru: **Penyelenggaraan Sekolah Model Implementasi Pembelajaran Mendalam dan Koding dan Kecerdasan Artifisial** (Program 07, status: Segera Hadir)
- Kartu program Anti Narkoba dipisah menjadi: **Integrasi Kurikulum Anti Narkoba** (Program 06, status: Segera Hadir — menunggu file referensi)

### 🔄 Diubah
- **Redesain layout** — selaraskan tampilan dengan Portal Administrasi Guru (referensi): font Lora + Outfit, palet warna forest green, topbar, sticky navigation putih, background sand/krem
- **Statistik diperbarui**: 5 dokumen tersedia (dari 2), 7 program terdaftar (dari 6)
- **Progress bar** di halaman hub program diperbarui: 5/7 program selesai (71%)
- Deskripsi kartu program diperbarui agar lebih informatif dan kontekstual

---

## [0.1.0] - 2026-01-xx

### ✅ Dirilis Pertama Kali
- Halaman utama portal (`index.html`) dengan grid kartu program
- Halaman hub program pemerintah (`program-pemerintah/index.html`)
- Program tersedia (dengan konten lengkap):
  - Gerakan Numerasi Nasional (GNN) — 118 hal., BSKAP Jan 2026
  - Standar Proses Pendidikan 2026 — Permendikdasmen No.1/2026
- Program sudah ada konten tapi belum ditautkan:
  - Juknis Keterampilan Menulis
  - Pendidikan Kebencanaan
  - Pendidikan Antikorupsi
- Program placeholder (Segera Hadir):
  - Integrasi Kurikulum Anti Narkoba
