# 🧠 Customer Churn Prediction

## 📋 Deskripsi Proyek  
Proyek ini bertujuan untuk **memprediksi pelanggan yang berpotensi churn (berhenti berlangganan)** menggunakan dataset *Telco Customer Churn*.  
Model dikembangkan dengan **Python (scikit-learn)** menggunakan algoritma **Random Forest Classifier** dan **Logistic Regression** sebagai pembanding.  

Hasil prediksi divisualisasikan dalam berbagai grafik seperti:
- ✅ *Confusion Matrix*  
- 📈 *ROC Curve*  
- 📊 *Distribusi Probabilitas Churn*  
- 🔁 *Perbandingan Aktual vs Prediksi*

---

## 🛠️ Tools & Teknologi  
| Kategori | Teknologi |
|-----------|------------|
| Bahasa Pemrograman | Python |
| Framework ML | scikit-learn |
| Visualisasi | Matplotlib |
| Manajemen Model | joblib |
| Lingkungan | Google Colab |

---

## 🚀 Fitur Utama  
- 🔹 **Preprocessing Otomatis**: Mengatasi missing values & encoding fitur kategorikal.  
- 🔹 **Optimisasi Model**: GridSearchCV untuk mencari hyperparameter terbaik.  
- 🔹 **Evaluasi Model**: Metrik akurasi, precision, recall, dan ROC AUC.  
- 🔹 **Visualisasi**: Grafik kinerja model & distribusi probabilitas churn.  
- 🔹 **Model Deployment Ready**: Model disimpan dalam format `.joblib` untuk penggunaan lanjutan.

---

## 📊 Hasil Model  
| Model | Akurasi | ROC AUC | Catatan |
|--------|----------|----------|----------|
| Logistic Regression | 80.5% | 0.84 | Model baseline |
| Random Forest | **89.0%** | **0.88** | Model utama (setelah tuning) |

---

## ⚙️ Cara Menjalankan Proyek  

### 1️⃣ Instalasi Dependensi  
Pastikan sudah memiliki Python 3.9+  
Lalu jalankan perintah berikut:
```bash
pip install -r requirements.txt
