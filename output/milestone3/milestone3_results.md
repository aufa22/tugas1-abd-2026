# Milestone 3 — EDA & Insight

1. Rating rata-rata 3.777/5 pada 10,448,835 ulasan valid unik, periode 2016-09-24 10:10:08 sampai 2026-09-27 07:20:57. Ini menggambarkan review teramati, bukan seluruh pemain.

2. Rating paling sering adalah 5 bintang: 6,309,889 ulasan (60.39% dari 10,448,835). Jika seri, rating lebih kecil dipilih sebagai laporan tunggal; distribusi lengkap ada pada tabel ratings.

3. Rating rendah (1–2) mencapai 2,833,547/10,448,835 (27.12%). Kategori ini adalah definisi rating rendah, bukan label sentimen NLP.

4. Bulan dengan ulasan terbanyak adalah 2020-07-01: 282,931 (2.71% dari semua review). Volume ini tidak sama dengan jumlah pemain aktif; bulan batas dapat parsial.

5. Balasan pengembang tersedia pada 138,739/10,448,835 ulasan (1.33%). Review tanpa balasan pada snapshot tidak membuktikan tidak pernah dibalas.

6. Median panjang review adalah 23.0 karakter Unicode. Nilai ini termasuk emoji dan spasi internal, serta tidak mengukur kualitas argumen pengguna.

7. Median durasi balasan 6.86 jam, berdasarkan 116,709 review dengan balasan dan tanggal valid (bukan semua 138,739 review yang memiliki balasan). Seleksi ini dapat bias dan zona waktu perlu diverifikasi.

8. Pada bulan tengah dengan n≥30, rating rata-rata berubah dari 4.294 (2016-10-01, n=1,963) ke 3.967 (2026-08-01, n=54,728), selisih -0.327 poin. Perbandingan dua titik bukan uji signifikansi atau bukti tren monoton.

## Validasi dan keterbatasan

Input memiliki ID unik, rating 1–5, content dan tanggal valid; jumlah agregat cocok dengan jumlah ulasan. Tidak ada uji kausal, filter negara, atau verifikasi zona waktu otomatis. Periksa pengaruh karantina dan duplikasi Milestone 2 sebelum menarik kesimpulan. Grafik versi membutuhkan dukungan sampel minimum.

## AI Disclosure Statement

Alat: ChatGPT/Codex. Bantuan: penyusunan SQL agregasi, visualisasi Plotly, dan template insight. Eksekusi teknis ini selesai dengan assertions lulus. Mahasiswa perlu menuliskan verifikasi dan pemahaman yang benar-benar dilakukan; jangan mengklaim telah memahami tanpa meninjau kode/output.
