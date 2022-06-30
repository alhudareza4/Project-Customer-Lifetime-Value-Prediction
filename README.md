# **Marketing Series : Customer Lifetime Value**
****
### Created by : Eta Engineers

## Content :

1. Business Problem Understanding
2. Data Understanding
3. Explanatory Data Analysis 
4. Preprocessing
5. Modeling & Analysis
6. Conclusion and Recomendation

# **1. Business Problem Understanding**
****

**Context**

Sebuah perusahaan Asuransi Kendaraan di AS ingin meningkatkan revenue. Ada banyak faktor yang dapat memengaruhi kesuksesan sebuah perusahaan Asuransi. Pelanggan atau customer adalah salah satu faktor utama yang menentukan kesuksesaan perusahaan. Namun mereka menghadapi masalah dalam marketingnya. Mereka ingin mempertahankan pelanggannya dan juga menarik pelanggan baru. 

Perusahaan sudah melakukan evaluasi, menawarkan perpanjangan polis dan mendapatkan respon dari customer. Namun itu belum cukup untuk menaikkan revenue perusahaan. Maka dari itu, mereka mempertimbangkan CLV (Customer Lifetime Value) sebagai parameter untuk tujuan ini.

CLV berarti nilai umur pelanggan. Apa yang dimaksud dengan umur pelanggan di sini bukanlah umur pelanggan dilihat dari tahun kelahirannya, melainkan dari rentang waktu ia menggunakan produk asuransi kendaraan tersebut. Lebih jelas lagi, CLV adalah sebuah metrik untuk memperkirakan total nilai pelanggan terhadap sebuah perusahaan asuransi dalam jangka waktu tertentu (mengikuti durasi hubungan bisnis keduanya). Secara sederhana, CLV adalah prediksi atas nilai total pendapatan yang bisa didapatkan dari pelanggan tersebut.

**Problem Statement :** <br>

  Penerapan strategi atau treatment terdapat setiap pelanggan dapat berbeda- beda. Apabila dilakukan treatment yang sama ke seluruh pelanggan akan memakan waktu dan sumber daya yang lebih, terlebih lagi treatment yang tidak tepat sasaran dapat menyebabkan berkurangnya keuntungan hingga mengalami kerugian bagi perusahaan.

  Sebagai contoh, pelanggan baru membutuhkan promosi dan iklan dimana salah satunya berupa potongan harga atau pengenalan jasa/ asuransi jenis baru, sedangkan untuk pelanggan lama, salah satu treatmentnya adalah dengan memberikan reward kepada mereka sehingga pelanggan tersebut tidak akan beralih ke kompetitor. 
  Secara umum, customer lifetime value ini akan membantu perusahaan untuk : 
  1. Mempertahankan loyal customer dan akuisisi pelanggan
  2. Strategi marketing yang akan diterapkan terhadap customer berdasarkan CLV


Dalam masalah yang melibatkan banyak variabel ini, dapat menjadi tantangan untuk memutuskan feature mana yang harus dimasukkan ke dalam model. Beberapa pendekatan yang digunakan dalam model ini diharapkan dapat menggambarkan hubungan antara CLV sebagai target variable dan feature yang telah diberikan di dalam data perusahaan. Kemudian, dalam melakukan prediksi terhadap CLV kita dapat gunakan dengan mengajukan pertanyaan, diantaranya:

1. Bagaimana memprediksi CLV, sehingga dapat meningkatkan revenue perusahaan?
2. Fitur apa saja yang paling berpengaruh terhadap CLV, sehingga perusahaan dapat mengakuisisi pelanggan secara efektif?

  
 **Goals :** <br>

  Berdasarkan permasalahan diatas, dapat kita simpulkan bahwa tujuan kita adalah untuk memahami hubungan antara variabel target (Y) dan variabel prediktor (X) serta menjelaskannya menggunakan data yang sesuai dengan regresi. Dengan demikian, perusahaan dapat memiliki kemampuan dalam memprediksi Customer Lifetime Value (CLV) dengan mengoptimalkan variable yang berpengaruh secara signifikan.
  
  **Analytic Approach :** <br>

  Kemudian, dalam mencapai tujuan tersebut kita akan melakukan analisa data yang bertujuan untuk menemukan pola dari variable- variable yang ada. Selain itu, analisa yang dilakukan untuk membangun model regresi yang terpercaya sehingga dapat dijadikan 'tools' bagi perusahaan dalam memprediksi Customer Lifetime Value
  
  **Metric Evaluation**

Evaluasi metrik yang akan dilakukan adalah R-square, dimana R-square adalah koefisien determinasi yang menjelaskan seberapa jauh data dependen dapat dijelaskan oleh data independen. R square bernilai antar 0 – 1 dengan ketentuan semakin mendekati angka satu berarti semakin baik.

Alasan dalam Metric Evaluation menggunakan R-square adalah : 

**Dari sisi Data :** <br>
    1. Dataset yang tersedia memiliki rentang nominal yang besar <br>
    2. Berdasarkan jurnal penelitian yang diterbitkan oleh National Library of Medicine, menunjukkan R-square lebih informatif dan tidak bias daripada SMAPE, dan tidak memiliki keterbatasan interpretasi MSE, RMSE, MAE dan MAPE.

**Dari sisi Bisnis :** <br>
    1. Salah satu Goals dari Analisa ini adalah "memahami hubungan antara variabel target (Y) dan variabel prediktor (X)", dan R-square adalah metric evaluation yang paling tepat untuk merepresentasikan dari Goals tersebut.

https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8279135/

