# Diabetes-Risk-Classification-Model

## Repository Outline
---
1. README.md - Penjelasan gambaran umum project
2. Classification_Modelling.ipynb - Notebook yang berisi percobaan machine learning mulai data loading, sampai saving model, dan ada penjelasan hasil percobaan yang dilakukan.
3. Model_Inference.ipynb - Notebook berisi percobaan data inference dari model machine learning yang telah dibuat.
4. best_xgb_pipeline.pkl - file pipeline dari hasil percobaan modeling machine learning.
5. diabetes_binary_health_indicators_BRFSS2015.csv - dataset yang digunakan dalam project kali ini.
---

## Problem Background
---
`Penyakit diabetes merupakan salah satu penyakit kronis yang jumlah penderitanya terus meningkat di Indonesia dan dapat menimbulkan komplikasi serius jika tidak ditangani dengan baik. Untuk membantu masyarakat dalam mengenali potensi risiko diabetes sejak dini, proyek ini bertujuan mengembangkan model machine learning yang mampu memprediksi apakah seseorang berisiko terkena diabetes berdasarkan data gaya hidup, kondisi kesehatan, dan status demografis. Model ini ditujukan untuk masyarakat umum yang ingin melakukan pengecekan mandiri terhadap risiko diabetes tanpa harus langsung ke fasilitas medis. Keberhasilan model akan diukur melalui metrik seperti akurasi, precision, recall, dan F1-score. Proyek ini akan menggunakan dataset BRFSS dan algoritma seperti KNN, SVM, Decision Tree, Random Forest, dan metode Boosting. Seluruh tahapan pengembangan direncanakan selesai pada tanggal 23 April 2024, mencakup proses eksplorasi data hingga evaluasi model dan deployment model.`
---

## Project Output
---
`Output project kali ini adalah notebook yang berisikan proses percobaan untuk menemukan model machine learning yang akan digunakan, file pipeline, file notebook percobaan data inference `
---

## Data
---
`Data yang digunakan adalah dataset diabetes health indicators dari kaggle by Alex Teboul. Data memilki 253680 entri, 22 kolom numerik yang bersifat kategorikal dan ada yang kontinu, tidak terdapat missing value pada dataset, tapi terdapat data duplikat sebanyak 24206 `
---

## Method
---
`Metode yang digunakan pada project machine learning ini adalah model supervised learning, untuk algoritma yang digunakan adalah KNN, Decision Tree, Randomforest, dan XGBoost. Keempat algoritma akan dibandingkan hasil ujinya setelah training untuk diambil salah satu`
---

## Stacks
---
`Bahasa Pemrograman yang digunakan pada project ini adalha Python, dengan tools yang digunakan adalah Jupyternotebook, dan library python yang digunakan adalah pandas, numpy, xgboost, time, matplotlib, seaborn, scipy, feature_engine, sklearn, imblearn, dan joblib`
---