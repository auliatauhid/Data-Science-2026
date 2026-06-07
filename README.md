# 📊 Portofolio Data Science 2026
### Aulia Tauhid Akbar · PJJ Informatika · Angkatan 2026

---

## 👤 Identitas

| | |
|---|---|
| **Nama Lengkap** | Aulia Tauhid Akbar |
| **NIM** | *250401020136* |
| **Kelas** | *Data Science - IF405* |
| **Program Studi** | PJJ Informatika |
| **Institusi** | *Universitas Siber Asia* |

---

## 📖 Tentang Repository Ini

Halo! Saya Aulia Tauhid Akbar, mahasiswa PJJ Informatika angkatan 2026. Saya membangun repository ini sebagai ruang belajar dan dokumentasi perjalanan saya di dunia **Data Science** — dari fondasi pemrograman Python hingga membangun model Machine Learning pertama. Tujuan saya adalah memahami data tidak hanya sebagai angka, tetapi sebagai cerita yang bisa dianalisis, divisualisasikan, dan dijadikan dasar keputusan.

Repository ini berisi kumpulan notebook dari setiap pertemuan perkuliahan Data Science, mencakup topik-topik inti seperti eksplorasi data (EDA), pembersihan data (*data cleaning*), visualisasi statistik, hingga preprocessing dan pemodelan dengan `scikit-learn`. Setiap notebook ditulis dengan komentar dan penjelasan agar mudah dipahami kembali di kemudian hari.

## 🛠️ Tools & Library

```
Bahasa        : Python 3.x
Environment   : Google Colab / Jupyter Notebook
```

| Kategori | Library |
|---|---|
| **Manipulasi Data** | `pandas`, `numpy` |
| **Visualisasi** | `matplotlib`, `seaborn` |
| **Machine Learning** | `scikit-learn` (LinearRegression, StandardScaler, train_test_split) |
| **Statistik** | `scipy` |
| **Akses Data** | `requests`, `gdown` |

---

## ▶️ Cara Menjalankan

### Opsi 1 — Google Colab (Dianjurkan)
Klik badge Colab di bagian atas setiap notebook, lalu pilih **"Run All"** dari menu Runtime.

### Opsi 2 — Lokal
```bash
# Clone repository
git clone https://github.com/auliatauhid/Data-Science-2026.git
cd Data-Science-2026

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn scipy requests gdown

# Jalankan Jupyter
jupyter notebook
```

---

## 🧭 Kesimpulan Perjalanan Belajar (Pertemuan 1–7)

Perjalanan belajar Data Science selama 7 pertemuan ini membentuk pemahaman yang terstruktur — dimulai dari hal yang paling mendasar hingga menyentuh ranah Machine Learning. Berikut ringkasannya:

**Pertemuan 1** meletakkan fondasi Python yang esensial: cara mencetak output, mendefinisikan variabel, bekerja dengan list, dan membuat fungsi yang modular dan dapat digunakan ulang.

**Pertemuan 2** memperkenalkan `pandas` sebagai tulang punggung analisis data — memuat dataset nyata (Titanic), mengeksplorasi strukturnya, dan menemukan pola pertama: status sosial-ekonomi (kelas tiket) berkorelasi kuat dengan tingkat keselamatan penumpang.

**Pertemuan 3** membangun pipeline *data cleaning* yang realistis pada dataset properti yang "kotor" — menangani missing values, outlier dengan metode IQR clip, inkonsistensi penulisan nama kota, hingga mengakses data dari REST API eksternal.

**Pertemuan 4** mendalami statistik deskriptif dan distribusi menggunakan dataset Iris — memahami skewness, kurtosis, korelasi Pearson, dan menemukan bahwa fitur *petal* jauh lebih informatif dibanding *sepal* untuk membedakan spesies.

**Pertemuan 5** naik level ke visualisasi multi-panel profesional menggunakan `GridSpec` Matplotlib — membangun dashboard lengkap untuk dataset Diamonds dan menemukan *paradoks Cut vs Harga* yang dijelaskan oleh pengaruh berat karat (Simpson's Paradox).

**Pertemuan 6** masuk ke ranah Machine Learning dengan membangun preprocessing pipeline yang benar: encoding kategorikal, *stratified train-test split* untuk menjaga proporsi kelas yang tidak seimbang, dan *feature scaling* dengan `StandardScaler` yang di-fit hanya pada data training.

**Pertemuan 7** menyelesaikan siklus pertama ML dengan melatih model `LinearRegression`, menginterpretasikan koefisien sebagai ukuran pengaruh fitur, dan mengevaluasi performa model menggunakan MAE, RMSE, dan R² — dilengkapi dengan *residual plot* untuk memvalidasi asumsi linearitas.

> Secara keseluruhan, 7 pertemuan ini membentuk **siklus penuh data science**: *mendapat data → membersihkan → mengeksplorasi → memvisualisasikan → memproses → memodelkan → mengevaluasi*. Fondasi ini menjadi bekal untuk topik yang lebih lanjut seperti klasifikasi, regularisasi, dan deep learning.

---

<div align="center">
  <sub>Dibuat oleh Aulia Tauhid Akbar · 2026</sub>
</div>
