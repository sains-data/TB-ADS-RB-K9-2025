# 📊 TUGAS BESAR ANALISIS DATA STATISTIKA 2025
## Penerapan Analisis Data Eksplorasi (EDA) pada Data Antropometri Mahasiswa ITERA Menggunakan RStudio
### Tugas Besar Analisis Data Statistika 2025 – Kelompok 9 RB

Repositori ini berisi proyek Tugas Besar mata kuliah **Analisis Data Statistika 2025** oleh Kelompok 9 RB.  
Fokus utama proyek adalah **Statistik Deskriptif** dan **Eksplorasi Data (EDA)** pada variabel antropometri mahasiswa ITERA, yaitu **Tinggi Badan**, **Berat Badan**, dan **Indeks Massa Tubuh (IMT)**.

**Temuan Utama:**  
Distribusi IMT menunjukkan **skewness positif yang tinggi** (≈ 9.951) akibat adanya **outlier ekstrem**, meskipun sebagian besar mahasiswa berada dalam kategori **Gizi Normal**.

---

## 🛠️ Cara Menjalankan Script R

Skrip utama analisis terdapat pada file **`codeR_9_RB.Rmd`**.  
Untuk menjalankan analisis:

1. **Unduh repositori ini** (clone atau download ZIP).  
2. **Buka RStudio** dan atur *working directory* ke folder repositori.  
3. **Instal semua paket yang diperlukan** (lihat daftar di bawah).  
4. **Buka `codeR_9_RB.Rmd`** dan jalankan seluruh chunk dari awal hingga akhir.

### 📦 Paket R yang Digunakan
- `dplyr` – manipulasi dan pembersihan data  
- `ggplot2` – visualisasi (Histogram, Boxplot, Bar Plot, dll.)  
- `e1071` – perhitungan skewness  
- `readr` – impor dataset CSV  

---

## 🔬 Penjelasan Dataset

- **Dataset Mentah:**  
  `dataset asil ads - Sheet1.csv` adalah data asli hasil survei mahasiswa.

- **Dataset Bersih:**  
  `data_bersih_fix - Sheet1.csv` merupakan dataset final yang sudah melewati proses *data cleaning*.

- **Variabel yang Dianalisis:**  
  - Tinggi Badan  
  - Berat Badan  
  - Indeks Massa Tubuh (IMT) → dihitung dari data tinggi dan berat

---

## 📁 Struktur Repositori

| File/Folder                          | Keterangan                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| **codeR_9_RB.Rmd**                  | Skrip lengkap R (R Markdown) berisi seluruh proses analisis IMT.           |
| **data_bersih_fix - Sheet1.csv**    | Dataset final yang telah divalidasi dan siap dianalisis.                   |
| **Poster_9_RB.png**                 | Poster/visualisasi ringkasan hasil analisis.                               |
| **README.md**                       | File deskripsi repositori ini.                                             |

---

# 🧑‍🤝‍🧑 Anggota Kelompok  
- **Rafli Al Mansyah Tambunan (124450007)**  
- **Yulia Kristine Malau (124450119)**  
- **Muhammad Rizaldi (124450093)**  
- **Fitra Pratama Mega (124450070)**  

---

## ©️ Lisensi

Repositori ini dibuat untuk keperluan akademis (Tugas Besar ADS 2025) dan dapat digunakan kembali sebagai referensi pembelajaran.
