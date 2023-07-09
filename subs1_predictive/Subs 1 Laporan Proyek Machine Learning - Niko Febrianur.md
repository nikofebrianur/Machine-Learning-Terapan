# MLT Proyek Pertama | Medical Insurance Premium Prediction

###### Disusun oleh : Niko Febrianur

Ini adalah proyek pertama analisis prediktif untuk memenuhi submission Dicoding Kelas Machine Learning Terapan. 

Proyek ini membangun model *machine learning* yang dapat memprediksi biaya pertanggungan medis tahunan.

## 1. Project Domain

### Latar Belakang

Domain proyek "Medical Insurance Premium Prediction" adalah industri asuransi kesehatan. Asuransi kesehatan adalah sektor yang penting dalam industri asuransi, yang melibatkan perlindungan finansial terhadap risiko kesehatan bagi individu dan keluarga mereka. 

Dalam domain ini, perusahaan asuransi menyediakan layanan perlindungan kesehatan dengan mengenakan premi kepada pemegang polis.

Relevansi proyek ini dengan industri asuransi kesehatan adalah sebagai berikut:

1. Penentuan Premi yang Akurat: Model prediktif yang dikembangkan dalam proyek ini bertujuan untuk membantu perusahaan asuransi menentukan premi asuransi kesehatan yang akurat. Dengan mempertimbangkan faktor-faktor risiko yang relevan, seperti usia, riwayat penyakit kronis, riwayat keluarga terkait kanker, operasi besar yang pernah dijalani, serta informasi fisik seperti tinggi dan berat badan, model ini dapat memberikan estimasi premi yang lebih tepat berdasarkan risiko individual yang dihadapi oleh calon pemegang polis.

2. Keadilan dalam Penentuan Premi: Model prediktif ini juga bertujuan untuk memberikan perkiraan premi yang lebih adil dan akurat bagi calon pemegang polis. Dengan mempertimbangkan faktor-faktor risiko yang relevan secara komprehensif, model ini dapat mengurangi ketidaksetaraan dalam penetapan premi. Ini berarti bahwa premi yang dibayarkan oleh calon pemegang polis akan lebih sesuai dengan risiko kesehatan yang mereka tanggung, memberikan keadilan dalam penentuan premi asuransi kesehatan.

Manfaat bagi Perusahaan Asuransi:
- Penentuan Premi yang Akurat: Dengan menggunakan model prediktif ini, perusahaan asuransi dapat menentukan premi asuransi kesehatan yang lebih akurat berdasarkan risiko individual calon pemegang polis. Hal ini dapat membantu perusahaan mengelola risiko keuangan dan mencegah kerugian yang tidak diharapkan.
- Peningkatan Efisiensi: Dengan memanfaatkan teknologi dan analisis data dalam menentukan premi, perusahaan asuransi dapat meningkatkan efisiensi dalam proses penentuan premi, menghemat waktu dan sumber daya yang dibutuhkan.

Manfaat bagi Calon Pemegang Polis:
- Premi yang Adil: Dengan menggunakan model prediktif yang mempertimbangkan faktor-faktor risiko secara komprehensif, calon pemegang polis akan menerima perkiraan premi yang lebih adil, yang sejalan dengan risiko kesehatan yang mereka tanggung. Hal ini dapat membantu mereka memahami dan menerima besaran premi yang mereka bayar.
- Perlindungan Finansial yang Optimal: Dengan premi yang didasarkan pada risiko individual, calon pemegang polis akan mendapatkan perlindungan finansial yang sesuai dengan kebutuhan dan risiko kesehatan mereka. Ini memberikan mereka kepastian dan keamanan dalam menghadapi risiko kesehatan yang mungkin mereka alami.

Secara keseluruhan, model analisis prediktif dalam proyek "Medical Insurance Premium Prediction" dapat memberikan manfaat yang signifikan bagi perusahaan asuransi dan calon pemegang polis. 

Dengan menggunakan model ini, perusahaan asuransi dapat mengoptimalkan penentuan premi dan mengelola risiko keuangan mereka, sementara calon pemegang polis akan mendapatkan perkiraan premi yang lebih adil dan akurat sesuai dengan risiko kesehatan mereka.

## 2. Business Understanding

Proyek ini dibangun untuk perusahaan asuransi kesehatan dengan karakteristik bisnis sebagai berikut:

1. Perusahaan Asuransi Kesehatan yang Berorientasi pada Analisis Data: Perusahaan ini memiliki kepentingan dan komitmen dalam mengoptimalkan penggunaan data untuk meningkatkan keputusan bisnis. Mereka mengakui nilai analisis prediktif dan *machine learning* dalam menentukan premi asuransi kesehatan yang akurat dan berdasarkan risiko individual.

2. Perusahaan dengan Basis Data Pelanggan yang Kaya: Perusahaan ini memiliki akses dan kepemilikan data pelanggan yang lengkap dan kaya akan informasi. Data tersebut mencakup variabel seperti usia, riwayat medis, operasi sebelumnya, alergi, riwayat penyakit keluarga, serta data fisik seperti tinggi dan berat badan. Data pelanggan yang kaya ini akan menjadi sumber informasi yang berharga dalam mengembangkan model prediktif.

3. Perusahaan yang Berfokus pada Keunggulan Kompetitif: Perusahaan ini mengutamakan keunggulan kompetitif di pasar asuransi kesehatan. Mereka ingin memanfaatkan teknik analisis prediktif dan *machine learning* untuk meningkatkan proses penetapan premi, memberikan perkiraan premi yang lebih akurat, serta menawarkan produk asuransi yang lebih menarik dan kompetitif bagi calon pemegang polis.

Dengan memahami karakteristik bisnis perusahaan asuransi kesehatan ini, proyek ini dapat dirancang dan disesuaikan untuk memenuhi kebutuhan dan tujuan bisnis yang spesifik.

