Sip, kalau project ini mau kamu taruh di GitHub, kamu bisa bikin **README.md** biar terlihat rapi dan jelas.
Berikut contoh isi README untuk project prediksi penjualan kopi dengan **Linear Regression** dan **Random Forest**:

---

# ☕ Coffee Sales Prediction with Machine Learning

## 📌 Project Overview

Proyek ini bertujuan untuk **memprediksi jumlah penjualan kopi Arabica** berdasarkan variabel seperti harga per 100g dan rating menggunakan **Machine Learning**.
Model yang digunakan:

* **Linear Regression**
* **Random Forest Regressor**

Perbandingan kedua model dilakukan untuk melihat mana yang lebih baik dalam menangkap pola data dan memberikan prediksi yang akurat.

---

## 📂 Dataset

Dataset berisi informasi mengenai:

* `100g_USD` → Harga kopi per 100 gram (USD)
* `rating` → Rating kualitas kopi
* `Jumlah` → Jumlah penjualan (target yang diprediksi)

---

## ⚙️ Tech Stack

* Python 3.x
* Pandas, NumPy → Data preprocessing
* Scikit-learn → Machine Learning (Linear Regression, Random Forest, Train-Test Split, Evaluasi)
* Matplotlib → Visualisasi hasil

---

## 🔎 Steps

1. Import dan eksplorasi dataset
2. Data preprocessing (memilih fitur, handle missing values)
3. Membagi data menjadi **train** dan **test**
4. Membangun model **Linear Regression**
5. Membangun model **Random Forest**
6. Mengevaluasi performa model dengan:

   * Mean Squared Error (MSE)
   * R² Score
7. Visualisasi hasil prediksi

---

## 📊 Results

* **Linear Regression**: Memberikan prediksi sederhana namun terbatas pada hubungan linier.
* **Random Forest**: Lebih fleksibel dalam menangkap pola non-linear dan memberikan hasil yang lebih akurat.

📈 Random Forest terbukti lebih unggul dibanding Linear Regression pada dataset ini.

---

## 🚀 Future Work

* Menambahkan variabel lain (asal kopi, metode roasting, dll.)
* Hyperparameter tuning (GridSearchCV untuk Random Forest)
* Membandingkan dengan model lain seperti **SVR** atau **XGBoost**

---

## 👤 Author

**Dimas Putra Nugroho**

* 🎓 S1 Sistem Informasi, Telkom University Purwokerto
* 💡 Interest: Machine Learning, Data Analytics, Business Intelligence

---
