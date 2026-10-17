Data Visualization: Dataset Lagu

Tugas Studi Kasus Mata Kuliah Data Mining (Data Visualization)

**Nama:** David Andrew Gregorius Tingang Liah

**NIM:** 2418058

**Kelas:** A

## Deskripsi

Project ini memvisualisasikan dataset lagu berisi 105 baris memakai Python (Pandas, Matplotlib, Seaborn) di Google Colab. Dataset ini lanjutan dari dataset tugas Data Cleansing (33 lagu), lalu saya tambah menjadi 105 lagu. Nilai jumlah putar, popularitas, dan durasi adalah data contoh untuk latihan, bukan angka resmi dari platform musik.

## Isi Repository

- 2418058DataVisualization.ipynb: notebook berisi kode, grafik, interpretasi, dan kesimpulan
- dataset_musik_visualisasi.csv: dataset (105 baris, 10 kolom)
- hasil_visualisasi/: 7 gambar hasil visualisasi
- README.md: dokumentasi project

## Kolom Dataset

| Kolom | Keterangan |
|---|---|
| id_lagu | nomor identitas lagu |
| judul | judul lagu |
| artis | nama artis atau band |
| genre | genre lagu |
| tahun_rilis | tahun rilis |
| durasi_detik | durasi lagu dalam detik |
| jumlah_putar | jumlah pemutaran (streaming) |
| popularitas | skor popularitas (0 sampai 100) |
| negara_artis | negara asal artis |
| benua | benua asal artis |

Di notebook ditambahkan kolom durasi_menit, jumlah_putar_miliar, dekade, usia_lagu, dan asal_lagu (lokal atau internasional).

## Teknik Visualisasi

| No | Visualisasi | Tujuan |
|---|---|---|
| 1 | Line chart | tren total jumlah putar per dekade |
| 2 | Bar chart | jumlah lagu per genre |
| 3 | Histogram | sebaran skor popularitas |
| 4 | Boxplot | durasi lagu per genre dan outlier |
| 5 | Scatter plot | hubungan jumlah putar dan popularitas |
| 6 | Heatmap | korelasi antarvariabel numerik |
| 7 | Bar chart | rata-rata popularitas per genre |

Setiap grafik memiliki judul, label sumbu, legenda, keterangan, dan interpretasi di notebook.

## Insight Utama

- Dataset didominasi Pop (43 lagu) dan Rock (22 lagu), dan lagu dari 2010-an paling banyak (44 lagu).
- Popularitas rata-rata 80,2 dengan median 81.
- Jumlah putar dan popularitas berkorelasi kuat (0,88). Lagu internasional rata-rata lebih populer (82,0) dibanding lagu lokal (70,8).
- Lagu yang lebih baru cenderung lebih pendek (korelasi -0,58). Rock paling panjang, K-Pop paling pendek.
- Perbedaan rata-rata popularitas antargenre kecil (selisih 7,4 poin).

## Cara Menjalankan

Buka 2418058DataVisualization.ipynb di Google Colab, lalu klik Runtime, Run all. Data sudah ada di dalam notebook, jadi tidak perlu upload file. Gambar hasil akan tersimpan di folder hasil_visualisasi.
