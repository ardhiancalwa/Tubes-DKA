# Sistem Evaluasi Fuzzy dengan Metode Mamdani & Sugeno

Repository ini mengimplementasikan sebuah sistem evaluasi berbasis logika fuzzy untuk menentukan skor evaluasi, dengan menggunakan dua metode inferensi utama, yaitu Mamdani dan Sugeno.

## Fitur Utama

- **Data Preprocessing**: Memuat dataset `winequality-red.csv` dan menyiapkan data dengan fitur relevan.
- **Fuzzification**: Mengubah nilai numerik pada fitur (*alcohol*, *volatile acidity*, dan *sulphates*) menjadi derajat keanggotaan fuzzy.
- **Inference Rules**: Menetapkan aturan fuzzy untuk kedua metode:
  - **Mamdani**: Menghasilkan output fuzzy dan melakukan defuzzifikasi menggunakan Center of Gravity (COG).
  - **Sugeno**: Menghitung skor evaluasi secara langsung melalui perhitungan berbobot.
- **Defuzzification**: Mengkonversi output fuzzy pada metode Mamdani ke nilai skor akhir.
- **Evaluasi & Analisis**: Menampilkan hasil prediksi serta melakukan perbandingan statistik antara metode Mamdani dan Sugeno menggunakan histogram dan boxplot.

## Teknologi

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib & Seaborn**
- **scikit-learn**

## Cara Menjalankan

Proyek ini dijalankan melalui [Tubes_DKA.ipynb](d:/Collage/Matkul%20Informatika/Semester%204/Dasar%20Kecerdasan%20Artificial/Tubes/Tubes/Tubes_DKA.ipynb) pada Jupyter Notebook atau VS Code Notebook.

Proyek ini merupakan implementasi praktis logika fuzzy untuk analisis kualitas (atau evaluasi) dengan memanfaatkan kedua metode inferensi fuzzy, Mamdani dan Sugeno.