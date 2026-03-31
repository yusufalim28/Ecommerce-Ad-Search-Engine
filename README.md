# Simple Text Search Engine using NLP (Bag of Words & Cosine Similarity)

Proyek ini adalah implementasi sistem pencarian dokumen sederhana menggunakan teknik **Natural Language Processing (NLP)**. Sistem ini bekerja dengan memproses teks mentah, mengubahnya menjadi representasi vektor, dan menghitung tingkat kemiripan antara kueri pengguna dengan dokumen yang tersedia.

## 👥 Kelompok 1 - Informatika
Proyek ini disusun oleh:
* **Siti Malikha** (2388010001)
* **Maemunah Halimatus Sa'diyah** (2388010026)
* **Yusuf Alim Romadon** (2388010010)

**Mata Kuliah:** Natural Language Processing (NLP)
**Institusi:** UIN Siber Syekh Nurjati Cirebon

---

## 🚀 Fitur Utama
Sistem ini mencakup alur kerja *end-to-end* pengolahan teks:
1. **Preprocessing Teks**: 
   * Case Folding (Lowercase)
   * Cleaning (Pembersihan simbol/emoji)
   * Tokenizing (Pemecahan kata)
   * Stemming menggunakan library **Sastrawi** untuk bahasa Indonesia
2. **Representasi Bag of Words (BoW)**: Mengubah dokumen menjadi Document-Term Matrix (DTM) menggunakan `CountVectorizer`.
3. **Similarity Engine**: Menghitung skor kemiripan menggunakan **Cosine Similarity**.
4. **Search Functionality**: Mencari 3 dokumen paling relevan berdasarkan kueri input.

## 📊 Dataset
Dataset yang digunakan terdiri dari 10 dokumen pendek yang diambil dari iklan otomatis dan landing page WhatsApp Commerce brand fashion/parfum (Scentplus).

## 🛠️ Teknologi yang Digunakan
* **Python**
* **Sastrawi** (Stemmer Bahasa Indonesia)
* **Scikit-Learn** (CountVectorizer & Cosine Similarity)
* **Pandas** (Data Manipulation)
* **Matplotlib** (Visualisasi Frekuensi Kata)

## 🏃 Cara Menjalankan
1. Clone repositori ini:
   ```bash
   https://github.com/yusufalim28/Ecommerce-Ad-Search-Engine.git
2. Instal library yang dibutuhkan:
   pip install Sastrawi scikit-learn pandas matplotlib
3. Buka file Kelompok1.ipynb menggunakan Jupyter Notebook atau Google Colab.
4. Jalankan semua cell untuk melihat demo pencarian.
