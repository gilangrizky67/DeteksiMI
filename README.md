# DeteksiMI
Deteksi Myocardial Infarction / Serangan jantung menggunakan Ensemble Learning berbasis signal Phonocardiogram. 

## Dataset
Dataset didapatkan dari proses rekam jantung yang dilakukan di RS Hasan Sadikin, Bandung
Dataset dapat diakses pada : 

https://drive.google.com/drive/folders/1T_baxFCQow1yIkJl2zKAA1TVI1d_grq4?usp=share_link

# Metode

## Preprocessing

Proses Preprocessing menggunakan library noisereduce dari PyPI.

## Feature Extraction
Proses ekstraksi ciri menggunakan 3 metode yaitu MFCC, DWT dan Energy Entropy

## Klasifikasi
Klasifikasi menggunakan 3 metode ensemble, yaitu Bagging, Stacking dan Boosting
