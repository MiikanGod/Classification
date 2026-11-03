# 🚀 Machine Learning & Deep Learning Classification Portfolio

Repository ini berisi kumpulan proyek implementasi **Machine Learning** dan **Deep Learning** menggunakan Python di **Google Colab**. Proyek ini mencakup 3 jenis tugas klasifikasi utama yang berbeda karakteristik: Klasifikasi Biner, Klasifikasi Multi-Kelas, dan Klasifikasi Multi-Label.

---

## 🧠 3 Jenis Klasifikasi

Berikut adalah ringkasan konsep dari ketiga jenis klasifikasi yang diimplementasikan dalam proyek ini:

1. **Klasifikasi Biner (*Binary Classification*)**
   * **Konsep:** Model klasifikasi yang hanya memiliki **dua kategori atau pilihan label output** saja (pilihan biner: Ya/Tidak, 0/1, Positif/Negatif).
   * **Contoh Kasus dalam Proyek:** Memprediksi risiko *dropout* mahasiswa (status Ya/Tidak) berdasarkan data akademik.

2. **Klasifikasi Multi-Kelas (*Multi-Class Classification*)**
   * **Konsep:** Model di mana data harus dikelompokkan ke dalam **lebih dari dua kategori**, tetapi setiap sampel data **hanya boleh memiliki satu label/kelas utama** saja (pilih satu yang paling tepat).
   * **Contoh Kasus dalam Proyek:** Mengklasifikasikan Tipe Utama (*Type1*) Pokémon berdasarkan citra gambar dan metadata teks.

3. **Klasifikasi Multi-Label (*Multi-Label Classification*)**
   * **Konsep:** Model di mana satu sampel data dapat dikategorikan ke dalam **beberapa label atau kategori sekaligus secara bersamaan** (tidak dibatasi hanya satu kelas).
   * **Contoh Kasus dalam Proyek:** Memprediksi beberapa kondisi kesehatan mental secara bersamaan (*Growing_Stress*, *Changes_Habits*, *Mood_Swings*, *Coping_Struggles*) untuk satu individu.

---

## 📂 Struktur, Dataset, & Tautan Unduh

Berikut adalah rincian dataset yang digunakan beserta tautan sumber untuk mengunduhnya:

### 1. Klasifikasi Biner (Binary Classification) - Student Dropout Risk
* **Dataset File:** `student_dropout_risk_2026.csv`
* **Algoritma:** Random Forest Classifier
* 🔗 **[Unduh Dataset Student Dropout Risk](https://www.kaggle.com/datasets/mohankrishnathalla/student-academic-performance-and-dropout-risk)**

### 2. Klasifikasi Multi-Kelas (Multi-Class Classification) - Pokemon image dataset
* **Dataset File:** `pokemon.csv` & folder `images.zip`
* **Preprocessing Gambar:** Resize piksel ke **128x128** dengan normalisasi nilai warna ke rentang `[0, 1]`.
* **Algoritma:** Convolutional Neural Network (CNN)
* 🔗 **[Unduh Dataset & Gambar Pokémon](https://www.kaggle.com/datasets/vishalsubbiah/pokemon-images-and-types)**

### 3. Klasifikasi Multi-Label (Multi-Label Classification) - Mental Health
* **Dataset File:** `Mental Health Dataset.csv`
* **Algoritma:** MultiOutput Classifier (Random Forest)
* 🔗 **[Unduh Dataset Mental Health](https://www.kaggle.com/datasets/bhavikjikadara/mental-health-dataset)**

---

## 🛠️ Teknologi & Library yang Digunakan
* **Bahasa Pemrograman:** Python
* **Environment:** Google Colab, Jupyter Notebook
* **Manipulasi & Analisis Data:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Random Forest, LabelEncoder, TfidfVectorizer, MultiOutputClassifier)
* **Deep Learning (Computer Vision):** TensorFlow / Keras (CNN)
* **Visualisasi:** Matplotlib, Seaborn

---

## 🚀 Cara Menjalankan Proyek di Google Colab
1. Unduh atau clone repository ini beserta dataset yang diperlukan dari tautan di atas.
2. Buka [Google Colab](https://colab.research.google.com/).
3. Unggah file dataset yang dibutuhkan ke sesi Colab Anda.
4. Salin dan jalankan skrip Python yang tersedia pada masing-masing modul pelatihan model.