Oleh sebab itu, proyek "Medical Insurance Premium Prediction" ini dapat membantu perusahaan asuransi kesehatan dengan karakteristik bisnis di atas dalam meningkatkan keputusan bisnis dan mencapai keunggulan kompetitif sebagai berikut:

1. Penentuan Premi yang Lebih Akurat: Dengan menggunakan model analisis prediktif yang dikembangkan dalam proyek ini, perusahaan dapat menentukan premi asuransi kesehatan yang lebih akurat berdasarkan faktor-faktor risiko yang relevan. Dengan mempertimbangkan variabel seperti usia, riwayat medis, operasi sebelumnya, riwayat penyakit keluarga, dan data fisik lainnya, model ini dapat memberikan estimasi premi yang lebih tepat dan konsisten. Hal ini membantu perusahaan mengambil keputusan yang lebih informasional dan meminimalkan risiko keuangan yang tidak terduga.

2. Peningkatan Efisiensi dan Produktivitas: Dengan memanfaatkan teknologi analisis prediktif dan *machine learning*, perusahaan dapat meningkatkan efisiensi dan produktivitas dalam proses penetapan premi. Model prediktif dapat secara otomatis memproses data dan memberikan perkiraan premi yang lebih cepat, mengurangi waktu dan upaya yang dibutuhkan dalam proses manual yang lebih lambat dan rentan terhadap kesalahan. Ini memungkinkan perusahaan untuk lebih fokus pada kegiatan inti bisnis mereka dan meningkatkan produktivitas keseluruhan.

3. Pengambilan Keputusan yang Lebih Informasional: Dengan menggunakan model analisis prediktif yang akurat, perusahaan dapat mengambil keputusan bisnis yang lebih informasional dan cerdas. Model ini memberikan wawasan yang lebih dalam tentang faktor-faktor risiko yang mempengaruhi premi asuransi kesehatan, membantu perusahaan memahami pelanggan mereka dengan lebih baik, dan mengidentifikasi pola atau tren yang relevan. Informasi ini memungkinkan perusahaan untuk mengoptimalkan strategi bisnis mereka, meningkatkan layanan kepada pelanggan, dan mengidentifikasi peluang baru di pasar asuransi kesehatan.

4. Keunggulan Kompetitif dalam Pasar: Dengan menggunakan model analisis prediktif yang lebih canggih dan akurat, perusahaan asuransi kesehatan dapat mencapai keunggulan kompetitif di pasar. Dengan memperkirakan premi dengan lebih tepat dan memberikan estimasi yang lebih adil, perusahaan dapat menarik calon pemegang polis dengan produk asuransi yang lebih menarik dan kompetitif. Hal ini membantu perusahaan membedakan diri dari pesaing, memperluas pangsa pasar, dan membangun hubungan jangka panjang dengan pelanggan.

Dengan memanfaatkan model prediktif yang dikembangkan dalam proyek ini, perusahaan asuransi kesehatan dapat mengambil keputusan bisnis yang lebih baik, meningkatkan efisiensi operasional, mencapai keunggulan kompetitif, dan memberikan layanan yang lebih baik kepada calon pemegang polis.

## 3. Problem Statements

- Apa langkah yang dapat diambil untuk meningkatkan akurasi dalam menentukan premi asuransi kesehatan?

Perusahaan asuransi menghadapi tantangan dalam menentukan premi yang akurat dan adil bagi calon pemegang polis. Hal ini disebabkan oleh keterbatasan dalam memahami faktor-faktor yang mempengaruhi besaran premi. 

Dalam proyek ini, kami akan mengatasi masalah ini dengan mengembangkan model analisis prediktif yang dapat memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi.

- Bagaimana caranya untuk meningkatkan transparansi dalam penetapan premi asuransi kesehatan?

Calon pemegang polis seringkali merasa bahwa penetapan premi asuransi kesehatan dilakukan secara tidak adil atau tidak transparan. Mereka tidak memahami faktor-faktor apa yang menjadi dasar penentuan premi.

Dalam proyek ini, kami akan mencoba meningkatkan transparansi dengan mengidentifikasi faktor-faktor yang paling signifikan dalam menentukan premi asuransi kesehatan, sehingga calon pemegang polis dapat memahami alasan di balik besaran premi yang mereka terima.

- Bagaimana risiko keuangan yang terkait dengan penentuan premi yang tidak akurat dapat dikurangi?
  
Penentuan premi yang tidak akurat dapat menyebabkan risiko keuangan bagi perusahaan asuransi. Jika premi yang ditetapkan terlalu rendah, perusahaan dapat menghadapi kerugian finansial jika terjadi klaim yang tinggi. 

Di sisi lain, premi yang terlalu tinggi dapat mengurangi daya tarik produk asuransi. Dalam proyek ini, kami akan membantu mengurangi risiko keuangan dengan memperkirakan premi yang lebih akurat berdasarkan faktor-faktor risiko yang relevan.

Dalam konteks penentuan premi asuransi kesehatan, berikut adalah contoh konkret dari faktor-faktor spesifik yang seringkali menyebabkan masalah-masalah yang disebutkan sebelumnya:

1. Kurangnya akurasi dalam menentukan premi asuransi kesehatan:
   - Masalah: Kurangnya pemahaman tentang faktor-faktor risiko yang berkontribusi pada biaya asuransi kesehatan, seperti riwayat medis, usia, jenis kelamin, gaya hidup, atau kondisi kesehatan tertentu.
   - Contoh: Seorang calon pemegang polis yang memiliki riwayat keluarga dengan penyakit jantung mungkin dikenakan premi yang tidak akurat karena tidak adanya pemahaman yang cukup tentang hubungan antara faktor ini dengan risiko kesehatan seseorang.

