# UTS Machine Learning – Segmentasi Destinasi Wisata Bali (K-Means)

## Identitas
- **NIM:** 2301010424
- **Nama:** Nitchel Juliow Runesi
- **Kelas:** XX
- **Mata Kuliah:** Machine Learning – INSTIKI (Dosen: Dr. I Gede Totok Suryawan, S.Kom., M.T.)
- **Jalur:** C – Clustering (K-Means)

## Deskripsi Proyek
Proyek ini mengelompokkan destinasi wisata di Bali berdasarkan rating, jumlah ulasan, dan lokasi (latitude dan longitude) menggunakan algoritma K-Means. Hasil pengelompokan dapat dipakai oleh pengelola pariwisata atau dinas pariwisata untuk memahami tipe-tipe destinasi yang ada, misalnya destinasi yang sudah sangat populer dan destinasi yang belum banyak dikunjungi, sehingga strategi promosi dan pengembangan dapat disesuaikan untuk tiap kelompok. Proyek mengikuti alur CRISP-DM.

## Dataset
- **Judul:** Bali Tourist Destination
- **Sumber:** https://huggingface.co/datasets/mariouskono/Bali-Tourist-Destination
- **Tanggal akses:** 25 November 2026
- **Lisensi:** Apache-2.0 (menurut halaman dataset)
- **Catatan:** data dikumpulkan dari Google Maps oleh pembuat dataset. Tidak memuat identitas pribadi.
- **File:** `data/bali_tourist_destination.csv`

## Struktur Repository
- README.md
- notebook/UTS_ML_2301010424_Nitchel.ipynb
- data/bali_tourist_destination.csv
- reports/ (grafik utama dan slide presentasi)

## Cara Menjalankan
1. Buka notebook di Google Colab atau Jupyter.
2. Pastikan file CSV ada di folder `data/` atau sesuaikan path di sel pembacaan data.
3. Jalankan Runtime → Run all.

## Ringkasan Hasil
Hasil lengkap (jumlah cluster terpilih, nilai Silhouette, profil dan nama tiap kelompok) ada di notebook pada bagian Evaluasi dan Kesimpulan.

## Pernyataan Penggunaan AI
- Alat yang dipakai: Claude
- Untuk bagian apa: membantu mencari dataset dan menyusun kerangka kode notebook.
- Cara saya memeriksa hasilnya: saya menjalankan kodenya sendiri, memeriksa hasilnya, dan memahami setiap bagian kode.

