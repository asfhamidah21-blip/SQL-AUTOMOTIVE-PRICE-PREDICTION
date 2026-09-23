# Tentang Project
Analisis harga mobil bekas 989k data- BMW, Ford, Honda, Toyota | SQL Deepnote

**Sumber Data** Kaggle - Automotive Price Prediction Dataset
**Dataset:** 1.000.000 baris → 989 ribu baris setelah pembersihan data
**Tools:** SQL, Deepnote
**Tujuan:** Portfolio Data Analyst


### Apa Yang Aku Kerjakan:
- Hapus data duplikat (dari 1jt jadi 989k)
- Menganalisa harga terendah pada data yang tersedia
- menganalisa jadi 4 bagian: harga, spek mesin, merek mobil dan tahun mobil.

### Hasil Temuan:

**1. Analisis Harga Berdasarkan Mobil dan Tahun (Kategori BMW, Honda, Toyota & Ford)  - BMW Paling Mahal**
Tahun 2020 harga rata-rata BMW $32.004, Honda cuma $15.142. Beda 2x lipat. Merek premium memang tahan harga.

**2. Kilometer Ekstrim >200rb = Harga Anjlok 4x Lipat**
- KM <50rb : harga ~$32811.0
- KM >200rb (Ekstrim) : harga ~$7485.0
Artinya pembeli takut kalau KM udah lewat 100rb, lewat dari itu harga terjun bebas.

**3. Umur Mobil - Depresiasi Stabil 10% per Tahun**
- Mobil umur 1 tahun: $39.425
- Mobil umur 10 tahun: $15.807 (turun 60%)
- Tahun pertama hampir tidak turun (1,1%), setelah itu turun konsisten 9-12% tiap tahun.
- Insight: Tidak ada anjlok mendadak, depresiasi mobil bekas itu linier dan stabil setelah tahun ke-2.
  
- **4. Analisis Merek Berdasarkan Harga**
Porsche paling mahal se-dataset ($43.005 rata-rata harga)

### Rekomendasi

**1. Untuk Penjual Mobil Bekas:**
- Sebaiknya fokus pada mobil dengan kilometer rendah (<50rb) karena harganya masih tinggi sekitar $32.811
- Mobil dengan kilometer di atas 200rb harganya turun jauh menjadi $7.485, jadi kurang menguntungkan untuk dijual kembali
- Untuk segmen mewah, merek Porsche ($43.005) dan Land Rover ($39.501) bisa menjadi pilihan utama
- Untuk segmen umum, BMW memiliki harga yang paling stabil dibanding Honda, Toyota, dan Ford

**2. Untuk Pembeli Mobil Bekas:**
- Waktu terbaik membeli adalah mobil umur 3 tahun, karena harganya sudah turun sekitar $4.000 dari harga baru tapi kondisinya masih bagus
- Disarankan menghindari mobil dengan kilometer di atas 100rb karena harganya akan turun sangat cepat

**3. Untuk Pengembangan Selanjutnya:**
- Untuk membuat model prediksi harga, 3 faktor terpenting adalah merek mobil, umur mobil, dan kilometer

### File di Repo Ini:
- `Notebook 1 (1).ipynb` = Semua query SQL dan analisanya
- `README.md` = Ringkasan ini
