# MLT Proyek Pertama | Medical Insurance Premium Prediction

###### Disusun oleh : Niko Febrianur

Ini adalah proyek pertama predictive analytics untuk memenuhi submission Dicoding Kelas Machine Learning Terapan. 

Proyek ini membangun model machine learning yang dapat memprediksi biaya pertanggungan medis tahunan.

## Domain Proyek

### Latar Belakang

Proyek "Medical Insurance Premium Prediction" bertujuan untuk mengembangkan model analisis prediktif yang memperkirakan premi asuransi kesehatan berdasarkan faktor-faktor seperti usia, riwayat penyakit kronis, riwayat keluarga terkait kanker, operasi besar yang pernah dijalani, serta informasi fisik seperti tinggi dan berat badan, serta parameter lainnya. 

Tujuannya adalah membantu perusahaan asuransi menentukan premi yang akurat dan berdasarkan risiko individual, serta memberikan perkiraan premi yang lebih adil dan akurat bagi calon pemegang polis.

  Referensi: 
  - [Increasing Health Insurance Costs and the Decline in Insurance Coverage](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1361195/) 
  - [The Effects of Premiums and Cost Sharing on Low-Income Populations: Updated Review of Research Findings](https://www.kff.org/medicaid/issue-brief/the-effects-of-premiums-and-cost-sharing-on-low-income-populations-updated-review-of-research-findings/)
  - [Factors Associated With Coverage of Health Insurance Among Women in Malawi](https://www.frontiersin.org/articles/10.3389/frhs.2022.780550/full)

## Business Understanding

Proyek ini dibangun untuk perusahaan asuransi kesehatan dengan karakteristik bisnis sebagai berikut:

1. Perusahaan Asuransi Kesehatan yang Berorientasi pada Analisis Data: Perusahaan ini memiliki kepentingan dan komitmen dalam mengoptimalkan penggunaan data untuk meningkatkan keputusan bisnis. Mereka mengakui nilai analisis prediktif dan machine learning dalam menentukan premi asuransi kesehatan yang akurat dan berdasarkan risiko individual.

2. Perusahaan dengan Basis Data Pelanggan yang Kaya: Perusahaan ini memiliki akses dan kepemilikan data pelanggan yang lengkap dan kaya akan informasi. Data tersebut mencakup variabel seperti usia, riwayat medis, operasi sebelumnya, alergi, riwayat penyakit keluarga, serta data fisik seperti tinggi dan berat badan. Data pelanggan yang kaya ini akan menjadi sumber informasi yang berharga dalam mengembangkan model prediktif.

3. Perusahaan yang Berfokus pada Keunggulan Kompetitif: Perusahaan ini mengutamakan keunggulan kompetitif di pasar asuransi kesehatan. Mereka ingin memanfaatkan teknik analisis prediktif dan machine learning untuk meningkatkan proses penetapan premi, memberikan perkiraan premi yang lebih akurat, serta menawarkan produk asuransi yang lebih menarik dan kompetitif bagi calon pemegang polis.

Dengan memahami karakteristik bisnis perusahaan asuransi kesehatan ini, proyek ini dapat dirancang dan disesuaikan untuk memenuhi kebutuhan dan tujuan bisnis yang spesifik.

### Problem Statements

1. Kurangnya akurasi dalam menentukan premi asuransi kesehatan: Perusahaan asuransi menghadapi tantangan dalam menentukan premi yang akurat dan adil bagi calon pemegang polis. Hal ini disebabkan oleh keterbatasan dalam memahami faktor-faktor yang mempengaruhi besaran premi. Dalam proyek ini, kami akan mengatasi masalah ini dengan mengembangkan model analisis prediktif yang dapat memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi.

2. Kurangnya transparansi dalam penetapan premi: Calon pemegang polis seringkali merasa bahwa penetapan premi asuransi kesehatan dilakukan secara tidak adil atau tidak transparan. Mereka tidak memahami faktor-faktor apa yang menjadi dasar penentuan premi. Dalam proyek ini, kami akan mencoba meningkatkan transparansi dengan mengidentifikasi faktor-faktor yang paling signifikan dalam menentukan premi asuransi kesehatan, sehingga calon pemegang polis dapat memahami alasan di balik besaran premi yang mereka terima.

3. Risiko keuangan bagi perusahaan asuransi: Penentuan premi yang tidak akurat dapat menyebabkan risiko keuangan bagi perusahaan asuransi. Jika premi yang ditetapkan terlalu rendah, perusahaan dapat menghadapi kerugian finansial jika terjadi klaim yang tinggi. Di sisi lain, premi yang terlalu tinggi dapat mengurangi daya tarik produk asuransi. Dalam proyek ini, kami akan membantu mengurangi risiko keuangan dengan memperkirakan premi yang lebih akurat berdasarkan faktor-faktor risiko yang relevan.

Dengan mengatasi masalah-masalah ini, proyek "Medical Insurance Premium Prediction" bertujuan untuk meningkatkan akurasi, transparansi, dan efisiensi dalam penetapan premi asuransi kesehatan, memberikan manfaat bagi perusahaan asuransi dan calon pemegang polis.

### Goals

1. Mengembangkan model analisis prediktif: Tujuan utama proyek ini adalah mengembangkan model analisis prediktif yang dapat memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi. Dengan melakukan analisis data yang komprehensif dan menggunakan teknik machine learning, tujuannya adalah menciptakan model yang dapat memberikan perkiraan premi yang lebih tepat berdasarkan faktor-faktor risiko yang relevan.

2. Meningkatkan transparansi: Proyek ini bertujuan untuk meningkatkan transparansi dalam penetapan premi asuransi kesehatan. Dengan mengidentifikasi faktor-faktor yang paling signifikan dalam menentukan premi, tujuannya adalah memberikan pemahaman yang lebih baik kepada calon pemegang polis mengenai alasan di balik besaran premi yang mereka terima. Hal ini akan membantu membangun kepercayaan dan kepuasan calon pemegang polis terhadap perusahaan asuransi.

3. Mengurangi risiko keuangan: Salah satu tujuan proyek ini adalah membantu perusahaan asuransi mengurangi risiko keuangan yang terkait dengan penetapan premi yang tidak akurat. Dengan memperkirakan premi dengan lebih akurat berdasarkan faktor-faktor risiko yang relevan, perusahaan asuransi dapat mengoptimalkan pengelolaan risiko keuangan mereka, menghindari kerugian yang tidak diharapkan, dan menjaga stabilitas keuangan perusahaan.

4. Meningkatkan keadilan premi: Proyek ini bertujuan untuk memberikan perkiraan premi yang lebih adil dan akurat bagi calon pemegang polis. Dengan mempertimbangkan faktor-faktor risiko yang relevan secara lebih holistik, tujuannya adalah mengurangi ketidaksetaraan dalam penetapan premi dan memberikan keadilan dalam penentuan premi asuransi kesehatan. Hal ini akan memberikan manfaat bagi calon pemegang polis dengan memastikan bahwa premi yang mereka bayar sejalan dengan risiko yang mereka tanggung.

## Solution statements
Berdasarkan goals di atas maka solusi yang diberikan ialah:
- Mencari pengetahuan yang ada pada data dengan menerapkan proses EDA
- Model machine learning akan menggunakan algoritma SVR yang ada pada referensi dan menggunakan library pycaret untuk menentukan algoritma yang lain.
- Evaluasi pembanding model akan menggunakan MSE atau Mean Squared Error.

## Data Understanding
Dataset yang digunakan dalam proyek ini merupakan data parameter terkait kesehatan yang diberikan hampir oleh 1000 konsumen secara sukarela.

Dataset dapat diunduh di: [Medical Insurance Premium Prediction](https://www.kaggle.com/datasets/tejashvi14/medical-insurance-premium-prediction).

### Sample data
| Age | Diabetes | BloodPressureProblems | AnyTransplants | AnyChronicDiseases | Height | Weight | KnownAllergies | HistoryOfCancerInFamily | NumberOfMajorSurgeries | PremiumPrice |
|-----|----------|-----------------------|----------------|--------------------|--------|--------|----------------|-------------------------|-----------------------|--------------|
| count | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 | 986.000000 |
| mean | 41.745436 | 0.419878 | 0.468560 | 0.055781 | 0.180527 | 168.182556 | 76.950304 | 0.215010 | 0.117647 | 0.667343 | 24336.713996 |
| std | 13.963371 | 0.493789 | 0.499264 | 0.229615 | 0.384821 | 10.098155 | 14.265096 | 0.411038 | 0.322353 | 0.749205 | 6248.184382 |
| min | 18.000000 | 0.000000 | 0.000000 | 0.000000 | 0.000000 | 145.000000 | 51.000000 | 0.000000 | 0.000000 | 0.000000 | 15000.000000 |
| 25% | 30.000000 | 0.000000 | 0.000000 | 0.000000 | 0.000000 | 161.000000 | 67.000000 | 0.000000 | 0.000000 | 0.000000 | 21000.000000 |
| 50% | 42.000000 | 0.000000 | 0.000000 | 0.000000 | 0.000000 | 168.000000 | 75.000000 | 0.000000 | 0.000000 | 1.000000 | 23000.000000 |
| 75% | 53.000000 | 1.000000 | 1.000000 | 0.000000 | 0.000000 | 176.000000 | 87.000000 | 0.000000 | 0.000000 | 1.000000 | 28000.000000 |
| max | 66.000000 | 1.000000 | 1.000000 | 1.000000 | 1.000000 | 188.000000 | 132.000000 | 1.000000 | 1.000000 | 3.000000 | 40000.000000 |

Berikut informasi pada dataset :

- Dataset memiliki format CSV (Comma-Seperated Values).
- Dataset memiliki 986 sample dengan 11 fitur.
- Dataset memiliki 11 fitur bertipe int64.
- Tidak ada missing value dalam dataset.

### Variabel-variabel pada Medical Insurance Premium Prediction dataset adalah sebagai berikut:
- Age : merupakan rentang umur dari pasien tersebut
- Diabetes : apakah pasien tersebut memiliki kadar gula darah abnormal atau tidak
- BloodPressureProblems: apakah pasien tersebut memiliki tingkat tekanan darah abnormal
- AnyTransplants: pernah melakukan transplantasi organ utama apapun
- AnyChronicDiseases: apakah pasien menderita penyakit kronis seperti asthama, dll
- Height: rentang tinggi badan pasien
- Weight: rentang berat badan pasien
- KnownAllergies: apakah pasien memiliki alergi yang diketahui
- HistoryOfCancerInFamily: apakah ada relatif darah dari pasien yang mengidap bentuk kanker apa pun
- NumberOfMajorSurgeries: jumlah operasi besar yang dijalani pasien tersebut
- PremiumPrice: harga premium tahunan

### Pendalaman Data Understanding
- Melakukan tahapan EDA seperti mendeskripsikan variabel, mencari outliers, Univariate hingga Multi-variate analysis.
- Untuk menganalisa outliers bisa menggunaka boxplot dengan memanggil fungsi .plot() pada pandas
- Mengecek data missing value dan membersihkan data missing value dengan membuat simple logic program
- Menggunakan histogram untuk melihat penyebaran data dengan library pandas fungsi .hist()
- Mencari Keterkaitan antar fitur numerik dan fitur kategori dengan correlation matrix menggunakan fungsi pandas dan visualisasi heatmap dengan seaborn

## Data Preparation
Berikut ada teknik yang digunakan dalam proses data preparation, yaitu:
 -  One Hot Encoding pada data Categorical dengan menggunakan pandas library pada fungsi pd.get_dummies(). Teknik ini dilakukan untuk mengubah variabel kategorikal menjadi representasi numerik yang nantinya dapat digunakan dalam model machine learning.
 -  Membagi dataset menjadi data training dan data testing menggunakan library sklearn dengan fungsi train_set_split() dengan perbandingan 80:20 yaitu data training sebesar 788 dan data testing sebesar 198. Teknik ini dilakukan agar nantinya model dapat dievaluasi dan untuk mendeteksi apakah terjadi overfitting dalam model. 

## Modeling
Dalam proses modeling, proyek ini akan menggunakan algoritma SVR dan algoritma Huber Regressor berdasarkan hasil dari data library pycaret.

### Tahapan yang dilakukan
Berikut adalah urutan tahapan yang dilakukan dalam proses modeling:
 - Melatih model dengan data training dengan menggunakan algoritma Huber Regressor dan SVR
 - Dalam tahap training, pengujian model dilakukan dengan menggunakan parameter default bawaan library
 - Melakukan pengujian dengan data training
 - Melakukan pengujian dengan data testing
 - Pengukuran menggunakan metriks MSE,MAE,RMSE dan R2 dengan menggunakan lirbary sklearn. 
 - Melihat hasil performa model antara hasil data training dan data testing
 - Meningkatkan performa model dengan menerapkan grid search atau hyper parameter pada model
 - Menggunakan hyper param pada Huber Regressor yaitu param_grid = { 'epsilon': [1.0, 1.5, 2.0],'alpha': [0.0001, 0.001, 0.01], 'max_iter': [100, 200, 300]}
 - Menggunakan hyper param pada SVR yaitu param_grid = {'kernel': ['linear', 'rbf'],'C': [0.1, 1, 10],'epsilon': [0.1, 0.2, 0.3]}
 - Setelah pengujian hyperparam, Huber Regressor mendapatkan param terbaik yaitu: {'alpha': 0.01, 'epsilon': 2.0, 'max_iter': 100}
 - Setelah pengujian hyperparam, SVR mendapatkan param terbaik yaitu: {'C': 1, 'epsilon': 0.1, 'kernel': 'linear'

### Hasil running model
 - Huber_MSE: Rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual pada data training adalah sekitar 18,480,694.56826, sedangkan pada data testing sekitar 25,177,990.875244. Hasil ini menunjukkan bahwa model memiliki tingkat kesalahan yang sedikit lebih tinggi pada data testing dibandingkan dengan data training.
 - SVR_MSE: Rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual pada data training adalah sekitar 40,114,366.684487, sedangkan pada data testing sekitar 42,742,505.675315. Hasil ini menunjukkan bahwa model testing memiliki tingkat kesalahan yang sedikit lebih tinggi pada data testing dibandingkan dengan data training.

Kesimpulan yang dapat diambil dari paparan di atas ialah adanya overfitting pada data training karena model cenderung memiliki tingkat kesalahan yang lebih tinggi pada data testing. 

### Kelebihan dan Kekurangan
 - Algoritma Huber Regressor memiliki keunggulan lebih tahan terhadap adanya outlier dan oleh karena itu dapat memberikan hasil yang lebih konsisten dan stabil dibandingkan dengan regresi linier biasa
 - Algoritma Huber Regressor memiliki kekurangan dalam pemilihan nilai yang tepat untuk delta dapat mempengaruhi kinerja algoritma, dan penyesuaian parameter ini sering kali memerlukan pengujian dan penyesuaian manual. 
 - Algoritma SVR memiliki keunggulan dapat menggunakan fungsi kernel yang berbeda untuk mengubah data input menjadi ruang fitur yang lebih tinggi, memungkinkan pemodelan yang lebih fleksibel dan penanganan kasus-kasus di mana hubungan antara fitur dan target bersifat non-linear.
 - Algoritma SVR memiliki kekurangan sangat sensitif terhadap skala data input. Oleh karena itu, penting untuk melakukan normalisasi atau penskalaan data sebelum menggunakan SVR untuk menghindari bias yang tidak diinginkan dalam model.

Berdasarkan pertimbangan kelebihan dan kekurangan di atas, maka algoritma Huber Regressor dinilai lebih unggul dari SVR dan setelahnya perlu menerapkan hyperparam saat model masuk ke evaluasi.

## Evaluation
Metrik evaluasi yang digunakan dalam proyek ini ialah sebagai berikut:

### MSE
Mean Square Error (MSE) adalah salah satu metrik evaluasi yang digunakan untuk mengukur sejauh mana perbedaan antara nilai prediksi dan nilai sebenarnya dalam masalah regresi. Model evaluasi MSE menghitung rata-rata dari kuadrat selisih antara nilai prediksi dan nilai sebenarnya. Semakin kecil MSE, semakin baik model tersebut dalam melakukan prediksi yang akurat.

Berikut adalah langkah-langkah untuk menghitung MSE:

1. Mulai dengan memiliki kumpulan data yang terdiri dari pasangan nilai sebenarnya (y) dan nilai prediksi (ŷ) untuk sejumlah contoh atau sampel.

2. Hitung selisih antara nilai sebenarnya dan nilai prediksi untuk setiap contoh. Selisih ini merupakan error atau kesalahan prediksi untuk masing-masing contoh.

3. Kuadratkan setiap selisih. Ini dilakukan untuk memastikan bahwa setiap error memiliki kontribusi positif terhadap nilai MSE, tanpa mempertimbangkan apakah prediksi lebih rendah atau lebih tinggi dari nilai sebenarnya.

4. Hitung rata-rata dari kuadrat selisih. Caranya adalah dengan menjumlahkan semua kuadrat selisih dan membaginya dengan jumlah contoh.

   MSE = (Σ (y - ŷ)²) / n
   
   di mana:
   - Σ menunjukkan penjumlahan
   - y adalah nilai sebenarnya
   - ŷ adalah nilai prediksi
   - n adalah jumlah contoh atau sampel dalam dataset.

5. Setelah menghitung MSE, semakin kecil nilai MSE, semakin baik model dalam melakukan prediksi yang akurat. MSE memiliki satuan yang berbeda dengan variabel yang dievaluasi, karena hasilnya berupa kuadrat. Oleh karena itu, MSE seringkali diinterpretasikan dalam konteks yang lebih luas, atau perbandingannya dibandingkan dengan metrik evaluasi lainnya.

MSE merupakan metrik evaluasi yang umum digunakan dalam masalah regresi karena memperhitungkan perbedaan antara nilai prediksi dan nilai sebenarnya secara keseluruhan dan memberikan bobot yang lebih besar pada perbedaan yang besar. Namun, MSE juga memiliki kelemahan yaitu sensitif terhadap outlier, artinya nilai ekstrem yang sangat berbeda dapat mempengaruhi MSE secara signifikan. Oleh karena itu, terkadang metrik evaluasi alternatif seperti Mean Absolute Error (MAE) juga digunakan untuk memberikan gambaran yang lebih lengkap tentang kinerja model.

## Kesimpulan 
Berdasarkan hasil paparan di atas, proyek ini menghasilkan rangkaian kesimpulan untuk kebutuhan bisnis sebagai berikut: 
 - Pasien yang mempunyai riwayat pernah melakukan transplantasi, melakukan operasi besar, dan mempunyai penyakit kronis lebih tertarik untuk membayar premi asuransi karena sesuai dengan resiko yang mereka tanggung. 
 - Pasien yang memiliki diabetes, riwayat kanker di keluarga, alergi, dan permasalahan tekanan darah tidak terlalu tertarik membayar premi asuransi.
