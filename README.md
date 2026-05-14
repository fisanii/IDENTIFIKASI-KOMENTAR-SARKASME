# IDENTIFIKASI-KOMENTAR-SARKASME

## A. Raw Data
Data komentar didapat dengan cara scraping video yang membahas kasus perselingkuhan pada platform youtube dan tiktok. Masing-masing video diambil 1000 komentar yang selanjutnya dilakukan integrasi, total keseluruhannya sebanya 1.947 baris dan 24 kolom.

## B. library
library yang digunakan yaitu pandas, numpy, re, sklearn, gensim (Word2Vec, FastText), googleapiclient, apify_client, emoji

## C. Metode
Klasifikasi komentar saras (1) dan non-sarkas (0) menerapkan tiga algoritma machine learning, yaitu Logistic Regression (LR), Support Vector Machine (SVM), dan Random Forest (RF). Masing-masing algoritma diuji menggunakan tiga teknik representasi teks, yaitu TF-IDF, Word2Vec, dan FastText.   

