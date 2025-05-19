# Used Car Price Analysis

## Repository Outline
`Pada project ini mempunyai 5 file`

```
1. README.md - Penjelasan gambaran umum project
2. h8dsft_Milestone1_Reido_Vidaya.ipynb.ipynb - Notebook yang berisi pengolahan data dengan python
3. merc.csv - Dataset Raw
4. Usedcar.csv - Dataset Clean
5. Usedcar_vis.twb - Dashboard Tableau
```

## Problem Background

`Pasar mobil bekas, khususnya merek Mercedes-Benz, menunjukkan variasi harga yang cukup besar. Faktor seperti model mobil, tahun produksi, jenis transmisi, dan mileage diduga berpengaruh terhadap harga jualnya. Namun, belum banyak analisis berbasis data yang secara spesifik mengukur seberapa besar pengaruh masing-masing faktor tersebut.`

`Sebagai seorang data analyst, penting untuk mengkaji faktor-faktor tersebut agar dapat memberikan referensi yang jelas kepada penjual maupun pembeli mobil bekas. Dengan begitu, proses jual beli dapat dilakukan dengan lebih adil dan berdasarkan data yang objektif.`

## Project Output
`Output dari proyek ini berupa sebuah dashboard interaktif yang dibuat menggunakan Tableau untuk memvisualisasikan data secara informatif dan mudah dipahami.`

## Data
`Data yang digunakan dalam project ini diperoleh dari BigQuery. Terdapat 12 kolom dan 10000 baris `

```
1. Model - Tipe mobil
2. Year - Tahun mobil diproduksi
3. Price - Harga jual mobil bekas
4. Transmission - Jenis transmisi mobil
5. Mileage - Jarak tempuh mobil
6. Fuel Type - Jenis bahan bakar yang digunakan
7. Tax -  Pajak kendaraan
8. Fuel Efficiency - Konsumsi Bahan Bakar
9. Engine Size - Ukuran mesin mobil
```

## Method
`Metode yang digunakan dalam proyek ini dimulai dengan pengambilan data dari platform Kaggle, di mana dataset yang dipilih diunduh dalam format CSV. Setelah data berhasil diperoleh, langkah selanjutnya adalah melakukan proses pembersihan data (data cleaning) menggunakan Python dengan bantuan library seperti pandas dan numpy. Proses ini mencakup penghapusan data duplikat, penanganan nilai yang hilang (missing values), standarisasi format kolom, perbaikan nilai outlier, serta penyesuaian tipe data agar sesuai dengan kebutuhan analisis. Setelah data bersih dan siap dianalisis, file CSV hasil cleaning kemudian diimpor ke Tableau untuk divisualisasikan. Di dalam Tableau, dibuat dashboard interaktif yang menyajikan berbagai visualisasi data untuk menggambarkan insight penting, memudahkan interpretasi, serta mendukung pengambilan keputusan berbasis data.`

## Stacks
`Project ini menggunakan bahasa pemrogaman python dengan beberapa library dibawah ini :`

```
- Pandas untuk manipulasi data
- Seaborn: Untuk membuat visualisasi data yang lebih menarik dan informatif berbasis matplotlib, terutama untuk analisis statistik
- Matplotlib dan seaborn untuk visualisasi data
- numpy: Untuk operasi numerik dan komputasi array, termasuk fungsi matematika dasar
- scipy.stats: Untuk melakukan analisis statistik lanjutan, seperti uji hipotesis dan distribusi probabilitas.
```

## Reference
`Link Tableau Public : https://public.tableau.com/views/Usedcar_vis/Model?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link `
