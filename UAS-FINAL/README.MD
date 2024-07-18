



# Judul Proyek: Proyek Prediksi Cuaca



### Identitas
- **Penulis:** **Indra Fadillah**
- **Nim:** **A11.2022.14186**
- **Tanggal:** **18-07-2024**

### Ringkasan
Tujuan dari proyek ini adalah untuk memprediksi kondisi cuaca menggunakan model pembelajaran mesin. Proyek ini melibatkan prapemrosesan data, analisis data eksploratif (EDA), rekayasa fitur, pelatihan model, dan evaluasi.

### Permasalahan
Prediksi cuaca sangat penting untuk perencanaan di berbagai sektor, termasuk pertanian, transportasi, dan manajemen bencana. Prediksi cuaca yang akurat dapat membantu mengurangi dampak buruk dan mengoptimalkan operasi.

### Model Penyelesaian / Alur Kerja
1. **Pengumpulan Data:** Mengumpulkan data cuaca dari sumber yang dapat dipercaya.
2. **Prapemrosesan Data:** Membersihkan dan mentransformasikan data.
3. **Analisis Data Eksploratif (EDA):** Memahami data melalui visualisasi dan statistik.
4. **Rekayasa Fitur:** Membuat fitur yang relevan untuk model.
5. **Pelatihan Model:** Melatih model pembelajaran mesin.
6. **Evaluasi Model:** Menilai kinerja model.

## Dataset
### Deskripsi
Dataset yang digunakan dalam proyek ini berisi data cuaca historis. Setiap baris mewakili kondisi cuaca yang dicatat pada waktu tertentu.
Link : https://www.kaggle.com/datasets/ananthr1/weather-prediction

### Fitur
- **Tanggal:** Tanggal pencatatan data.
- **Suhu:** Suhu dalam derajat Celsius.
- **Kelembapan:** Persentase kelembapan.
- **Kecepatan Angin:** Kecepatan angin dalam km/jam.
- **Presipitasi:** Jumlah presipitasi dalam mm.
- **Kondisi:** Kondisi cuaca (misalnya, cerah, hujan).

## Analisis Data Eksploratif (EDA)
Proses EDA melibatkan pemeriksaan dataset untuk menemukan pola, anomali, dan hubungan antar fitur. Wawasan utama dari EDA akan memandu proses rekayasa fitur dan pemilihan model.

### Visualisasi
- **Distribusi Suhu**
- **Tingkat Kelembapan**
- **Analisis Kecepatan Angin**
- **Pola Presipitasi**
- **Heatmap Korelasi**

## Rekayasa Fitur
### Proses
- Menangani nilai yang hilang.
- Mengkodekan variabel kategorikal.
- Melakukan skala pada fitur numerik.
- Membuat fitur baru berdasarkan data yang ada.

## Pelatihan dan Evaluasi Model
### Model yang Digunakan
- **Regresi Linear**
- **Decision Tree**
- **Random Forest**
- **Gradient Boosting**

## Diskusi
### Temuan
- Fitur yang paling berpengaruh untuk memprediksi kondisi cuaca.
- Perbandingan kinerja model.
- Wawasan dari analisis pentingnya fitur.

### Tantangan
- Menangani data yang hilang.
- Mengatasi ketidakseimbangan kelas dalam variabel target.

## Kesimpulan
Proyek ini menunjukkan proses membangun model prediksi cuaca menggunakan pembelajaran mesin. Hasil menunjukkan bahwa model ensemble seperti Random Forest dapat memberikan prediksi yang akurat. Pekerjaan di masa depan bisa melibatkan penerapan model dan integrasi data real-time untuk peningkatan berkelanjutan.
