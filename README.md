# 🚀 AgroSmart Analytics: Global Cattle Disease & Production Intelligence

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![Stage](https://img.shields.io/badge/Stage-EDA%20%26%20Preprocessing-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.x-blue.svg)

## 📌 Project Overview
Proyek ini bertujuan untuk mengintegrasikan analitik pertanian tingkat lanjut dan kecerdasan buatan (*AI-Driven Livestock Intelligence*) untuk pemantauan kesehatan sapi perah dan optimasi produksi susu.

### 🧭 Navigation Tree
📁 AgroSmart Analytics - Case Study Setup
├── 📊 01_cattle_disease_eda_preprocessing.ipynb ← CORE ANALYSIS
└── 📋 README.md

---

## 📈 Dataset Intelligence Report
| Core Metrics | Data Categories |
| :--- | :--- |
| 📋 **Source**: Global Cattle Disease Detection Dataset | 🌡️ Physiological Sensors |
| 🔢 **Volume**: **250,000** cattle records | 🥛 Feed Management Systems |
| ✅ **Quality**: Zero Missing Values | 🌤️ Environmental Conditions |
| 📅 **Coverage**: 3 Years (2022-2024) | 💉 Vaccination Records |
| 🔧 **Features**: 40 IoT-enabled columns | 🥛 Milk Production Metrics |

---

## 💡 Key Findings & Business Insights
1. **The "Goldilocks" Balanced Dataset:** Proporsi status kesehatan sapi terbagi menjadi **55.0% Sehat** dan **45.0% Sakit**, menghilangkan kebutuhan teknik balancing data sintetik seperti SMOTE.
2. **Feed Efficiency Discovery:** Rata-rata efisiensi konversi pakan adalah **0.82 L/kg**. Identifikasi *outliers* berkinerja tinggi (hingga 8.45 L/kg) memberikan peluang optimasi pakan berbasis *clustering*.
3. **Why Multivariate Machine Learning is Needed:** Analisis bivariat (*Boxplot*) pada `Body_Temperature_C` dan `Rumination_Time_hrs` menunjukkan distribusi dan median yang hampir tumpang tindih sempurna antar sapi sehat dan sakit. Hal ini membuktikan bahwa diagnosis kesehatan ternak tidak cukup dengan 1-2 variabel tunggal, melainkan memerlukan model multivariat (*Random Forest / Ensemble*) untuk menangkap pola non-linear dari 40 sensor IoT secara simultan.

---
## 📬 Let's Connect
Jika Anda memiliki pertanyaan mengenai proyek ini, saran kolaborasi, atau peluang pekerjaan di bidang Data Science/Analitik, silakan hubungi saya melalui:

*   **LinkedIn:** [Lalu Zidane Alif Akbar](https://www.linkedin.com/in/lalu-zidane-b89395229/)
*   **WhatsApp:** [+62 857 3711 9716](https://wa.me/6285737119716)

*Saya selalu terbuka untuk diskusi mengenai data science, desain, dan pengembangan teknologi.*