2. Kurangnya transparansi dalam penetapan premi:
   - Masalah: Ketidaktahuan calon pemegang polis mengenai faktor-faktor yang digunakan oleh perusahaan asuransi dalam menentukan premi asuransi kesehatan.
   - Contoh: Seorang calon pemegang polis mungkin tidak mengetahui bahwa faktor seperti indeks massa tubuh (BMI), kebiasaan merokok, atau sejarah perawatan medis sebelumnya berdampak signifikan pada besaran premi yang diberikan.

3. Risiko keuangan bagi perusahaan asuransi:
   - Masalah: Penentuan premi yang tidak akurat dapat menyebabkan ketidakseimbangan antara risiko yang ditanggung oleh perusahaan dan premi yang diterima.
   - Contoh: Jika perusahaan asuransi menetapkan premi yang terlalu rendah untuk kelompok tertentu yang memiliki risiko tinggi, mereka dapat menghadapi klaim yang melebihi pendapatan premi, mengakibatkan kerugian finansial.

Dalam proyek "Medical Insurance Premium Prediction", faktor-faktor ini akan dianalisis secara komprehensif dan dimasukkan ke dalam model analisis prediktif. 

Dengan memanfaatkan teknik *machine learning*, model ini akan menghasilkan perkiraan premi yang lebih akurat, mempertimbangkan faktor-faktor risiko yang relevan dengan tingkat keakuratan yang lebih tinggi.

Selain itu, dengan mengidentifikasi faktor-faktor yang paling signifikan dalam penetapan premi, perusahaan asuransi dapat memberikan penjelasan yang lebih baik kepada calon pemegang polis mengenai alasan di balik besaran premi yang mereka terima, meningkatkan transparansi dan kepercayaan.

## 4. Goals

Proyek ini memiliki tujuan sebagai berikut:

1. Mengembangkan model analisis prediktif: Tujuan utama proyek ini adalah mengembangkan model analisis prediktif yang dapat memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi. Dengan melakukan analisis data yang komprehensif dan menggunakan teknik *machine learning*, tujuannya adalah menciptakan model yang dapat memberikan perkiraan premi yang lebih tepat berdasarkan faktor-faktor risiko yang relevan.

2. Meningkatkan transparansi: Proyek ini bertujuan untuk meningkatkan transparansi dalam penetapan premi asuransi kesehatan. Dengan mengidentifikasi faktor-faktor yang paling signifikan dalam menentukan premi, tujuannya adalah memberikan pemahaman yang lebih baik kepada calon pemegang polis mengenai alasan di balik besaran premi yang mereka terima. Hal ini akan membantu membangun kepercayaan dan kepuasan calon pemegang polis terhadap perusahaan asuransi.

3. Mengurangi risiko keuangan: Salah satu tujuan proyek ini adalah membantu perusahaan asuransi mengurangi risiko keuangan yang terkait dengan penetapan premi yang tidak akurat. Dengan memperkirakan premi dengan lebih akurat berdasarkan faktor-faktor risiko yang relevan, perusahaan asuransi dapat mengoptimalkan pengelolaan risiko keuangan mereka, menghindari kerugian yang tidak diharapkan, dan menjaga stabilitas keuangan perusahaan.

Metrik evaluasi yang digunakan untuk mengukur keberhasilan mencapai setiap tujuan dapat meliputi:

- Akurasi prediksi: Metrik ini digunakan untuk mengukur sejauh mana model analisis prediktif dapat memperkirakan premi asuransi kesehatan dengan tepat. Nilai akurasi yang tinggi menunjukkan bahwa model memberikan perkiraan yang lebih akurat, sehingga membantu mencapai tujuan pertama.

- Tingkat transparansi: Metrik ini dapat diukur dengan melakukan survei atau penilaian terhadap calon pemegang polis untuk mengukur tingkat pemahaman mereka tentang alasan di balik besarnya premi yang mereka terima. Semakin tinggi tingkat pemahaman dan kepercayaan calon pemegang polis terhadap alasan penetapan premi, semakin tinggi pula tingkat transparansi yang dicapai.

- Risiko keuangan: Metrik ini dapat diukur dengan membandingkan kinerja keuangan perusahaan asuransi sebelum dan setelah penerapan model analisis prediktif. Jika risiko keuangan berkurang setelah menggunakan model, hal ini menunjukkan bahwa tujuan ketiga tercapai.

Selain itu, metrik lain yang dapat digunakan untuk mengukur keberhasilan proyek ini adalah ialah *Mean Squared Error* (*MSE*): Metrik ini dapat digunakan untuk mengukur seberapa dekat prediksi premi dengan nilai sebenarnya. Semakin rendah nilai *MSE*, semakin baik model analisis prediktif dalam memperkirakan premi.

Penggunaan metrik evaluasi yang tepat dan relevan dengan tujuan proyek akan membantu dalam menilai keberhasilan dan dampak proyek terhadap perusahaan asuransi dan calon pemegang polis.

## 5. Solution statements

Solusi yang diberikan untuk proyek ini melibatkan beberapa tahapan dan algoritma yang digunakan. Berikut adalah penjelasan yang lebih rinci mengenai solusi yang diberikan:

1. Eksplorasi Data (Exploratory Data Analysis - EDA):
   - Sebelum melatih model, proses EDA akan dilakukan untuk memahami karakteristik data yang ada. EDA akan membantu dalam mengidentifikasi pola, melihat hubungan antar variabel, dan menemukan wawasan yang berguna dalam memprediksi premi asuransi kesehatan.

