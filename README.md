# PURWALAND 5.3 — Dashboard Informasi Lahan Kabupaten Purwakarta

## Fokus
Dashboard informasi, bukan aplikasi WebGIS operasional. SPL telah dihapus dari menu, galeri, dan ruang lingkup.

## Peta acuan dari dokumen pengguna
- `curah_hujan.jpg`: TUGAS MODUL 3-1.pdf halaman 2. Legenda 100–300 dan 300–500; satuan/periode belum jelas.
- `jenis_tanah.jpg`: halaman 3. Kode Ao, Je, Nd, Th, To, Vc dipertahankan persis; kepanjangan kode belum diverifikasi.
- `kemiringan_lereng.jpg`: halaman 6. Kelas 1–5; batas interval tidak terbaca jelas.
- `penggunaan_lahan.jpg`: halaman 4, tetap dipertahankan sebagai peta pendukung.

Peta-peta tersebut adalah gambar layout yang diekstrak dari PDF, bukan data vektor/raster mentah. Dashboard menampilkannya sebagai peta acuan dan tidak mengklaim hasil analisis spasial baru.

## Statistik dan batasan
- Jenis tanah: tabel luas dari artikel Nurlukman dkk., Paspalum 13(1), 2025 (basis analisis 2020).
- Kemiringan lereng: KLHS RPJMD Purwakarta 2025–2029, Tabel 2.3; kelas dan luas sesuai dokumen.
- Curah hujan: KLHS RPJMD Purwakarta 2025–2029, Tabel 2.4 (tahun 2021). Luas area per rentang hujan bukan curah hujan bulanan.
- Statistik tabel dan peta PDF tidak otomatis identik; terutama legenda peta curah hujan dan kode jenis tanah perlu verifikasi dari sumber metadata asli.
- Tidak ada SPL dalam versi ini.

## Menjalankan
Buka `web/index.html`. Jika browser membatasi pemuatan data lokal, jalankan `python -m http.server 8000` dari folder utama, lalu buka `http://localhost:8000/web/`.
