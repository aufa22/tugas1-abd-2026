# Data Tugas 1

## Dataset yang Dipilih

Dataset yang digunakan adalah **Mobile Legend Playstore Dataset** dari Kaggle. Dataset ini berisi data ulasan pengguna game **Mobile Legends: Bang Bang** yang berasal dari Google Play Store. Berdasarkan sumber yang dapat diverifikasi, dataset ini memiliki sekitar **548.250–548.260 ulasan** pengguna dan memiliki informasi rating dengan rentang 1–5 bintang.

### Informasi Dataset

| Item                    | Isi                                                                                                                                                                               |
| ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Nama dataset            | Mobile Legend Playstore Dataset                                                                                                                                                   |
| Sumber                  | Kaggle — https://www.kaggle.com/datasets/dewanakretarta/mobile-legend-playstore-dataset                                                                                           |
| Lisensi/ketentuan pakai | Belum dapat diverifikasi dari metadata Kaggle yang tersedia secara publik; periksa kembali bagian License pada halaman Kaggle sebelum redistribusi atau penggunaan di luar tugas. |
| Ukuran                  | ±548.250–548.260 baris ulasan; belum memenuhi ketentuan >1.000.000 baris pada tugas. Ukuran file dalam MB belum dapat diverifikasi dari sumber yang tersedia.                     |
| Periode data            | Tidak disebutkan secara eksplisit pada sumber yang dapat diverifikasi. Dataset tercatat sebagai dataset Kaggle oleh Dewanakretarta pada 2023.                                     |
| Unit analisis           | Satu ulasan/review pengguna Mobile Legends: Bang Bang pada Google Play Store.                                                                                                     |

### Catatan Kesesuaian dengan Ketentuan Tugas

Template tugas mensyaratkan dataset dengan ukuran **≥500 MB atau >1.000.000 baris**. Dataset ini memiliki sekitar **548 ribu ulasan**, sehingga berdasarkan jumlah baris **belum memenuhi** batas >1.000.000 baris. Ukuran file dalam MB juga belum dapat diverifikasi dari sumber yang tersedia.

Karena itu, dataset perlu dikonfirmasi kepada dosen atau diganti dengan dataset yang memenuhi salah satu batas tersebut apabila ketentuan ukuran bersifat wajib.

## Tempat Mencari Dataset

Pilih dataset Indonesia yang legal digunakan, dapat didokumentasikan sumbernya, dan memenuhi batas ukuran tugas.

| Situs                                                               | Kegunaan                                                                 |
| ------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| [Satu Data Indonesia](https://data.go.id/)                          | Portal data terbuka lintas instansi pemerintah Indonesia.                |
| [Badan Pusat Statistik](https://www.bps.go.id/)                     | Statistik sosial, ekonomi, kependudukan, dan data wilayah.               |
| [BMKG Data Online](https://dataonline.bmkg.go.id/)                  | Data cuaca, iklim, gempa bumi, dan observasi meteorologi.                |
| [Hugging Face Datasets](https://huggingface.co/datasets)            | Dataset publik yang dapat dicari berdasarkan topik, bahasa, atau ukuran. |
| [Kaggle Datasets](https://www.kaggle.com/datasets)                  | Katalog dataset publik; periksa lisensi dan dokumentasi pembuatnya.      |
| [Google Dataset Search](https://datasetsearch.research.google.com/) | Mesin pencari untuk menemukan dataset dari berbagai portal.              |

## Cara Memperoleh Data

1. Buka URL sumber di atas.
2. Unduh file dataset **Mobile Legend Playstore Dataset** ke folder `data/raw/` tanpa mengubah data mentah.
3. Catat nama file dan checksum bila tersedia.
4. Ubah variabel `DATA_PATH` pada `notebooks/01_data_profiling.ipynb` agar menunjuk ke file tersebut.

## Aturan Penyimpanan

- Jangan commit dataset mentah atau hasil olahan berukuran besar ke Git.
- File pada `data/raw/` adalah data asli dan tidak boleh diubah.
- Simpan hasil transformasi yang dapat direproduksi pada `data/processed/`.
