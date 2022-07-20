

# Description

This notebook provides an end-to-end demonstration of Marketing Series : Customer Lifetime Value prediction using machine learning. The scope of topics discussed in this notebook includes data analysis & machine learning (supervised Regression, feature selection, hyperparameter tuning, etc.)

This notebook also serves as a part of graduation requirement from Job Connector Data Science program by Purwadhika.
****

# Problem Statement

Sebuah perusahaan Asuransi Kendaraan di AS ingin meningkatkan revenue. Ada banyak faktor yang dapat memengaruhi kesuksesan sebuah perusahaan Asuransi. Pelanggan atau customer adalah salah satu faktor utama yang menentukan kesuksesaan perusahaan. Namun mereka menghadapi masalah dalam marketingnya. Mereka ingin mempertahankan pelanggannya dan juga menarik pelanggan baru. 

Perusahaan sudah melakukan evaluasi, menawarkan perpanjangan polis dan mendapatkan respon dari customer. Namun itu belum cukup untuk menaikkan revenue perusahaan. Maka dari itu, mereka mempertimbangkan CLV (Customer Lifetime Value) sebagai parameter untuk tujuan ini.

CLV berarti nilai umur pelanggan. Apa yang dimaksud dengan umur pelanggan di sini bukanlah umur pelanggan dilihat dari tahun kelahirannya, melainkan dari rentang waktu ia menggunakan produk asuransi kendaraan tersebut. Lebih jelas lagi, CLV adalah sebuah metrik untuk memperkirakan total nilai pelanggan terhadap sebuah perusahaan asuransi dalam jangka waktu tertentu (mengikuti durasi hubungan bisnis keduanya). Secara sederhana, CLV adalah prediksi atas nilai total pendapatan yang bisa didapatkan dari pelanggan tersebut.
Penerapan strategi atau treatment terdapat setiap pelanggan dapat berbeda- beda. Apabila dilakukan treatment yang sama ke seluruh pelanggan akan memakan waktu dan sumber daya yang lebih, terlebih lagi treatment yang tidak tepat sasaran dapat menyebabkan berkurangnya keuntungan hingga mengalami kerugian bagi perusahaan.

  Sebagai contoh, pelanggan baru membutuhkan promosi dan iklan dimana salah satunya berupa potongan harga atau pengenalan jasa/ asuransi jenis baru, sedangkan untuk pelanggan lama, salah satu treatmentnya adalah dengan memberikan reward kepada mereka sehingga pelanggan tersebut tidak akan beralih ke kompetitor. 
  Secara umum, customer lifetime value ini akan membantu perusahaan untuk : 
  1. Mempertahankan loyal customer dan akuisisi pelanggan
  2. Strategi marketing yang akan diterapkan terhadap customer berdasarkan CLV


Dalam masalah yang melibatkan banyak variabel ini, dapat menjadi tantangan untuk memutuskan feature mana yang harus dimasukkan ke dalam model. Beberapa pendekatan yang digunakan dalam model ini diharapkan dapat menggambarkan hubungan antara CLV sebagai target variable dan feature yang telah diberikan di dalam data perusahaan. Kemudian, dalam melakukan prediksi terhadap CLV kita dapat gunakan dengan mengajukan pertanyaan, diantaranya:

1. Bagaimana memprediksi CLV, sehingga dapat meningkatkan revenue perusahaan?
2. Fitur apa saja yang paling berpengaruh terhadap CLV, sehingga perusahaan dapat mengakuisisi pelanggan secara efektif?

****

# Dataset Information

Source : https://www.kaggle.com/datasets/arashnic/marketing-seris-customer-lifetime-value?select=squark_automotive_CLV_training_data.csv


| Attribute | Data Type, Length | Description |
| --- | --- | --- |
| Customer | Text | ID Customer |
| State | Text | Region |
| Customer Lifetime Value | Float | Customer Lifetime Value (Target) |
| Response | Text | Menanggapi panggilan pemasaran |
| Coverage | Text | Jenis Pertanggungan Asuransi Kendaraan |
| Education | Text | Pendidikan |
| Effective To Date | Text | Tanggal asuransi expired |
| Employment Status | Text | Status Pekerjaan |
| Gender | Text | Female/Male |
| Income | Float | Pendapatan Customer (Dollar) |
| Location Code | Text | Wilayah Geografis tempat tinggal |
| Marital Status | Text | Status Pernikahan |
| Monthly Premium Auto | Float | Tagihan perbulan |
| Months Since Last Claim | Float | Jumlah Bulan Sejak klaim terakhir |
| Months Since Policy Inception | Float | Jumlah bulan sejak customer memulai polis asuransi  |
| Number of Open Complaints | Float | Jumlah komplain yang masih berjalan |
| Number of Policies | Float | Jumlah Polis yang dimiliki pelanggan saat ini |
| Policy Type | Text | Tipe perjanjian asuransi |
| Policy | Text | Perjanjian asuransi |
| Renew Offer Type | Text | Penawaran untuk perbarui polis yang sudah/akan habis |
| Sales Channel | Text | cara atau media yang ditempuh untuk menjual produk |
| Total Claim Amount | Float | Jumlah kumulatif klaim sejak awal polis |
| Vehicle Class | Text | Klasifikasi Tipe Kendaraan |
| Vehicle Size | Text | Ukuran kendaraan |
****

# Content :

1. Business Problem Understanding
2. Data Understanding
3. Explanatory Data Analysis 
4. Preprocessing
5. Modeling & Analysis
6. Conclusion and Recomendation
****
# How To Use

To get the notebook, simply download or clone this repository. From there, you can open it up in a text editor.
****
