# DeteksiMI
Deteksi Myocardial Infarction / Serangan jantung menggunakan Ensemble Learning berbasis signal Phonocardiogram. 

## Dataset
Dataset didapatkan dari proses rekam jantung yang dilakukan di RS Hasan Sadikin, Bandung
Dataset dapat diakses pada : 

Normal : https://drive.google.com/drive/folders/17YDAeE61PoCP2f5mGX7T2ElbwoAX7gYt?usp=sharing
MI : https://drive.google.com/drive/folders/1TUCscgChKImNjRBZYeOO6eHKJSLCz7G-?usp=share_link

# Metode

## Preprocessing

Proses Preprocessing menggunakan library noisereduce dari PyPI.

## Feature Extraction
Proses ekstraksi ciri menggunakan 3 metode yaitu MFCC, DWT dan Energy Entropy

## Klasifikasi
Klasifikasi menggunakan 3 metode ensemble, yaitu Bagging, Stacking dan Boosting
