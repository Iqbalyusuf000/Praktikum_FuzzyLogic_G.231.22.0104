# Praktikum Fuzzy Logic & ANFIS

Repository ini berisi kumpulan notebook praktikum yang membahas **Sistem Inferensi Fuzzy** dan **ANFIS (Adaptive Neuro-Fuzzy Inference System)** sebagai bagian dari kegiatan praktikum / pembelajaran sistem cerdas.

## 📂 Daftar File

| File | Deskripsi |
|-----|----------|
| `Praktikum_FuzzyMamdani_G_231_22_0104.ipynb` | Implementasi **Fuzzy Mamdani**, mencakup fuzzifikasi, rule base, inferensi, agregasi, dan defuzzifikasi (Centroid, Bisector, MOM). |
| `Praktikum_FuzzySugeno_G_231_22_0104.ipynb` | Implementasi **Fuzzy Sugeno**, dengan output berupa fungsi linier dan perhitungan weighted average. |
| `Praktikum_FuzzyTsukamoto_G_231_22_0104.ipynb` | Implementasi **Fuzzy Tsukamoto**, menggunakan fungsi keanggotaan monoton dan defuzzifikasi berbasis rata-rata terbobot. |
| `Praktikum_ANFIS_G_231_22_0104.ipynb` | Implementasi **ANFIS (Adaptive Neuro-Fuzzy Inference System)** secara manual, termasuk firing strength, normalisasi, dan least squares untuk consequent parameter. |

## 🧠 Materi yang Dipelajari

- Konsep dasar **Fuzzy Logic**
- Fuzzifikasi & Defuzzifikasi
- Metode inferensi:
  - Mamdani
  - Sugeno
  - Tsukamoto
- Perbandingan metode fuzzy
- Konsep **ANFIS** dan hybrid learning
- Implementasi fuzzy menggunakan **scikit-fuzzy**
- Visualisasi fungsi keanggotaan dan output

## 🛠️ Teknologi & Library

- Python 3.x
- NumPy
- Matplotlib
- scikit-fuzzy
- ipywidgets (untuk visualisasi interaktif)

## 📦 Instalasi Library

Pastikan library berikut sudah terpasang:

```bash
!pip install scikit-fuzzy
