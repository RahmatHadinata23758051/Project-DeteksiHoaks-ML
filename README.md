# Indonesian Hoax News Detection using Machine Learning

## 1. Executive Summary

Proyek ini berfokus pada pengembangan model Artificial Intelligence (AI) untuk melakukan klasifikasi otomatis terhadap berita hoaks berbahasa Indonesia. Menggunakan pendekatan Natural Language Processing (NLP), model ini dirancang untuk membantu memvalidasi informasi digital secara cepat dan akurat.

## 2. Metodologi & Workflow

Sistem ini dibangun dengan mengikuti alur kerja Machine Learning yang sistematis untuk memastikan hasil yang valid dan dapat dipertanggungjawabkan.

### Alur Kerja (Pipeline):

Data Acquisition: Mengambil data dari Kaggle.

Text Preprocessing: Cleaning, Tokenizing, dan Stopword Removal.

Feature Engineering: Menggunakan TF-IDF Vectorizer (Unigram & Bigram).

Modeling: Algoritma Logistic Regression.

Evaluation: Pengujian akurasi dan performa.

Visualisasi Pipeline Proyek:

<img width="12016" height="10564" alt="Pipeline" src="https://github.com/user-attachments/assets/3d17ebda-999c-466d-9a49-224755d53efa" />


## 3. Analisis Dataset

Dataset yang digunakan dalam proyek ini bersumber dari platform Kaggle: Deteksi Berita Hoaks Indo Dataset. Dataset ini mencakup total 23.944 data berita yang telah dibersihkan (cleaned) dengan rincian pelabelan sebagai berikut:

Label 0 (Valid): Berita terverifikasi dari sumber terpercaya seperti Antara News, Detik, dan Kompas.

Label 1 (Hoaks): Berita hasil fabrikasi atau disinformasi yang dikumpulkan dari TurnBackHoax (MAFINDO).

## 4. Hasil dan Evaluasi Model

Model berhasil mencapai performa yang sangat impresif pada data uji:

Akurasi: 98.08%

Precision/Recall: 0.98

Matriks Evaluasi (Confusion Matrix):

<img width="751" height="590" alt="image" src="https://github.com/user-attachments/assets/fb0cf480-2dc4-4545-8784-f9e820c077a6" />


## 5. Cara Menggunakan Model

Model disimpan dalam format .pkl yang dapat dimuat kembali menggunakan library joblib.

Load tfidf_vectorizer.pkl.

Load logistic_regression_hoax_model.pkl.

Masukkan teks berita baru untuk mendapatkan prediksi kategori.

## 6. Kesimpulan

Penggunaan Logistic Regression terbukti sangat efektif untuk klasifikasi teks hoaks karena mampu menangkap pola diksi tertentu yang sering digunakan dalam berita bohong di Indonesia.

Dibuat oleh: Rahmat Hadinata

Project: Tugas TOR Magang AI Engineer.
