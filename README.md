# Tentang Project
Analisis harga mobil bekas 989k data- BMW, Ford, Honda, Toyota | SQL Deepnote

**Sumber Data** Kaggle - Automotive Price Prediction Dataset
**Dataset:** 1.000.000 baris → 989 ribu baris setelah pembersihan data
**Tools:** SQL, Deepnote, Power BI
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
- 
- **4. Analisis Merek Berdasarkan Harga**
Porsche paling mahal se-dataset ($43.005 rata-rata harga)

### File di Repo Ini:
- `Notebook 1.ipynb` = Semua query SQL dan analisanya
- `README.md` = Ringkasan ini
