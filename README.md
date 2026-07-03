# Klasifikasi Opini Publik di Media Sosial X terhadap Program Makan Bergizi Gratis (MBG) dengan Implementasi Algoritma Support Vector Machine (SVM)

## Deskripsi

Repository ini merupakan dokumentasi penelitian skripsi yang berjudul:

**"Klasifikasi Opini Publik di Media Sosial X terhadap Program Makan Bergizi Gratis (MBG) dengan Implementasi Algoritma Support Vector Machine (SVM)"**

Penelitian ini bertujuan mengklasifikasikan opini masyarakat Indonesia terhadap Program Makan Bergizi Gratis (MBG) berdasarkan data unggahan pada media sosial X (Twitter). Proses klasifikasi dilakukan menggunakan pendekatan **Text Mining** dengan algoritma **Support Vector Machine (SVM)** serta mengikuti tahapan **CRISP-DM (Cross Industry Standard Process for Data Mining)**. 

---

## Tujuan Penelitian

Penelitian ini bertujuan untuk:

1. Membangun dataset hasil text mining mengenai opini publik terhadap Program Makan Bergizi Gratis (MBG) pada media sosial X.
2. Mengimplementasikan algoritma Support Vector Machine (SVM) untuk mengklasifikasikan opini masyarakat ke dalam tiga kelas sentimen, yaitu **positif**, **negatif**, dan **netral**. :contentReference[oaicite:2]{index=2}

---

## Metodologi Penelitian

Penelitian menggunakan metode **CRISP-DM**, yang terdiri dari tahapan:

- Business Understanding
- Data Understanding
- Data Preparation
- Modeling
- Evaluation
- Deployment :contentReference[oaicite:3]{index=3}

## Dataset

Dataset diperoleh melalui proses scraping pada media sosial X menggunakan **Tweet Harvest** berbasis **Node.js** yang dijalankan melalui Google Colab.

Kriteria pengambilan data:

- Platform : Media Sosial X (Twitter)
- Bahasa : Indonesia
- Periode : November 2025 – Januari 2026
- Jumlah data hasil scraping : **7.462 tweet**
- Jumlah data setelah preprocessing : **7.227 tweet** 

---

## Distribusi Sentimen

Hasil pelabelan menggunakan **InSet Lexicon** menghasilkan:

| Sentimen | Jumlah |
|----------|-------:|
| Negatif | 3.299 |
| Positif | 2.926 |
| Netral | 1.002 |
| **Total** | **7.227** |

:contentReference[oaicite:6]{index=6}

---

## Struktur Repository

```
Klasifikasi-Opini-MBG-SVM
│
├── DATASET/
│   ├── DATASET_MBG_FINAL.csv
│   ├── Preprocessing_Data_MBG_Final.csv
│   └── Data_MBG_Berlabel_Final.csv
├── NOTEBOOK/
│   ├── PROSES_SCRAPPING_DATA.ipynb
│   ├── PRE_PROCESSING_DATA.ipynb
│   └── Pelabelan_Depl.ipynb
│
└── README.md
```

---

## Teknologi yang Digunakan

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Sastrawi
- Matplotlib
- WordCloud
- Tweet Harvest
- Node.js

---

## Metode Evaluasi

Model dievaluasi menggunakan:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

:contentReference[oaicite:7]{index=7}

---

## Penulis

**Reska Astisia**

Program Studi Sistem Informasi

Universitas Bengkulu

---

## Lisensi

Repository ini dibuat sebagai dokumentasi penelitian skripsi. Seluruh data, kode, dan dokumentasi digunakan untuk kepentingan akademik dengan tetap memperhatikan etika penggunaan data.
