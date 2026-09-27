# 🚗 Analisis Harga Kendaraan

## 📌 Gambaran Project

Project ini bertujuan untuk menganalisis data kendaraan guna mengetahui
faktor-faktor yang berkaitan dengan harga kendaraan.

Analisis dilakukan menggunakan SQL, mulai dari data profiling,
data quality checking, data cleaning, hingga exploratory data analysis.

## 🎯 Tujuan Analisis

- Memahami karakteristik data kendaraan
- Mengidentifikasi masalah kualitas data
- Melakukan proses data cleaning
- Menganalisis faktor-faktor yang berkaitan dengan harga kendaraan
- Menghasilkan insight dan rekomendasi berdasarkan hasil analisis

## 🛠️ Tools yang Digunakan

- MySQL
- Deepnote
- GitHub

## 📊 Dataset

Dataset terdiri dari 1.000.000 data kendaraan dengan beberapa informasi,
antara lain:

- Make
- Model
- Year
- Mileage
- Engine HP
- Transmission
- Fuel Type
- Drivetrain
- Body Type
- Condition
- Accident History
- Vehicle Age
- Price

### 🔗 Sumber Data

Dataset diperoleh dari:
[Kaggle](https://www.kaggle.com/datasets/metawave/vehicle-price-prediction)

## 🧹 Data Cleaning & Data Quality

Tahapan yang dilakukan:

1. Data profiling
2. Pemeriksaan missing value
3. Pemeriksaan duplicate
4. Pemeriksaan data type
5. Pemeriksaan invalid value
6. Pemeriksaan  outlier
7. Validasi tahun dan usia kendaraan

## 📈 Analisis

Analisis yang dilakukan:

1. Statistik awal
2. Harga berdasarkan usia kendaraan
3. Harga berdasarkan mileage
4. Harga berdasarkan engine HP
5. Harga berdasarkan kondisi kendaraan
6. Harga berdasarkan accident history
7. Harga berdasarkan model
8. Analisis Make × Condition

## 💡 Insight

### 1. Harga dan Usia Kendaraan

Harga kendaraan cenderung lebih rendah ketika usia kendaraan semakin tinggi. Kendaraan berusia 1–5 tahun memiliki rata-rata harga yang jauh lebih tinggi dibandingkan kendaraan berusia 10–25 tahun.

### 2. Harga dan Mileage

Kendaraan dengan mileage yang lebih tinggi cenderung memiliki harga yang lebih rendah. Kendaraan dengan mileage terendah memiliki rata-rata harga lebih dari tiga kali kendaraan dengan mileage tertinggi.

### 3. Harga dan Engine HP

Kendaraan dengan tenaga mesin lebih tinggi cenderung memiliki harga yang lebih tinggi. Kelompok kendaraan dengan 300–581 HP memiliki rata-rata harga hampir tiga kali kelompok 90–162 HP.

### 4. Merek dan Kondisi Kendaraan

Kendaraan dengan kondisi Excellent cenderung memiliki
rata-rata harga lebih tinggi dibandingkan kondisi Good dan Fair
dalam masing-masing merek.

## 💼 Rekomendasi

- Kondisi kendaraan dapat dijadikan salah satu pertimbangan dalam
  menentukan strategi harga.
- Usia dan mileage kendaraan dapat digunakan sebagai faktor pendukung
  dalam menentukan harga.
- Kendaraan dengan kondisi yang lebih baik dapat diposisikan pada
  rentang harga yang lebih tinggi.
- Analisis lebih lanjut dapat dilakukan untuk mengetahui karakteristik
  kendaraan dengan harga tinggi.