2. Algoritma *SVR* (Support Vector Regression) dan *Huber Regressor*:
   - Algoritma *SVR* dan *Huber Regressor* dipilih sebagai algoritma *machine learning* yang akan digunakan dalam proyek ini.
   - *SVR* adalah algoritma yang digunakan untuk memodelkan dan memprediksi data regresi. Dalam proyek ini, *SVR* akan digunakan untuk memprediksi premi asuransi kesehatan berdasarkan faktor-faktor risiko yang relevan.
   - *Huber Regressor* adalah algoritma regresi yang robust terhadap *outlier*s. Ini adalah salah satu metode yang efektif dalam menangani data yang memiliki noise atau pencilan (*outlier*s). *Huber Regressor* dapat memberikan hasil prediksi yang lebih stabil dan tahan terhadap gangguan dari data yang ekstrem.

3. Penggunaan *Library* PyCaret:
   - *Library* PyCaret akan digunakan untuk menentukan algoritma *machine learning* yang optimal untuk proyek ini.
   - PyCaret menyediakan berbagai algoritma *machine learning* yang siap pakai dan memfasilitasi proses pemilihan algoritma yang terbaik berdasarkan data dan tujuan proyek.
   - Dengan menggunakan PyCaret, proses pemilihan algoritma dapat dilakukan dengan lebih efisien dan cepat.

4. Evaluasi dengan Metrik *MSE* (Mean Squared Error):
   - Metrik *MSE* (Mean Squared Error) akan digunakan untuk melakukan evaluasi pembanding antara model-model yang dikembangkan.
   - *MSE* adalah metrik yang umum digunakan dalam masalah regresi untuk mengukur sejauh mana selisih antara nilai prediksi dan nilai sebenarnya.
   - Dengan menggunakan metrik *MSE*, kita dapat mengukur tingkat keakuratan model dalam memprediksi premi asuransi kesehatan.

Proses pemilihan algoritma lain dalam *library* PyCaret melibatkan eksperimen dan evaluasi berdasarkan kinerja model menggunakan metrik evaluasi yang relevan, seperti *MSE*. 

PyCaret menyediakan fungsionalitas yang memungkinkan untuk membandingkan kinerja berbagai algoritma dengan cepat dan memilih algoritma yang memberikan hasil terbaik.

Melalui pendekatan ini, diharapkan solusi yang diberikan dapat memenuhi tujuan proyek dalam mengembangkan model analisis prediktif yang akurat dan efektif untuk memprediksi premi asuransi kesehatan.

## 6. Data Understanding

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
- Melakukan tahapan EDA seperti mendeskripsikan variabel, mencari *outlier*s, Univariate hingga Multi-variate analysis.
- Untuk menganalisa *outlier*s bisa menggunaka boxplot dengan memanggil fungsi .plot() pada pandas
- Mengecek data missing value dan membersihkan data missing value dengan membuat simple logic program
- Menggunakan histogram untuk melihat penyebaran data dengan *library* pandas fungsi .hist()
- Mencari keterkaitan antar fitur numerik dan fitur kategori dengan correlation matrix menggunakan fungsi pandas dan visualisasi heatmap dengan seaborn

### Visualisasi proses Data Understanding

Untuk mengatasi outlier, salah satu metode yang umum digunakan adalah metode IQR (Interquartile Range) dengan visualisasi menggunakan boxplot. Berikut penjelasan mengenai metode IQR dan visualisasi boxplot:

Metode IQR:
1. Konsep: IQR merupakan ukuran statistik yang menggambarkan rentang atau sebaran data pada bagian tengah distribusi data. IQR dihitung dengan mengurangi nilai kuartil ketiga (Q3) dengan nilai kuartil pertama (Q1). Outlier dianggap sebagai nilai yang terletak di luar rentang IQR yang ditentukan.
2. Cara Kerja:
   - Hitung Q1 (kuartil pertama) dan Q3 (kuartil ketiga) dari data.
   - Hitung IQR dengan mengurangi Q1 dari Q3.
   - Tentukan batas atas dan batas bawah untuk outlier dengan menggunakan rumus: batas atas = Q3 + (1.5 * IQR), batas bawah = Q1 - (1.5 * IQR).
   - Data yang berada di luar batas atas dan batas bawah tersebut dianggap sebagai outlier.

Visualisasi Boxplot:
1. Konsep: Boxplot adalah visualisasi grafis yang digunakan untuk menganalisis distribusi data dan mengidentifikasi adanya outlier. Boxplot menampilkan beberapa ukuran statistik, termasuk Q1, Q3, median, serta batas atas dan batas bawah untuk outlier.
2. Cara Kerja:
   - Boxplot terdiri dari sebuah kotak (box) yang menunjukkan rentang IQR (dari Q1 hingga Q3).
   - Garis di dalam kotak menunjukkan posisi median.
   - Whisker atau garis lurus yang terhubung dengan kotak menunjukkan rentang data yang dianggap tidak sebagai outlier.
   - Titik-titik di luar whisker menunjukkan adanya outlier.
  
![outliers_boxplot](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/994b7ef1-fe6d-4bc4-94a5-5800322fe11f)
###### Gambar 6.1 Visualisasi outliers menggunakan boxplot

Dengan menggunakan metode IQR dan visualisasi boxplot, kita dapat mengidentifikasi dan mengatasi outlier dalam data. Outlier dapat menjadi nilai yang ekstrem dan tidak biasa yang dapat mempengaruhi hasil analisis statistik dan model prediksi. 

Dengan memperhatikan IQR dan melihat visualisasi boxplot, kita dapat menentukan batas atas dan batas bawah untuk outlier, serta mengambil tindakan yang tepat, seperti menghapus atau mengelola outlier tersebut, agar tidak mempengaruhi hasil analisis secara signifikan.

Kemudian untuk menganalisa sebaran dataset, kita dapat menggunakan histogram. Histogram adalah visualisasi grafis yang digunakan untuk menampilkan distribusi frekuensi dari suatu variabel dalam bentuk interval atau bin.

Berikut adalah langkah-langkah untuk menganalisa sebaran dataset menggunakan histogram:

