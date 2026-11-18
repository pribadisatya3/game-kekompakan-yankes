# Game Kekompakan Tim — Yankes Badung

Aplikasi web interaktif untuk menguji kekompakan tim di lingkungan **Bidang Pelayanan Kesehatan, Dinas Kesehatan Kabupaten Badung**, dilengkapi dengan **Dashboard Admin** untuk memantau rekapitulasi hasil dan ekspor laporan ke Excel/CSV.

## Struktur File
- `index.html`: Aplikasi utama (siap deploy langsung ke Vercel / Netlify / GitHub Pages).
- `vercel.json`: Konfigurasi routing statis untuk Vercel.
- `README.md`: Panduan penggunaan dan deployment.

## Fitur Utama
1. **Mode 1 Tim Besar & Mode Kompetisi (2–4 Tim):** Mendukung kustomisasi nama tim dan daftar anggota.
2. **3 Ronde Interaktif:**
   - **Ronde 1 (Satu Frekuensi):** Menjawab pertanyaan keseharian kantor secara bergantian/rahasia lalu sistem menghitung persentase kesamaan jawaban.
   - **Ronde 2 (Estafet Kata Kunci):** Tebak cepat istilah kesehatan & pelayanan (Puskesmas, Akreditasi, SIPERKLIN, Mangusada, dll.) selama 60 detik dengan daftar kata tabu.
   - **Ronde 3 (Misi Darurat Pelayanan):** Simulasi keputusan cepat 15 detik untuk skenario pelayanan publik.
3. **Dashboard Admin (PIN Default: `1234`):**
   - Melihat statistik rata-rata tingkat kekompakan tim.
   - Tabel riwayat setiap sesi permainan beserta predikat kekompakan.
   - Fitur **Unduh Excel / CSV** untuk laporan kegiatan.

## Cara Deploy ke Vercel
1. Ekstrak file ZIP ini.
2. Buka [vercel.com](https://vercel.com), klik **Add New... > Project**.
3. Tarik (*drag & drop*) folder hasil ekstrak ke halaman Vercel, atau push ke repositori GitHub `Yankesbadung` lalu impor di Vercel.
