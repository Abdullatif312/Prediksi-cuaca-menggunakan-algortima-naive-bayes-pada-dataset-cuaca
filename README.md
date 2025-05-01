
# Prediksi Cuaca dengan Algoritma Naive Bayes

Notebook ini berisi eksperimen data mining untuk memprediksi apakah seseorang akan bermain atau tidak berdasarkan kondisi cuaca menggunakan algoritma **Naive Bayes**.

## Dataset
Dataset yang digunakan berisi data kategorikal tentang kondisi cuaca:
- `Outlook`: Cerah, Mendung, Hujan
- `Temp`: Suhu udara (Panas, Sedang, Dingin)
- `Humidity`: Kelembapan (Tinggi, Naormal)
- `Windy`: Kondisi berangin (True/False)
- `Play`: Target variabel (Yes/No)

## Langkah-Langkah
1. **Import library dan data**
2. **Pra-pemrosesan** data (encoding kategorikal)
3. **Split data** menjadi latih dan uji
4. **Pelatihan model** menggunakan `CategoricalNB`
5. **Evaluasi model**: Akurasi dan laporan klasifikasi
6. **Visualisasi hasil** menggunakan Confusion Matrix

## Hasil
Model Naive Bayes mampu mengklasifikasikan data dengan cukup baik. Visualisasi Confusion Matrix ditampilkan di akhir notebook untuk memperjelas performa klasifikasi.

## Dependensi
- `pandas`
- `scikit-learn`
- `matplotlib`

## Cara Menjalankan
Buka file notebook `Predikisi_Cuaca_Algoritma_Naive_Bayes.ipynb` ini di Jupyter Notebook atau JupyterLab, lalu jalankan setiap sel dari atas ke bawah.

## Penulis
Notebook ini dibuat sebagai demonstrasi sederhana untuk klasifikasi data kategorikal menggunakan Naive Bayes dalam Bahasa Indonesia.