1. Membagi Data Menjadi Interval atau Bin:
   - Pertama, kita perlu membagi data ke dalam interval atau bin. Jumlah dan lebar interval dapat bervariasi tergantung pada dataset dan tujuan analisis.
   - Untuk mendapatkan jumlah interval yang tepat, kita bisa menggunakan aturan umum seperti aturan Sturges atau Scott's normal reference rule.

2. Menghitung Frekuensi:
   - Selanjutnya, kita menghitung frekuensi munculnya data di setiap interval. Frekuensi dapat dihitung sebagai jumlah observasi yang jatuh di dalam setiap interval.

3. Visualisasi dengan Histogram:
   - Dengan menggunakan data frekuensi yang telah dihitung, kita dapat membuat histogram.
   - Pada sumbu horizontal, kita menempatkan interval atau bin, sedangkan pada sumbu vertikal, kita menampilkan frekuensi munculnya data dalam interval tersebut.
   - Untuk menggambarkan histogram, kita dapat menggunakan bar-chart dengan lebar bar yang mencerminkan lebar interval.

4. Interpretasi:
   - Dengan melihat histogram, kita dapat menganalisa sebaran dataset secara visual.
   - Kita dapat melihat apakah data memiliki distribusi normal, simetris, asimetris (ke kiri atau ke kanan), atau memiliki pola tertentu seperti bimodal (dua puncak).
   - Kita juga dapat melihat kisaran nilai yang paling sering muncul dan sebaran nilai di dalam dataset.

Histogram membantu kita memahami pola dan sebaran data dengan cepat. Analisis sebaran dataset menggunakan histogram memungkinkan kita mengidentifikasi tipe distribusi data, menentukan apakah terdapat outlier, dan memperoleh gambaran umum tentang data tersebut. 

Hal ini dapat menjadi langkah awal dalam eksplorasi data sebelum melakukan analisis lebih lanjut atau membangun model prediksi.

![histogram](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/88d5ec99-beca-4d6f-a34d-a95921c4fe79)
###### Gambar 6.2 Sebaran dataset

![pairplot](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/ab84ebd0-4fe9-4436-9439-359c83ee7eb3)
###### Gambar 6.2 Korelasi PremiumPrice dengan fitur lainnya

Terakhir, untuk menganalisa keterkaitan antara fitur numerik dan fitur kategori, kita dapat menggunakan correlation matrix dengan fungsi pandas dan visualisasi heatmap menggunakan library seaborn. 

Heatmap menunjukkan tingkat korelasi antara setiap pasangan fitur numerik dan fitur kategori. Warna dalam heatmap mencerminkan tingkat korelasi, di mana warna lebih terang menunjukkan korelasi yang lebih kuat, sedangkan warna lebih gelap menunjukkan korelasi yang lebih lemah atau tidak ada korelasi.

Kita dapat melihat hubungan positif atau negatif antara fitur numerik dan fitur kategori berdasarkan nilai korelasi. Analisis ini membantu dalam memahami keterkaitan antar fitur-fitur dalam dataset dan dapat memberikan wawasan yang berguna untuk pemilihan fitur, pemodelan, atau analisis lebih lanjut.

Dengan menggunakan correlation matrix dan visualisasi heatmap, kita dapat dengan mudah menganalisa keterkaitan antara fitur numerik dan fitur kategori dalam dataset secara visual dan kuantitatif.

![correlation_matrix](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/9b8346a0-2cab-4184-be8a-789a447e7f6d)
###### Gambar 6.3 Matriks korelasi PremiumPrice 

Dapat dilihat dari gambar matriks di atas bahwa variabel *AnyTransplants*, *AnyChronicDiseases*, dan *NumberOfMajorSurgeries* memiliki warna heatmap yang terang dan ini menunjukkan bahwa ketiga variabel tersebut memiliki korelasi dengan variabel *PremiumPrice*     

## 7. Data Preparation

Berikut ada teknik yang digunakan dalam proses data preparation, yaitu:

Proses *One Hot Encoding* pada fitur kategorikal adalah teknik yang digunakan untuk mengubah variabel kategorikal menjadi representasi numerik yang dapat digunakan dalam model *machine learning*. 

Hal ini diperlukan karena sebagian besar algoritma *machine learning* hanya dapat bekerja dengan input numerik.

Pandas *library* menyediakan fungsi pd.get_dummies() yang memudahkan dalam melakukan *One Hot Encoding*. Fungsi ini akan menghasilkan kolom-kolom baru yang mewakili setiap nilai unik dari fitur kategorikal. Jika suatu baris memiliki nilai tersebut, kolom yang sesuai akan diatur menjadi 1, sedangkan kolom lainnya akan menjadi 0.

Misalnya, jika terdapat fitur "Warna" dengan nilai "Merah", "Biru", dan "Hijau", setelah One Hot Encoding akan terbentuk tiga kolom baru: "Warna_Merah", "Warna_Biru", dan "Warna_Hijau". 

Jika suatu baris memiliki nilai "Merah" pada fitur "Warna", maka kolom "Warna_Merah" akan diatur menjadi 1, sedangkan kolom lainnya akan menjadi 0.

Proses pembagian dataset menjadi data training dan data testing penting dalam pengembangan model *machine learning*. Ini dilakukan untuk mengevaluasi performa model pada data yang belum pernah dilihat sebelumnya dan untuk menghindari *overfitting*. 

Data training digunakan untuk melatih model, sedangkan data testing digunakan untuk menguji seberapa baik model yang dilatih dapat melakukan prediksi pada data yang belum pernah dilihat sebelumnya. 

Dengan memisahkan data training dan data testing, kita dapat mengukur sejauh mana model dapat mengeneralisasi dan memprediksi dengan akurat pada data baru.

