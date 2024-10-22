# **Tugas Akhir Klasifikasi Apel 🍎**

Proyek ini bertujuan untuk mengklasifikasi **jenis-jenis apel** menggunakan model CNN. Dataset yang digunakan adalah subset dari **Fruit-360**, dataset publik dari platform Kaggle, dengan hanya mengambil gambar-gambar apel.

---

## 📂 **Deskripsi Dataset**
Dataset ini terdiri dari **10.104 gambar** dengan resolusi **100x100 piksel**, yang dikelompokkan menjadi **15 kelas apel** berikut:

| **Kelas**                | **Jumlah Gambar** |
|--------------------------|------------------:|
| Apple Golden 3           | 642               |
| Apple Golden 2           | 656               |
| Apple Red 2              | 656               |
| Apple Red Delicious 1    | 656               |
| Apple Pink Lady 1        | 608               |
| Apple Granny Smith 1     | 656               |
| Apple Hit 1              | 936               |
| Apple Braeburn 1         | 656               |
| Apple Red 3              | 573               |
| Apple 6                  | 630               |
| Apple Red Yellow 2       | 891               |
| Apple Golden 1           | 640               |
| Apple Red 1              | 656               |
| Apple Crimson Snow 1     | 592               |
| Apple Red Yellow 1       | 656               |

---

## 🛠️ **Arsitektur Model CNN**
Model yang digunakan memiliki arsitektur sebagai berikut:
- **4 Layer Convolution** dengan aktivasi ReLU dan MaxPooling
- **2 Layer Dense** dengan aktivasi ReLU dan Softmax untuk output

---

## 📊 **Evaluasi Model**
- Training Accuracy: 95.61%
- Validation Accuracy: 95.04%

