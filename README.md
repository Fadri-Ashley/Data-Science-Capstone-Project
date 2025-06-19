# 🧠 Obesity Level Prediction – Data Science Capstone Project

Capstone project ini bertujuan untuk membangun sistem prediksi tingkat obesitas berdasarkan data pribadi dan kebiasaan hidup seseorang. Proyek ini dilakukan sebagai tugas akhir dari mata kuliah **Bengkel Koding - Data Science** di Universitas Dian Nuswantoro.

---

## 🔍 Tujuan Proyek

Mengembangkan model klasifikasi machine learning untuk memprediksi tingkat obesitas (NObeyesdad) berdasarkan berbagai variabel seperti usia, tinggi badan, kebiasaan makan, dan aktivitas fisik, lalu mengimplementasikan model tersebut ke dalam aplikasi web interaktif menggunakan **Flask**.

---

## 📌 Tahapan Proyek

### 1. 🧠 *Persiapan & Pembelajaran* 

Sebelum memulai proyek, pastikan telah menguasai materi berikut:

* **Python Dasar**
* **Library Data Science**:

  * `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
* **Statistik Dasar**:

  * Distribusi, korelasi, outlier, regresi, dsb
* **Exploratory Data Analysis (EDA)**
* **Preprocessing Data**
* **Machine Learning Klasifikasi**
* **Evaluasi Model**:

  * Accuracy, Precision, Recall, F1-Score
* **Pickle**: untuk menyimpan model
* **Flask**: untuk membuat aplikasi web
* **Obesity Dataset**: sebagai sumber data

---

### 2. 🛠️ *Pembuatan Model Machine Learning* 

* Lakukan EDA dan preprocessing data
* Tangani missing value, duplikasi, outlier, dan data imbalance
* Buat model klasifikasi (min. 3 algoritma)
* Evaluasi model menggunakan metrik yang sesuai
* Simpan model terbaik menggunakan `pickle`

---

### 3. 📐 *Analisis Kebutuhan Aplikasi Web (Flask)*

#### ✅ **Fitur Utama:**

1. **Form Input Data**

   * Gender, Age, Height, Weight
   * family\_history\_with\_overweight, FAVC, FCVC, NCP
   * CAEC, SMOKE, CH2O, SCC, FAF, TUE, CALC, MTRANS
2. **Prediksi Hasil**

   * Prediksi tingkat obesitas berdasarkan input
   * Confidence score (jika memungkinkan)
3. **Tampilan UI**

   * Judul aplikasi: *Obesity Level Predictor*
   * Deskripsi proyek
   * Hasil prediksi
   * Visualisasi sederhana (misal: distribusi kelas obesitas)

---

### 4. 🎨 *Desain UI*

* Desain tampilan web menggunakan Figma
* Pastikan layout mudah dipahami dan responsif

---

### 5. 💻 *Implementasi Aplikasi*

* Gunakan **Flask** untuk membangun aplikasi
* Integrasikan form input dengan model `.pkl`
* Tampilkan hasil prediksi dalam antarmuka web

---

### 6. 🚀 *Deployment* 

* Deploy aplikasi ke platform **Render**
* Buat akun, hubungkan GitHub repository, dan setting environment

---

### 7. 🎤 *Presentasi Proyek* (I'm Here)

* Siapkan slide presentasi
* Pahami alur data, preprocessing, model, dan deployment

#### 📊 **Bobot Penilaian:**

* 💻 Coding: **50%**
* ❓ Tanya Jawab: **20%**
* 🌐 Model Deployment: **30%**