Rasio 80:20 sering digunakan sebagai perbandingan pembagian data training dan data testing. Data training sebesar 80% digunakan untuk melatih model, sementara data testing sebesar 20% digunakan untuk menguji performa model. 

Rasio ini merupakan aturan praktis umum yang memberikan keseimbangan antara memiliki jumlah data yang cukup untuk melatih model dan menyediakan data yang cukup untuk menguji performa model. 

Namun, rasio ini dapat bervariasi tergantung pada karakteristik dataset dan kebutuhan proyek tertentu.

## 8. Modeling
Dalam proses modeling, proyek ini akan menggunakan algoritma *SVR* dan algoritma *Huber Regressor* berdasarkan hasil dari data *library* pycaret.

Algoritma *SVR* (Support Vector Regression) dan *Huber Regressor* adalah dua algoritma yang umum digunakan dalam masalah regresi. Kedua algoritma ini digunakan dalam proyek ini untuk memprediksi premi asuransi kesehatan berdasarkan faktor-faktor risiko yang relevan. Berikut adalah penjelasan mengenai konsep dan cara kerja keduanya:

*Support Vector Regression* (SVR):
   - Konsep: *SVR* adalah variasi *dari Support Vector Machines* (SVM) yang digunakan dalam masalah regresi. Tujuan utama SVR adalah untuk menemukan fungsi regresi yang paling baik yang meminimalkan kesalahan prediksi pada data training dengan tetap mempertahankan margin maksimum.
   - Cara Kerja: *SVR* bekerja dengan mencari hyperplane (bidang) yang dapat memisahkan data training dengan margin maksimum. *Hyperplane* ini berfungsi sebagai fungsi regresi yang memprediksi nilai target berdasarkan fitur-fitur input. Dalam *SVR*, titik-titik data yang berada di luar margin maksimum tetap diperbolehkan, sehingga mengakomodasi adanya pencilan (outliers). *SVR* mengoptimalkan margin dengan menyeimbangkan kesalahan prediksi dan kompleksitas model.
   - Kelebihan: *SVR* efektif dalam menangani masalah regresi dengan data yang memiliki noise atau pencilan (outliers). Algoritma ini juga memiliki fleksibilitas dalam memilih fungsi kernel yang sesuai untuk memodelkan hubungan non-linear antara fitur input dan target.

*Huber Regressor*:
   - Konsep: *Huber Regressor* adalah algoritma regresi yang robust terhadap *outliers*. Algoritma ini menggabungkan metode *Least Squares* (LS) dan *Least Absolute Deviations* (LAD) dengan menggunakan fungsi kerugian *Huber*.
   - Cara Kerja: *Huber Regressor* menghitung residual atau selisih antara nilai prediksi dan nilai sebenarnya. Jika residual lebih kecil dari suatu ambang batas, *Huber Regressor* menggunakan fungsi kerugian Least Squares (LS) yang merupakan kuadrat dari residual. Namun, jika residual lebih besar dari ambang batas, fungsi kerugian yang digunakan adalah fungsi kerugian Least Absolute Deviations (LAD) yang merupakan nilai absolut dari residual. Dengan demikian, *Huber Regressor* memberikan penekanan yang lebih besar pada ketahanan terhadap pencilan dibandingkan dengan metode Least Squares.
   - Kelebihan: *Huber Regressor* efektif dalam menangani data yang memiliki pencilan yang signifikan. Dibandingkan dengan metode Least Squares, *Huber Regressor* memiliki performa yang lebih baik ketika terdapat pencilan yang signifikan dalam data. Algoritma ini memungkinkan penyesuaian yang lebih baik terhadap karakteristik data yang berbeda.

Dalam proyek ini, kedua algoritma tersebut digunakan untuk memodelkan hubungan antara faktor-faktor risiko yang relevan dengan premi asuransi kesehatan. 

Dengan menggunakan konsep dan cara kerja yang telah dijelaskan, algoritma *SVR* dan *Huber Regressor* dapat menghasilkan prediksi premi yang lebih akurat dan tahan terhadap pencilan (outliers) dalam data.

