# Klasifikasi Sentimen Ulasan ChatGPT
Proyek ini bertujuan untuk mengklasifikasikan ulasan pengguna aplikasi ChatGPT di Android ke dalam dua
kategori sentimen: **Positif** dan **Negatif**, menggunakan algoritma **Support Vector Machine (SVM)** dan
ekstraksi fitur dengan **TF-IDF**.

# Dataset
Dataset asli dari Kaggle: https://www.kaggle.com/datasets/thedevastator/chatgpt-user-feedback
Salinan cadangan: https://drive.google.com/drive/folders/1mE6V0mxLFdVwqiR0R0wK7Z2sGTxCHtG8?hl=id 

# Cara Menggunakan
1. Buka file `Final_Project_ML.ipynb` di Google Colab
2. Jalankan seluruh cell dari atas hingga bawah
3. Di bagian akhir, gunakan antarmuka **Gradio** untuk memasukkan
   ulasan dan melihat hasil klasifikasi secara langsung

##  Contoh Hasil Prediksi
- “Aplikasi ini sangat membantu dan responsif.” → **Positif**  
- “Sering error dan tidak bisa login.” → **Negatif** 

## Daftar File
- UAS.ipynb → Berisi seluruh kode
- svm_model.joblib → File model SVM yang sudah dilatih
- tfidf_vectorizer.joblib → Vectorizer TF-IDF untuk data teks
