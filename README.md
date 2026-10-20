# UTS-Graf-Sains-Data-najmu-026
Tugas UTS Graf Sains Data

Proyek ini merupakan pengerjaan Ujian Tengah Semester (UTS) mata kuliah Graf Sains Data menggunakan dataset RetailRocket. Analisis dilakukan untuk mempelajari hubungan antara pengguna dan barang melalui graf, membentuk Vector Space Model (VSM), menghitung kemiripan antarbarang, serta membuat rekomendasi menggunakan metode K-Nearest Neighbors (KNN).

## Isi Repository

- `UTS-Graf-sains-data-najmu.ipynb` — notebook yang berisi kode, proses analisis, visualisasi, perhitungan similarity, rekomendasi KNN, dan evaluasi.
- File visualisasi graf — gambar hasil visualisasi graf interaksi pengguna dan barang serta kemiripan antarbarang.

## Dataset

Dataset dibagi menjadi dua periode:

- **P1 (Training):** 3 Mei 2015–21 Agustus 2015.
- **P2 (Testing):** 22 Agustus 2015–18 September 2015.

File dataset P1 dan P2 disimpan di Google Drive karena ukurannya terlalu besar untuk diunggah langsung ke repository GitHub.

**Link dataset:** [https://drive.google.com/drive/folders/1BzIeiHE3TsIhCKPTzCP17ce6lBZG3ubX?usp=sharing]

## Metode yang Digunakan

1. Eksplorasi data dan pembentukan graf menggunakan Neo4j.
2. Pembentukan VSM User dan VSM Item.
3. Perhitungan cosine similarity antarbarang.
4. Pembuatan rekomendasi menggunakan KNN.
5. Evaluasi rekomendasi menggunakan Hit@5 dan NDCG@5.