### Tahapan yang dilakukan
Berikut adalah urutan tahapan yang dilakukan dalam proses modeling:
 - Melatih model dengan data training dengan menggunakan algoritma *Huber Regressor* dan *SVR*
 - Dalam tahap training, pengujian model dilakukan dengan menggunakan parameter default bawaan *library*
 - Melakukan pengujian dengan data training
 - Melakukan pengujian dengan data testing
 - Pengukuran menggunakan metriks *MSE*,MAE,R*MSE* dan R2 dengan menggunakan lirbary sklearn. 
 - Melihat hasil performa model antara hasil data training dan data testing
 - Meningkatkan performa model dengan menerapkan grid search atau *hyperparameter* pada model
 - Menggunakan *hyperparameter* pada *Huber Regressor* yaitu param_grid = { 'epsilon': [1.0, 1.5, 2.0],'alpha': [0.0001, 0.001, 0.01], 'max_iter': [100, 200, 300]}
 - Menggunakan *hyperparameter* pada *SVR* yaitu param_grid = {'kernel': ['linear', 'rbf'],'C': [0.1, 1, 10],'epsilon': [0.1, 0.2, 0.3]}
 - Setelah pengujian *hyperparameter*, *Huber Regressor* mendapatkan param terbaik yaitu: {'alpha': 0.01, 'epsilon': 2.0, 'max_iter': 100}
 - Setelah pengujian *hyperparameter*, *SVR* mendapatkan param terbaik yaitu: {'C': 1, 'epsilon': 0.1, 'kernel': 'linear'

 - Huber_*MSE*: Rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual pada data training adalah sekitar 18,480,694.56826, sedangkan pada data testing sekitar 25,177,990.875244. Hasil ini menunjukkan bahwa model memiliki tingkat kesalahan yang sedikit lebih tinggi pada data testing dibandingkan dengan data training.
 - *SVR*_*MSE*: Rata-rata dari kuadrat selisih antara nilai prediksi dan nilai aktual pada data training adalah sekitar 40,114,366.684487, sedangkan pada data testing sekitar 42,742,505.675315. Hasil ini menunjukkan bahwa model testing memiliki tingkat kesalahan yang sedikit lebih tinggi pada data testing dibandingkan dengan data training.

Kesimpulan yang dapat diambil dari paparan di atas ialah adanya overfitting pada data training karena model cenderung memiliki tingkat kesalahan yang lebih tinggi pada data testing. 

### Kelebihan dan Kekurangan
 - Algoritma *Huber Regressor* memiliki keunggulan lebih tahan terhadap adanya *outlier* dan oleh karena itu dapat memberikan hasil yang lebih konsisten dan stabil dibandingkan dengan regresi linier biasa
 - Algoritma *Huber Regressor* memiliki kekurangan dalam pemilihan nilai yang tepat untuk delta dapat mempengaruhi kinerja algoritma, dan penyesuaian parameter ini sering kali memerlukan pengujian dan penyesuaian manual. 
 - Algoritma *SVR* memiliki keunggulan dapat menggunakan fungsi kernel yang berbeda untuk mengubah data input menjadi ruang fitur yang lebih tinggi, memungkinkan pemodelan yang lebih fleksibel dan penanganan kasus-kasus di mana hubungan antara fitur dan target bersifat non-linear.
 - Algoritma *SVR* memiliki kekurangan sangat sensitif terhadap skala data input. Oleh karena itu, penting untuk melakukan normalisasi atau penskalaan data sebelum menggunakan *SVR* untuk menghindari bias yang tidak diinginkan dalam model.

Berdasarkan pertimbangan kelebihan dan kekurangan di atas, maka algoritma *Huber Regressor* dinilai lebih unggul dari *SVR* dan setelahnya perlu menerapkan *hyperparameter* saat model masuk ke evaluasi.

## 9. Evaluation

Metrik evaluasi yang digunakan dalam proyek ini ialah sebagai berikut:

### *MSE*
Mean Square Error (*MSE*) adalah salah satu metrik evaluasi yang digunakan untuk mengukur sejauh mana perbedaan antara nilai prediksi dan nilai sebenarnya dalam masalah regresi. 

Model evaluasi *MSE* menghitung rata-rata dari kuadrat selisih antara nilai prediksi dan nilai sebenarnya. Semakin kecil *MSE*, semakin baik model tersebut dalam melakukan prediksi yang akurat.

Berikut adalah langkah-langkah untuk menghitung *MSE*:

1. Mulai dengan memiliki kumpulan data yang terdiri dari pasangan nilai sebenarnya (y) dan nilai prediksi (ŷ) untuk sejumlah contoh atau sampel.

2. Hitung selisih antara nilai sebenarnya dan nilai prediksi untuk setiap contoh. Selisih ini merupakan error atau kesalahan prediksi untuk masing-masing contoh.

3. Kuadratkan setiap selisih. Ini dilakukan untuk memastikan bahwa setiap error memiliki kontribusi positif terhadap nilai *MSE*, tanpa mempertimbangkan apakah prediksi lebih rendah atau lebih tinggi dari nilai sebenarnya.

4. Hitung rata-rata dari kuadrat selisih. Caranya adalah dengan menjumlahkan semua kuadrat selisih dan membaginya dengan jumlah contoh.

   *MSE* = (Σ (y - ŷ)²) / n
   
   di mana:
   - Σ menunjukkan penjumlahan
   - y adalah nilai sebenarnya
   - ŷ adalah nilai prediksi
   - n adalah jumlah contoh atau sampel dalam dataset.

5. Setelah menghitung *MSE*, semakin kecil nilai *MSE*, semakin baik model dalam melakukan prediksi yang akurat. *MSE* memiliki satuan yang berbeda dengan variabel yang dievaluasi, karena hasilnya berupa kuadrat. Oleh karena itu, *MSE* seringkali diinterpretasikan dalam konteks yang lebih luas, atau perbandingannya dibandingkan dengan metrik evaluasi lainnya.

Tabel 9.1 Tabel hasil running evaluasi model setelah menggunakan *hyperparameter*
|           | Huber         | SVR            |
|-----------|---------------|----------------|
| train_MSE | 18480694.56826 | 40114366.684487 |
| test_MSE  | 25177990.875244 | 42742505.675315 |
| eval_train | 18104561.09466 | 18614533.696279 |
| eval_test  | 24212812.866265 | 25605704.542962 |

Berikut adalah grafik hasil evaluasi model setelah dilakukan penerapan *hyperparameter*.

![model_eval_hy_params](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/d374d1d7-fcc2-4afb-9745-a221cacb2453)
###### Gambar 9.1 Hasil evaluasi model setelah penerapan *hyperparameter*

*MSE* merupakan metrik evaluasi yang umum digunakan dalam masalah regresi karena memperhitungkan perbedaan antara nilai prediksi dan nilai sebenarnya secara keseluruhan dan memberikan bobot yang lebih besar pada perbedaan yang besar. 

Namun, *MSE* juga memiliki kelemahan yaitu sensitif terhadap *outlier*, artinya nilai ekstrem yang sangat berbeda dapat mempengaruhi *MSE* secara signifikan. 

Oleh karena itu, terkadang metrik evaluasi alternatif seperti *Mean Absolute Error* (MAE) juga digunakan untuk memberikan gambaran yang lebih lengkap tentang kinerja model.

Berdasarkan hasil evaluasi model setelah menggunakan *hyperparameter*, kita dapat mengambil beberapa kesimpulan:

1. *Mean Squared Error* (*MSE*) - Train Set:
   - Model *Huber* memiliki *MSE* train set sebesar 18,480,694.56826.
   - Model *SVR* memiliki *MSE* train set sebesar 40,114,366.684487.
   - Model *Huber* memiliki nilai *MSE* yang lebih rendah dibandingkan dengan model *SVR* pada data training. Artinya, model Huber mampu melakukan prediksi yang lebih akurat daripada model *SVR*.

2. *Mean Squared Error* (*MSE*) - Test Set:
   - Model *Huber* memiliki *MSE* test set sebesar 25,177,990.875244.
   - Model *SVR* memiliki *MSE* test set sebesar 42,742,505.675315.
   - Model *Huber* juga memiliki nilai *MSE* yang lebih rendah dibandingkan dengan model *SVR* pada data testing. Hal ini menunjukkan bahwa model *Huber* lebih baik dalam melakukan prediksi pada data yang belum pernah dilihat sebelumnya.

3. Evaluation Score (eval) - Train Set:
   - Model *Huber* memiliki evaluasi score train set sebesar 18,104,561.09466.
   - Model *SVR* memiliki evaluasi score train set sebesar 18,614,533.696279.
   - Meskipun model *Huber* memiliki *MSE* yang lebih rendah pada data training, evaluasi score keduanya memiliki perbedaan yang cukup kecil. Kedua model memberikan performa yang serupa pada data training.

4. Evaluation Score (eval) - Test Set:
   - Model *Huber* memiliki evaluasi score test set sebesar 24,212,812.866265.
   - Model *SVR* memiliki evaluasi score test set sebesar 25,605,704.542962.
   - Model *Huber* juga memberikan evaluasi score yang lebih rendah dibandingkan dengan model *SVR* pada data testing. Hal ini menunjukkan bahwa model *Huber* lebih baik dalam melakukan prediksi yang lebih akurat pada data yang belum pernah dilihat sebelumnya.

Berdasarkan kesimpulan di atas, model *Huber* memiliki performa yang lebih baik daripada model *SVR* dalam memprediksi premi asuransi kesehatan. Model *Huber* memiliki *MSE* yang lebih rendah baik pada data training maupun test set, serta memberikan evaluasi score yang lebih baik pada data testing. 

Oleh karena itu, model *Huber* dapat dianggap lebih optimal dalam proyek ini untuk memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi.

## 10. Kesimpulan 

Proyek ini berhasil mengembangkan model analisis prediktif menggunakan model *Huber* yang mampu memperkirakan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi dibandingkan dengan model *SVR*. 

Hasil evaluasi menunjukkan bahwa model *Huber* memberikan *MSE* yang lebih rendah pada data training dan test set, serta evaluasi score yang lebih baik pada data testing. 

Hal ini menunjukkan bahwa model *Huber* dapat memberikan prediksi premi yang lebih akurat dan bermanfaat bagi perusahaan asuransi dan calon pemegang polis.

Manfaat bagi Perusahaan Asuransi:
- Penentuan premi yang lebih akurat: Model *Huber* dapat membantu perusahaan asuransi menentukan premi asuransi kesehatan dengan tingkat akurasi yang lebih tinggi, mengurangi risiko keuangan dan meningkatkan efisiensi dalam pengelolaan risiko.

- Transparansi yang ditingkatkan: Dengan memahami faktor-faktor yang signifikan dalam penetapan premi, perusahaan asuransi dapat memberikan penjelasan yang lebih baik kepada calon pemegang polis mengenai alasan di balik besaran premi yang mereka terima, meningkatkan transparansi dan kepercayaan.

Manfaat bagi Calon Pemegang Polis:
- Premi yang adil dan akurat: Model *Huber* dapat memberikan prediksi premi yang lebih adil dan akurat berdasarkan faktor-faktor risiko yang relevan, memastikan bahwa premi yang dibayarkan sejalan dengan risiko yang ditanggung oleh calon pemegang polis.

- Pemahaman yang lebih baik: Dengan penjelasan yang lebih jelas mengenai faktor-faktor yang mempengaruhi penetapan premi, calon pemegang polis dapat memiliki pemahaman yang lebih baik tentang alasan di balik besaran premi yang mereka terima.

Langkah Tindak Lanjut:
- Implementasi model: Model *Huber* yang telah dikembangkan dapat diimplementasikan oleh perusahaan asuransi dalam proses penetapan premi asuransi kesehatan mereka.

- Peningkatan data dan pemeliharaan model: Perusahaan asuransi dapat terus memperkaya data yang digunakan dalam model dan mempertahankan model dengan melakukan pemeliharaan dan pembaruan secara berkala.

- Evaluasi dan peningkatan: Perusahaan asuransi dapat terus mengevaluasi kinerja model dan melakukan perbaikan atau pengembangan lebih lanjut untuk meningkatkan keakuratan dan efektivitas prediksi premi.

Dengan mengambil langkah-langkah tindak lanjut ini, perusahaan asuransi dapat memanfaatkan model analisis prediktif ini untuk meningkatkan ketepatan penetapan premi, meningkatkan transparansi, dan memberikan manfaat yang lebih baik bagi calon pemegang polis dalam pengalaman asuransi kesehatan mereka.

## References: 
Chauluka M, Uzochukwu B, and Chinkhumba J, "Factors Associated With Coverage of Health Insurance Among Women in Malawi," *Frontiers in Health Services*, vol.2, 2022.

Michael Chernew, David M Cutler, and Patricia Seliger Keenan, "Increasing Health Insurance Costs and the Decline in Insurance Coverage,
" *Health Services Research*, vol.40, no.10.1111. 2005. 

Samantha Artiga, Petry Ubri, and Julia Zur, "The Effects of Premiums and Cost Sharing on Low-Income Populations: Updated Review of Research Findings The Effects of Premiums and Cost Sharing on Low-Income Populations 2," *Issue Brief*, 2017



