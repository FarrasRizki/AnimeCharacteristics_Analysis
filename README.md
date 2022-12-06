# Anime Rating Prediction
Project by Muhammad Farras Rizki

## A. Latar Belakang
Anime adalah animasi asal Jepang yang digambar dengan tangan maupun menggunakan teknologi komputer. Judul anime pertama di dunia adalah Katsudo Shashin. Anime ini diperkirakan muncul di Jepang pada tahun 1907. Anime pertama yang mencapai kepopuleran yang luas adalah Astro Boy karya Ozamu Tezuka pada 1963. Sejak saat itu anime mulai berkembang dan banyak dikenal oleh masyarakat luas.


## B. Tentang Dataset
Dataset berisi 14578 baris dan 18 kolom. Baris dalam dataset ini merepresentasikan informasi dari suatu anime beserta ratingnya. Informasi tersebut meliputi media penayangan, jumlah episode, genre, tahun produksi, jumlah penonton hingga rating. Rating yang digunakan memiliki range nilai dari 0 hingga 5.


## C. Tujuan Project :
Memprediksi rating suatu anime menggunakan model regresi
Memberikan insight pada orang yang akan memproduksi anime, mengenai faktor apa saja yang berkontribusi pada rating suatu anime


## D. Sumber Dataframe
Source : https://www.kaggle.com/datasets/alancmathew/anime-dataset
Informasi yang ada pada dataset ini diambil dari https://www.anime-planet.com/ pada tanggal 15 Juni 2020


## E. Deskripsi Pemodelan
Tujuan dari pemodelan adalah ingin membuat model yang mampu memprediksi rating suatu anime. Model yang akan digunakan adalah jenis Regression. Target Variabel yang akan digunakan adalah kolom `rating`.

Model Machine Learning yang akan diuji antara lain:
1. Linier Regression
2. Random Forest Classification
