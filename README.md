# 🎮 Clustering Perilaku Pemain Game Online

> **Project Akhir — Konsep Data Warehouse & Mining**  
> Institut Teknologi & Bisnis Bina Sarana Global | Tahun Akademik 2025–2026

---

## 👤 Identitas

| | |
|---|---|
| **Nama** | Louis Hasashi Halim |
| **Email** | louishasashi@gmail.com |
| **Program Studi** | Sistem Informasi |
| **Institusi** | Institut Teknologi & Bisnis Bina Sarana Global |
| **Dosen** | Agus Rifaldi, S.Kom |

---

## 🔗 Links

| Platform | Link |
|----------|------|
| 🌐 Google Sites (Portofolio) | https://sites.google.com/view/data-science-portofolio/halaman-muka |
| 🎥 Video Presentasi YouTube | [*(update setelah upload video)*](https://youtu.be/EZL2kaHkfug?si=I2CtxrHhKRwX0IYp) |
| 🐙 GitHub | https://github.com/louishasashi-dev/kdwm_uas |

---

## 📌 Deskripsi Project

Project ini menerapkan metode **K-Means Clustering** untuk mengelompokkan pemain game online berdasarkan pola perilaku bermain mereka. Analisis menggunakan framework **CRISP-DM** dan dataset publik dari Kaggle.

**Tujuan:** Mengidentifikasi segmen pemain yang memiliki karakteristik perilaku berbeda, sehingga dapat memberikan insight untuk strategi engagement yang lebih efektif.

---

## 📊 Dataset

| Info | Detail |
|------|--------|
| **Nama Dataset** | Online Gaming Behavior Dataset |
| **Sumber** | [Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset) |
| **Jumlah Data** | 40.034 baris |
| **Jumlah Fitur** | 13 kolom |
| **Fitur Clustering** | PlayTimeHours, SessionsPerWeek, AvgSessionDurationMinutes, PlayerLevel, AchievementsUnlocked |

---

## 🔬 Metode

- **Algoritma:** K-Means Clustering
- **Penentuan K:** Elbow Method + Silhouette Score
- **K Optimal:** 3 cluster
- **Preprocessing:** StandardScaler (normalisasi)
- **Evaluasi:** Silhouette Score, distribusi cluster
- **Visualisasi:** PCA 2D, bar chart, heatmap korelasi

---

## 📁 Struktur Repository

```
├── clustering_gaming_behavior.ipynb   # Notebook utama (CRISP-DM lengkap)
├── online_gaming_behavior_insights.csv # Dataset
├── hasil_clustering_gaming.csv        # Output hasil clustering
└── README.md
```

---

## 🏆 Hasil Clustering

| Cluster | Nama Segmen | Jumlah Pemain | Karakteristik |
|---------|-------------|---------------|---------------|
| 0 | **High-Time Casual** | ~12.773 (31.9%) | Jam bermain tinggi (~18.6 jam), level rendah (~33) |
| 1 | **Veteran Player** | ~14.871 (37.1%) | Level tinggi (~80), bermain efisien (~11.6 jam) |
| 2 | **Light Player** | ~12.390 (30.9%) | Jam bermain rendah (~5.8 jam), level rendah (~30) |

---

## 🛠️ Tech Stack

- Python 3
- Pandas, NumPy
- Scikit-learn (KMeans, StandardScaler, PCA, silhouette_score)
- Matplotlib, Seaborn
- Jupyter Notebook

---

> *Learning by building real projects.*
