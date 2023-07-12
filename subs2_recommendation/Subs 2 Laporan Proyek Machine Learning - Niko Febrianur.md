# MLT Proyek Kedua | Coursera Courses Recommendation System

###### Disusun oleh : Niko Febrianur

Ini adalah proyek kedua, membuat sistem rekomendasi untuk memenuhi submission Dicoding Kelas *machine learning* Terapan. 

Proyek ini membangun model *machine learning* yang dapat memberikan rekomendasi kursus Coursera kepada pengguna.

## 1. Project Domain

### Latar belakang

Domain proyek untuk sistem rekomendasi kursus Coursera ini adalah industri pembelajaran online. Di era digital saat ini, banyak individu mencari peluang untuk meningkatkan pengetahuan dan keterampilan mereka melalui platform pembelajaran online. 

Coursera adalah salah satu platform populer yang menawarkan berbagai kursus dari universitas dan lembaga terkemuka di seluruh dunia.

Dalam domain ini, tantangan yang dihadapi adalah bagaimana menyediakan rekomendasi kursus yang relevan dan sesuai dengan minat, tujuan belajar, dan tingkat keahlian pengguna. 

Dalam konteks ini, model *machine learning* dapat memainkan peran penting dalam menganalisis data pengguna, seperti riwayat kursus yang telah diambil, preferensi pengguna, dan ulasan yang diberikan.

Model *machine learning* dapat mempelajari pola dan hubungan antara pengguna dan kursus-kursus yang ada di Coursera. Dengan menggunakan teknik pengolahan bahasa alami (Natural Language Processing) dan teknik pembelajaran mesin lainnya, model dapat memahami teks deskripsi kursus, topik, dan keterkaitan antara kursus-kursus yang ada. 

Model juga dapat menganalisis data pengguna, seperti preferensi, tingkat pemahaman, dan riwayat kursus, untuk memberikan rekomendasi yang personal dan relevan.

Dengan menggunakan sistem rekomendasi ini, pengguna dapat menemukan kursus-kursus yang sesuai dengan minat dan kebutuhan mereka. Hal ini dapat membantu pengguna dalam meningkatkan pengetahuan, keterampilan, dan memperoleh sertifikat atau gelar dalam bidang yang diminati. 

Sistem rekomendasi ini juga dapat membantu Coursera dalam meningkatkan pengalaman pengguna dan mempertahankan anggota dengan menyediakan rekomendasi yang akurat dan bermutu.

Dengan membangun model *machine learning* untuk sistem rekomendasi kursus Coursera, diharapkan dapat memberikan manfaat bagi pengguna dan platform pembelajaran online dalam mempermudah proses pencarian kursus yang sesuai dengan minat dan kebutuhan individu.

## 2. Business Understanding

Dalam konteks proyek ini, pemahaman bisnis adalah memahami tujuan dan manfaat yang ingin dicapai oleh pengembangan sistem rekomendasi kursus Coursera. 

Berikut adalah beberapa poin penting dalam pemahaman bisnis proyek ini:

1. Meningkatkan pengalaman pengguna: sistem rekomendasi kursus Coursera bertujuan untuk meningkatkan pengalaman pengguna dengan menyediakan rekomendasi yang personal dan relevan. Dengan menggunakan model *machine learning*, pengguna akan mendapatkan rekomendasi kursus yang sesuai dengan minat, tujuan belajar, dan tingkat keahlian mereka. Hal ini dapat membantu pengguna dalam menemukan kursus yang menarik dan sesuai dengan kebutuhan mereka.

2. Meningkatkan retensi pengguna: dengan menyediakan rekomendasi yang akurat dan bermutu, sistem ini diharapkan dapat membantu Coursera dalam mempertahankan anggota. Pengguna yang mendapatkan rekomendasi yang relevan dan memberikan nilai tambah dalam perjalanan pembelajaran mereka cenderung tetap aktif dan terlibat dalam platform. Meningkatkan retensi pengguna adalah tujuan bisnis yang penting untuk menghasilkan pertumbuhan jangka panjang.

3. Penyediaan kursus yang relevan: sistem rekomendasi ini juga memberikan manfaat kepada Coursera dalam hal penyediaan kursus yang relevan. Dengan menganalisis preferensi pengguna, keterampilan yang dibutuhkan dalam pasar, dan tren industri, Coursera dapat menggunakan hasil rekomendasi untuk memperbaiki kurikulum dan menawarkan kursus yang sesuai dengan permintaan pengguna.

4. Meningkatkan konversi dan pendapatan: sistem rekomendasi yang efektif dapat meningkatkan konversi, yaitu mengubah pengguna yang hanya menjelajahi platform menjadi peserta kursus yang berlangganan. Dengan memberikan rekomendasi yang menarik dan relevan, pengguna akan cenderung mendaftar dan membayar untuk kursus yang direkomendasikan. Hal ini dapat meningkatkan pendapatan Coursera dan mengoptimalkan model bisnis mereka.

5. Analisis data dan pemahaman pengguna: dalam pengembangan sistem rekomendasi, analisis data pengguna menjadi komponen kunci. Dengan memahami pola perilaku pengguna, preferensi, dan riwayat kursus, Coursera dapat mendapatkan wawasan berharga tentang minat dan kebutuhan pengguna mereka. Analisis data juga membantu dalam mengukur efektivitas rekomendasi yang diberikan dan melakukan perbaikan yang diperlukan.

Dengan pemahaman bisnis yang kuat, pengembangan sistem rekomendasi kursus Coursera dapat fokus pada tujuan dan manfaat yang ingin dicapai. 

Dalam hal ini, meningkatkan pengalaman pengguna, retensi pengguna, penyediaan kursus yang relevan, meningkatkan konversi dan pendapatan, serta analisis data pengguna menjadi fokus utama dalam pengembangan dan evaluasi sistem rekomendasi ini.

## 3. Problem Statements

Berdasarkan business understanding di atas, proyek ini akan berusaha menjawab pertanyaan pada masalah-masalah sebagai berikut:

1. Bagaimana mengembangkan sistem rekomendasi yang dapat memberikan pengalaman pengguna yang lebih baik dalam mencari dan memilih kursus di Coursera?

2. Bagaimana meningkatkan retensi pengguna dengan menyediakan rekomendasi kursus yang relevan dan menarik bagi pengguna Coursera?

3. Bagaimana mengoptimalkan penyediaan kursus yang relevan dengan mengidentifikasi preferensi pengguna, keterampilan yang dibutuhkan dalam pasar, dan tren industri?

4. Bagaimana meningkatkan konversi pengguna menjadi peserta kursus berbayar dengan menyediakan rekomendasi yang menarik dan memberikan nilai tambah?

5. Bagaimana menganalisis data pengguna dengan efektif untuk memahami perilaku, preferensi, dan kebutuhan pengguna dalam konteks rekomendasi kursus?

Dengan memfokuskan diri pada pertanyaan-pertanyaan di atas, tujuan proyek ini akan menjadi lebih jelas dan memungkinkan pengembangan solusi yang efektif untuk memecahkan masalah yang ingin diselesaikan, yaitu meningkatkan pengalaman pengguna, retensi pengguna, penyediaan kursus yang relevan, konversi pengguna, dan analisis data pengguna.

## 4. Goals

Dalam proyek ini, kami memiliki beberapa tujuan yang ingin dicapai dalam pengembangan sistem rekomendasi kursus Coursera yakni sebagai berikut:

1. Meningkatkan pengalaman pengguna: tujuan utama adalah meningkatkan pengalaman pengguna dengan menyediakan rekomendasi kursus yang personal dan relevan. Hal ini akan membantu pengguna dalam menemukan kursus yang sesuai dengan minat, tujuan belajar, dan tingkat keahlian mereka. Pencapaian tujuan ini akan memberikan manfaat berupa kepuasan pengguna yang lebih tinggi, peningkatan keterlibatan, dan kemungkinan lebih tinggi bagi pengguna untuk menyelesaikan kursus yang mereka ikuti.

- Metrik evaluasi: 
  - Tingkat kepuasan pengguna: dilakukan survei atau pengukuran berdasarkan umpan balik pengguna terkait pengalaman mereka dalam menggunakan sistem rekomendasi. 
  - Tingkat keterlibatan pengguna: meliputi jumlah klik pada rekomendasi, waktu yang dihabiskan di halaman kursus yang direkomendasikan, dan tingkat interaksi dengan materi kursus.

2. Meningkatkan retensi pengguna: tujuan ini bertujuan untuk meningkatkan retensi pengguna dengan memberikan rekomendasi kursus yang relevan dan menarik. Dengan rekomendasi yang akurat, pengguna cenderung tetap aktif dan terlibat dalam platform Coursera.

- Metrik evaluasi: 
  - Tingkat retensi pengguna: persentase pengguna yang tetap aktif dalam platform setelah menerima rekomendasi. 
  - Tingkat keterlibatan berkelanjutan: meliputi frekuensi log masuk, partisipasi dalam forum diskusi, dan kemajuan dalam menyelesaikan kursus.

3. Penyediaan kursus yang relevan: tujuan ini melibatkan meningkatkan penyediaan kursus yang relevan dengan mengidentifikasi preferensi pengguna, keterampilan yang dibutuhkan dalam pasar, dan tren industri. Hal ini akan membantu Coursera dalam menyusun kurikulum yang sesuai dengan permintaan pengguna.

- Metrik evaluasi: 
  - Tingkat keberhasilan rekomendasi: persentase kesesuaian antara kursus yang direkomendasikan dengan preferensi pengguna.
  - Tingkat penerimaan dan partisipasi dalam kursus: meliputi jumlah pendaftaran dan partisipasi dalam kursus yang direkomendasikan.

4. Meningkatkan konversi dan pendapatan: tujuan ini berfokus pada meningkatkan konversi pengguna menjadi peserta kursus berbayar dengan memberikan rekomendasi yang menarik dan memberikan nilai tambah.

- Metrik evaluasi: 
  - Tingkat konversi pengguna: persentase pengguna yang mendaftar untuk kursus berbayar setelah menerima rekomendasi.
  - Pendapatan: meningkatnya pendapatan dari penjualan kursus berbayar yang dihasilkan melalui rekomendasi.

5. Analisis data dan pemahaman pengguna: tujuan ini melibatkan analisis data pengguna untuk memahami perilaku, preferensi, dan kebutuhan pengguna dalam konteks rekomendasi kursus.

- Metrik evaluasi: 
  - Akurasi rekomendasi: persentase kesesuaian antara rekomendasi yang diberikan dengan preferensi dan minat pengguna yang terungkap melalui analisis data.
  - Tingkat pemahaman pengguna: menggunakan survei atau pengukuran lainnya untuk mengukur pemahaman pengguna terkait relevansi dan kegunaan rekomendasi yang diberikan.

Dengan menggunakan metrik evaluasi yang tepat, kesuksesan dalam mencapai setiap tujuan dapat diukur dan dinilai secara objektif. 

Hal ini akan membantu dalam mengidentifikasi kekuatan dan kelemahan sistem rekomendasi, serta memberikan wawasan yang berguna dalam pengembangan dan peningkatan selanjutnya.

## 5. Solution Approach

Tahapan untuk menyelesaikan tujuan dari proyek ini adalah sebagai berikut:

1. Tahap EDA (Exploratory Data Analysis):
   - Mengumpulkan data: Mengumpulkan data kursus Coursera, termasuk informasi kursus seperti judul, deskripsi, topik, ulasan pengguna, dan riwayat kursus pengguna.
   - Melakukan pembersihan data: Membersihkan dan memformat data agar sesuai dengan kebutuhan analisis.
   - Analisis data: Melakukan analisis eksploratori untuk memahami distribusi data, tren, dan pola yang ada. Ini meliputi pemahaman tentang preferensi kursus yang diambil pengguna, rating kursus, dan atribut keahlian yang relevan.

2. Pendekatan Content-Based Filtering:
   - Pembangunan fitur: Menggunakan teknik pengolahan bahasa alami (NLP) untuk menganalisis deskripsi kursus dan menghasilkan vektor fitur yang merepresentasikan konten kursus.
   - Membangun model: Menggunakan algoritma seperti TF-IDF atau Word Embeddings untuk membangun model yang dapat mengukur kesamaan antara kursus berdasarkan fitur-fitur kontennya.
   - Rekomendasi kursus: Menghitung kesamaan antara kursus yang ada dengan kursus yang diminati oleh pengguna berdasarkan kursus yang telah diambil dan atribut keahlian.

3. Pendekatan *Collaborative Filtering*:
   - Matriks User-Item: Membangun matriks user-item yang merepresentasikan preferensi pengguna terhadap kursus-kursus yang ada.
   - Membangun model: Menggunakan algoritma seperti Singular Value Decomposition (SVD) atau Matrix Factorization untuk membangun model yang dapat menemukan pola kolaboratif di antara kursus dan keahlian.
   - Rekomendasi kursus: Membuat rekomendasi kursus berdasarkan peringkat prediksi yang diberikan oleh model.

4. Evaluasi Model:
   - Evaluasi Content-Based Filtering: Menggunakan metrik Precission untuk mengukur sejauh mana rekomendasi kursus yang diberikan relevan dengan preferensi pengguna.
   - Evaluasi *Collaborative Filtering*: Menggunakan metrik Root Mean Square Error (RMSE) untuk mengukur sejauh mana peringkat prediksi model mendekati peringkat yang sebenarnya.

5. Perbaikan dan Penyesuaian Model:
   - Menganalisis hasil evaluasi model dan melakukan perbaikan atau penyesuaian yang diperlukan untuk meningkatkan performa dan akurasi rekomendasi.

Dengan pendekatan ini, kita dapat memanfaatkan fitur-fitur konten kursus (Content-Based Filtering) serta pola kolaboratif antara pengguna dan kursus (*Collaborative Filtering*) untuk memberikan rekomendasi kursus yang relevan kepada pengguna. 

Evaluasi menggunakan metrik Precission dan RMSE akan memberikan wawasan tentang sejauh mana performa model dalam memberikan rekomendasi yang tepat.

## 6. Data Understanding

Kumpulan data ini dihapus dari informasi yang tersedia untuk umum di situs web Coursera pada september 2021 dan dimasukkan secara manual jika data dihapus dengan tidak benar. 

Dataset dapat diunduh di: [Coursera courses dataset 2021](https://www.Kaggle.Com/datasets/khusheekapoor/Coursera-courses-dataset-2021).

### Sample data

Tabel 6.1 Contoh Data pada Dataset
| Course Name                                               | University                               | Difficulty Level | Course Rating | Course URL                                          | Course Description                                 | Skills                                           |
|-----------------------------------------------------------|------------------------------------------|------------------|---------------|-----------------------------------------------------|----------------------------------------------------|--------------------------------------------------|
| Write A Feature Length Screenplay For Film Or ...          | Michigan State University                | Beginner         | 4.8           | [Course URL](https://www.coursera.org/learn/write-a-feature...)              | Write a Full Length Feature Film Script In th...   | Drama Comedy peering screenwriting film D...     |
| Business Strategy: Business Model Canvas Analy...          | Coursera Project Network                 | Beginner         | 4.8           | [Course URL](https://www.coursera.org/learn/canvas-analysis...)              | By the end of this guided project, you will be... | Finance business plan persona (user experien... |
| Silicon Thin Film Solar Cells                              | �cole Polytechnique                      | Advanced         | 4.1           | [Course URL](https://www.coursera.org/learn/silicon-thin-fi...)              | This course consists of a general presentation... | chemistry physics Solar Energy film lambda... |
| Finance for Managers                                        | IESE Business School                     | Intermediate     | 4.8           | [Course URL](https://www.coursera.org/learn/operational-fin...)              | When it comes to numbers, there is always more... | accounts receivable dupont analysis analysis... |
| Retrieve Data using Single-Table SQL Queries                | Coursera Project Network                 | Beginner         | 4.6           | [Course URL](https://www.coursera.org/learn/single-table-sq...)              | In this course you�ll learn how to effectively... | Data Analysis select (sql) database manageme... |
| Building Test Automation Framework using Selen...          | Coursera Project Network                 | Beginner         | 4.7           | [Course URL](https://www.coursera.org/learn/building-test-a...)              | Selenium is one of the most widely used functi... | maintenance test case test automation scree... |
| Doing Business in China Capstone                            | The Chinese University of Hong Kong       | Advanced         | 3.3           | [Course URL](https://www.coursera.org/learn/doing-business-...)              | Doing Business in China Capstone enables you t... | marketing plan Planning Marketing consumpti... |
| Programming Languages, Part A                               | University of Washington                 | Intermediate     | 4.9           | [Course URL](https://www.coursera.org/learn/programming-lan...)              | This course is an introduction to the basic co... | inference ml (programming language) higher-o... |
| The Roles and Responsibilities of Nonprofit Bo...          | The State University of New York          | Intermediate     | 4.3           | [Course URL](https://www.coursera.org/learn/nonprofit-gov-2)                | This course provides a more in-depth look at t... | Planning Peer Review fundraising strategic ... |
| Business Russian Communication. Part 3                     | Saint Petersburg State University         | Intermediate     | Not Calibrated | [Course URL](https://www.coursera.org/learn/business-russia...)              | Russian is considered to be one of the most di... | Russian market (economics) tax exemption co... |

### Variabel-variabel pada dataset Coursera Courses 2021 adalah sebagai berikut:

- Course Name: Nama kursus.
- University: Universitas yang menyelenggarakan kursus.
- Difficulty Level: Tingkat kesulitan kursus (Beginner, Intermediate, Advanced).
- Course Rating: Nilai atau peringkat kursus oleh pengguna.
- Course URL: Tautan URL kursus di Coursera.
- Course Description: Deskripsi singkat tentang kursus.
- Skills: Keterampilan atau topik yang terkait dengan kursus tersebut.

Tabel 6.2 Tipe Data Tiap Kolom pada Dataset
```sh
RangeIndex: 3522 entries, 0 to 3521
Data columns (total 7 columns):
 #   Column              Non-Null Count  Dtype 
---  ------              --------------  ----- 
 0   Course Name         3522 non-null   object
 1   University          3522 non-null   object
 2   Difficulty Level    3522 non-null   object
 3   Course Rating       3522 non-null   object
 4   Course URL          3522 non-null   object
 5   Course Description  3522 non-null   object
 6   Skills              3522 non-null   object
dtypes: object(7)
```

### Pendalaman Data Understanding


### Visualisasi proses Data Understanding


## 7. Data Preparation

Berikut adalah tahapan-tahapan yang dilakukan:

1. Drop outliers menggunakan IQR: Mengidentifikasi dan menghapus *outlier* pada dataset menggunakan metode IQR (Interquartile Range).
2. Mengatasi missing value: Melakukan penanganan terhadap nilai yang hilang pada dataset, seperti menghapus baris atau mengisi nilai yang hilang dengan metode tertentu, seperti mean atau median.
3. Mengambil kolom yang diperlukan dan merubah nama kolom: Memilih kolom-kolom yang relevan untuk analisis dan memberikan nama baru jika diperlukan.
4. Exclude rating yang ingin dihapus dari dataset: Menghapus data dengan rating tertentu yang ingin dikecualikan dari analisis.
5. Reset index dataframe untuk menghindari error: Mereset indeks dataframe setelah melakukan operasi penghapusan atau pemrosesan data agar indeks kembali terurut secara berurutan.
6. Convert "rating" column to int64 data type: Mengubah tipe data kolom "rating" menjadi tipe data int64 untuk mempermudah analisis numerik.
7. Mendapatkan list unik kolom kursus dan keahlian: Mengidentifikasi dan mendapatkan daftar unik kolom "courseName" dan "skills" dalam dataset.

## 8. Modeling

Pada proyek ini diterapkan 2 tipe model, yaitu *Content Based Filtering* dan *Collaborative Based Filtering*.

### *Content Based Filtering*
*Content Based Filtering* adalah pendekatan dalam sistem rekomendasi yang mengandalkan analisis konten dari item yang direkomendasikan. 

Dalam konteks sistem rekomendasi kursus Coursera, pendekatan ini akan menganalisis fitur-fitur konten dari kursus, seperti deskripsi kursus, topik, rating, atau keterampilan yang terkait, untuk memberikan rekomendasi yang relevan kepada pengguna.

Kelebihan *Content Based Filtering*:
1. Personalisasi: Pendekatan *Content Based Filtering* memungkinkan personalisasi yang tinggi, karena rekomendasi didasarkan pada preferensi pengguna yang diungkapkan melalui analisis konten kursus.
2. Tidak tergantung pada data pengguna lain: Pendekatan ini tidak memerlukan informasi tentang preferensi pengguna lain, sehingga tidak bergantung pada data kolaboratif atau historis dari pengguna lainnya.
3. Memperhitungkan kepentingan unik pengguna: Pendekatan ini memperhitungkan preferensi pengguna yang spesifik dan tidak terpengaruh oleh tren atau preferensi umum.

Kekurangan *Content Based Filtering*:
1. Terbatas pada fitur yang diamati: Pendekatan ini terbatas pada fitur-fitur yang diamati dan dianalisis dalam konten kursus. Rekomendasi mungkin kurang beragam jika tidak ada fitur yang signifikan dalam analisis konten yang dapat membedakan kursus secara signifikan.
2. Tidak memperhitungkan preferensi baru: Pendekatan ini tidak secara otomatis menyesuaikan dengan perubahan preferensi pengguna. Jika preferensi pengguna berubah atau berkembang, rekomendasi mungkin tetap berfokus pada preferensi yang lebih lama.

Teknik Perhitungan Similarity:
1. *Cosine Similarity*: *Cosine Similarity* mengukur kesamaan antara dua vektor dengan menghitung kosinus sudut antara vektor-vektor tersebut. Dalam konteks *Content Based Filtering*, kita dapat menggunakan *Cosine Similarity* untuk mengukur kesamaan antara vektor representasi fitur kursus berdasarkan deskripsi, topik, atau keterampilan. Nilai *Cosine Similarity* berkisar antara -1 hingga 1, di mana nilai 1 menunjukkan kesamaan yang sempurna dan nilai -1 menunjukkan perbedaan yang sempurna.

2. **Euclidean Distance**: **Euclidean Distance** mengukur jarak antara dua titik dalam ruang Euclidean. Dalam konteks *Content Based Filtering*, kita dapat menggunakan **Euclidean Distance** untuk mengukur jarak antara vektor representasi fitur kursus. Semakin kecil nilai **Euclidean Distance**, semakin mirip kedua kursus dalam hal fitur-fitur yang diamati.

Kedua teknik perhitungan *similarity* tersebut digunakan untuk membandingkan kesamaan antara kursus-kursus dalam sistem rekomendasi. 

### Tahapan yang dilakukan dengan pendekatan *Content Based Filtering*
Selama pendekatan ini, proses modeling dilakukan berdasar urutan sebagai berikut ini:

1. *TF-IDF Vectorizer*: Tahap ini melibatkan penggunaan TF-IDF (Term Frequency-Inverse Document Frequency) Vectorizer untuk mengubah teks pada deskripsi kursus menjadi representasi numerik. TF-IDF mengukur pentingnya suatu kata dalam dokumen berdasarkan frekuensi kemunculan kata tersebut dalam dokumen dan inversi frekuensi kemunculan kata tersebut dalam seluruh koleksi dokumen. *TF-IDF Vectorizer* menghasilkan vektor fitur yang merepresentasikan konten kursus.

2. *Cosine Similarity*: Setelah mendapatkan vektor fitur menggunakan *TF-IDF Vectorizer*, tahap selanjutnya adalah menghitung kesamaan antara kursus menggunakan metode *Cosine Similarity*. *Cosine Similarity* mengukur kesamaan arah antara dua vektor dalam ruang vektor. Pada konteks Content Based Filtering, *Cosine Similarity* digunakan untuk mengukur kesamaan antara vektor fitur kursus berdasarkan deskripsi, topik, atau keterampilan yang terkait. Semakin tinggi nilai *Cosine Similarity*, semakin mirip kedua kursus dalam hal fitur-fitur yang diamati.

Tabel 8.1 Hasil Perhitungan Cosine Similarity pada Matrix TF-IDF

```sh
array([[1.        , 0.        , 0.15356638, ..., 0.        , 0.        ,
        0.        ],
       [0.        , 1.        , 0.        , ..., 0.15163383, 0.        ,
        0.0421248 ],
       [0.15356638, 0.        , 1.        , ..., 0.        , 0.        ,
        0.        ],
       ...,
       [0.        , 0.15163383, 0.        , ..., 1.        , 0.        ,
        0.        ],
       [0.        , 0.        , 0.        , ..., 0.        , 1.        ,
        0.        ],
       [0.        , 0.0421248 , 0.        , ..., 0.        , 0.        ,
        1.        ]])
```

Tabel 8.2 Hasil Similarity Matrix pada Setiap Course

| courseName                                                                    |   Statistical Inference |   Agile Analytics |   Planning a Patient Safety or Quality Improvement Project (Patient Safety III) |   Data Structures and Design Patterns for Game Developers |   Getting Started with Linux Terminal |
|:------------------------------------------------------------------------------|------------------------:|------------------:|--------------------------------------------------------------------------------:|----------------------------------------------------------:|--------------------------------------:|
| Mathematical Foundations for Cryptography                                     |                       0 |          0        |                                                                               0 |                                                 0.0547025 |                             0         |
| Water in the Western United States                                            |                       0 |          0        |                                                                               0 |                                                 0         |                             0         |
| Internet of Things: How did we get here?                                      |                       0 |          0        |                                                                               0 |                                                 0         |                             0         |
| COVID-19: What You Need to Know (CME Eligible)                                |                       0 |          0        |                                                                               0 |                                                 0         |                             0         |
| Toledo: Deciphering Secrets of Medieval Spain                                 |                       0 |          0        |                                                                               0 |                                                 0         |                             0         |
| Applying Data Analytics in Finance                                            |                       0 |          0.273049 |                                                                               0 |                                                 0.0685219 |                             0         |
| Object-Oriented Design                                                        |                       0 |          0        |                                                                               0 |                                                 0.14411   |                             0         |
| Multiplatform Mobile App Development with Web Technologies: Ionic and Cordova |                       0 |          0        |                                                                               0 |                                                 0.0177147 |                             0.0366682 |
| Applying Investment Decision Rules for Startups                               |                       0 |          0        |                                                                               0 |                                                 0.0378254 |                             0         |
| Be a Leader, Develop a Leader                                                 |                       0 |          0        |                                                                               0 |                                                 0         |                             0         |


3. *Euclidean Distance*: Selain *Cosine Similarity*, tahap Content Based Filtering juga dapat menggunakan *Euclidean Distance* untuk mengukur jarak antara vektor fitur kursus. *Euclidean Distance* menghitung jarak antara dua titik dalam ruang Euclidean. Dalam konteks *Content Based Filtering*, *Euclidean Distance* digunakan untuk mengukur jarak antara vektor fitur kursus. Semakin kecil nilai *Euclidean Distance*, semakin mirip kedua kursus dalam hal fitur-fitur yang diamati.

Tabel 8.3 Hasil Perghitungan Euclidean Distance pada Matrix TF-IDF

| courseName                                                                    |   Teach English Now! Capstone Project 2 |   Introduction to Particle Accelerators (NPAP MOOC) |   Engineering Practices for Building Quality Software |   Anti-Racism I |   Best Practices for iOS User Interface Design |
|:------------------------------------------------------------------------------|----------------------------------------:|----------------------------------------------------:|------------------------------------------------------:|----------------:|-----------------------------------------------:|
| Introduction to Java Programming: Java Fundamental Concepts                   |                                 1.41421 |                                             1.34813 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Siamese Network with Triplet Loss in Keras                                    |                                 1.41421 |                                             1.41421 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Docker Essentials & Building a Containerized Web Application                  |                                 1.41421 |                                             1.41421 |                                               1.32744 |         1.41421 |                                        1.41421 |
| What does it mean to identify as Transgender or Gender Non-Conforming (TGNC)? |                                 1.41421 |                                             1.39635 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Foundations of mining non-structured medical data                             |                                 1.41421 |                                             1.41421 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Guitar Chord Voicings: Playing Up The Neck                                    |                                 1.41421 |                                             1.41421 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Simulation and modeling of natural processes                                  |                                 1.41421 |                                             1.41421 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Global Statistics - Composite Indices for International Comparisons           |                                 1.41421 |                                             1.41421 |                                               1.38613 |         1.41421 |                                        1.3911  |
| Electrodynamics: An Introduction                                              |                                 1.41421 |                                             1.35176 |                                               1.41421 |         1.41421 |                                        1.41421 |
| Law in the Time of COVID-19: A Northwestern Teach-Out                         |                                 1.41421 |                                             1.41421 |                                               1.41421 |         1.41421 |                                        1.41421 |

Tahapan-tahapan di atas merupakan bagian dari proses *Content Based Filtering* yang bertujuan untuk menganalisis dan membandingkan konten kursus berdasarkan vektor fitur yang dihasilkan menggunakan *TF-IDF Vectorizer*. 

Penggunaan metode *Cosine Similarity* dan *Euclidean Distance* memungkinkan untuk mengukur kesamaan atau perbedaan antara kursus-kursus dalam hal konten yang diamati.

*Cosine Similarity* mengukur kesamaan arah antara vektor fitur, sedangkan *Euclidean Distance* mengukur jarak antara vektor fitur. 

Pilihan antara kedua metode ini tergantung pada konteks dan tujuan aplikasi yang lebih spesifik.

### *Collaborative Filtering*

*Collaborative Filtering* adalah pendekatan dalam sistem rekomendasi yang mengandalkan informasi dari pengguna-pengguna lain dalam menghasilkan rekomendasi. 

Pendekatan ini mencoba untuk menemukan pola kolaboratif antara pengguna dan item yang direkomendasikan berdasarkan interaksi atau preferensi mereka.

Ada dua jenis utama dalam *Collaborative Filtering*:
1. *User-Based Collaborative Filtering*: Pendekatan ini mencari kesamaan antara pengguna berdasarkan riwayat preferensi atau interaksi mereka dengan item. Jika dua pengguna memiliki pola preferensi yang serupa, kemungkinan besar mereka akan memiliki preferensi yang sama pada item yang belum mereka eksplorasi. Rekomendasi diberikan berdasarkan preferensi pengguna yang serupa.

2. *Item-Based Collaborative Filtering*: Pendekatan ini mencari kesamaan antara item berdasarkan riwayat preferensi atau interaksi pengguna dengan item tersebut. Jika dua item memiliki pola preferensi yang serupa dari pengguna yang sama, kemungkinan besar pengguna yang memiliki preferensi pada item pertama juga akan memiliki preferensi pada item kedua. Rekomendasi diberikan berdasarkan kesamaan antara item yang ada dengan item yang diminati oleh pengguna.

Kelebihan *Collaborative Filtering*:
1. *Discovery of Serendipity*: *Collaborative Filtering* dapat menghasilkan rekomendasi yang tidak terduga atau serendipitous. Pendekatan ini memungkinkan pengguna menemukan item baru yang mungkin tidak mereka eksplorasi sebelumnya.
2. Tidak tergantung pada fitur konten: Pendekatan ini tidak memerlukan informasi tentang fitur konten dari item yang direkomendasikan. Ini membuatnya berguna dalam situasi di mana informasi fitur tidak tersedia atau sulit untuk dianalisis.

Kekurangan *Collaborative Filtering*:
1. *Cold Start Problem*: *Collaborative Filtering* memiliki tantangan saat menghadapi pengguna baru atau item baru. Jika tidak ada riwayat preferensi atau interaksi yang tersedia, sulit untuk memberikan rekomendasi yang relevan.
2. *Scalability*: Pendekatan ini dapat mengalami kesulitan dalam skala yang besar. Semakin banyak pengguna dan item yang ada, semakin sulit untuk menghasilkan rekomendasi yang akurat secara efisien.

Pendekatan *Collaborative Filtering* memanfaatkan informasi dari pengguna-pengguna lain untuk memberikan rekomendasi. 

Dalam praktiknya, seringkali pendekatan ini dikombinasikan dengan *Content Based Filtering* untuk meningkatkan performa dan relevansi rekomendasi yang dihasilkan.

### Training Model

Pada tahapan training model, proses yang dilakukan adalah sebagai berikut: 

1. Splitting Data: Bagi data menjadi set pelatihan (train set) dan set pengujian (test set). Set pelatihan akan digunakan untuk melatih model, sedangkan set pengujian akan digunakan untuk menguji performa model secara independen. Perbandingan umum adalah sekitar 80% data untuk set pelatihan dan 20% untuk set pengujian.

2. Model Architecture: Tentukan arsitektur model RecommenderNet yang akan digunakan. RecommenderNet adalah model yang dirancang khusus untuk tugas rekomendasi dan memanfaatkan teknik deep learning untuk menghasilkan rekomendasi yang personal dan akurat. Arsitektur model RecommenderNet harus disesuaikan dengan masalah spesifik dan karakteristik data.

3. Data Preparation for Training: Lakukan pra-pemrosesan pada data pelatihan. Ini melibatkan konversi variabel kategori menjadi representasi numerik yang sesuai, normalisasi data jika diperlukan, dan pembuatan data dalam bentuk yang cocok untuk pelatihan model RecommenderNet.

4. Training Model: Latih model RecommenderNet menggunakan set pelatihan. Selama proses pelatihan, model akan mempelajari pola-pola dan relasi antara pengguna dan kursus untuk menghasilkan rekomendasi yang tepat. Proses ini melibatkan optimisasi parameter melalui iterasi berulang untuk mengurangi kesalahan dan meningkatkan kinerja model.

![grafik model metrik](https://github.com/nikofebrianur/Machine-Learning-Terapan/assets/42314371/409c78b1-822a-487e-be01-ff6f8a1fa3b0)

####### Gambar 8.1 Grafik Visualisasi Metrik Model Training 

5. Evaluasi Model: Evaluasi performa model menggunakan set pengujian yang telah dipisahkan sebelumnya. Hitung metrik evaluasi yang sesuai, seperti akurasi, presisi, atau recall, untuk mengukur sejauh mana model mampu memberikan rekomendasi yang relevan dan sesuai dengan preferensi pengguna.

Dalam tahapan ini, data dipisahkan menjadi set pelatihan dan set pengujian untuk memastikan evaluasi yang objektif terhadap performa model. 

Set pelatihan digunakan untuk melatih model, sedangkan set pengujian digunakan untuk menguji performa model secara independen dan mengukur sejauh mana model dapat menggeneralisasi dengan baik ke data yang belum pernah dilihat sebelumnya.
 
## 9. Evaluation


Tabel 9.2 Hasil Rekomendasi dengan Cosine Similarity

|    | courseName                                                          |   rating | skills                                                                                                                                                                                                                                                             |
|---:|:--------------------------------------------------------------------|---------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Cloud Systems Software                                              | 1        | orchestration (computing)  i/o virtualization  health  architecture neutral distribution format  Cloud-Based Integration  Software Framework  System Programming  SQL  Cloud Engineering  multitier architecture information-technology cloud-computing            |
|  1 | Software Architecture                                               | 0.481082 | architecture tradeoff analysis method  design pattern  software  non-functional requirement  unified modeling language  pipeline (software)  Software Architecture  capgemini  software design  architecture computer-science software-development                 |
|  2 | Agile Software Development                                          | 0.475195 | scrum (software development)  agile manifesto  user story  extreme programming  Software Engineering  software  agile management  Leadership and Management  Agile Software Development  Computer Programming computer-science software-development                |
|  3 | Introduction to Software Testing                                    | 0.42788  | software  test double  test plan  Software Testing  test automation  mock object  functional testing  Software Engineering  unit testing  code coverage computer-science software-development                                                                      |
|  4 | Software Design as an Element of the Software Development Lifecycle | 0.422111 | Software Architecture  software design  security  Software Testing  Software Engineering  interfaces  low-level design  software  specification (technical standard)  software development process computer-science software-development                           |
|  5 | Cloud Security Basics                                               | 0.420811 | separation of duties  protocol stack  cloud computing security  trust boundary  attack surface  cryptographic protocol  security  Network Security  Cloud Computing  public key certificate information-technology cloud-computing                                 |
|  6 | International Security Management                                   | 0.411086 | Leadership and Management  security management  crime  Risk Management  terrorism  security  Risk  Intelligence Analysis  safety  risk assessment social-sciences governance-and-society                                                                           |
|  7 | G Suite Security                                                    | 0.403576 | password  user (computing)  Software Security  security  relative change and difference  Cloud Computing  digital signature  multi-factor authentication  javascript syntax  single sign-on computer-science computer-security-and-networks                        |
|  8 | Software Product Management Capstone                                | 0.401497 | Product Management  Leadership and Management  project  scrum (software development)  Project Management  software  software product management  Software Engineering  software project management  Agile Software Development computer-science design-and-product |
|  9 | Introduction to Software Product Management                         | 0.397504 | project  Software Engineering  Product Management  Leadership and Management  software  Agile Software Development  agile management  software product management  Planning  agile manifesto computer-science design-and-product                                   |

Tabel 9.2 Hasil Rekomendasi dengan Euclidean Distance

|    | courseName                                                          |   rating | skills                                                                                                                                                                                                                                                             |
|---:|:--------------------------------------------------------------------|---------:|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|  0 | Cloud Systems Software                                              |  0       | orchestration (computing)  i/o virtualization  health  architecture neutral distribution format  Cloud-Based Integration  Software Framework  System Programming  SQL  Cloud Engineering  multitier architecture information-technology cloud-computing            |
|  1 | Software Architecture                                               |  1.01874 | architecture tradeoff analysis method  design pattern  software  non-functional requirement  unified modeling language  pipeline (software)  Software Architecture  capgemini  software design  architecture computer-science software-development                 |
|  2 | Agile Software Development                                          |  1.0245  | scrum (software development)  agile manifesto  user story  extreme programming  Software Engineering  software  agile management  Leadership and Management  Agile Software Development  Computer Programming computer-science software-development                |
|  3 | Introduction to Software Testing                                    |  1.06969 | software  test double  test plan  Software Testing  test automation  mock object  functional testing  Software Engineering  unit testing  code coverage computer-science software-development                                                                      |
|  4 | Software Design as an Element of the Software Development Lifecycle |  1.07507 | Software Architecture  software design  security  Software Testing  Software Engineering  interfaces  low-level design  software  specification (technical standard)  software development process computer-science software-development                           |
|  5 | Cloud Security Basics                                               |  1.07628 | separation of duties  protocol stack  cloud computing security  trust boundary  attack surface  cryptographic protocol  security  Network Security  Cloud Computing  public key certificate information-technology cloud-computing                                 |
|  6 | International Security Management                                   |  1.08528 | Leadership and Management  security management  crime  Risk Management  terrorism  security  Risk  Intelligence Analysis  safety  risk assessment social-sciences governance-and-society                                                                           |
|  7 | G Suite Security                                                    |  1.09218 | password  user (computing)  Software Security  security  relative change and difference  Cloud Computing  digital signature  multi-factor authentication  javascript syntax  single sign-on computer-science computer-security-and-networks                        |
|  8 | Software Product Management Capstone                                |  1.09408 | Product Management  Leadership and Management  project  scrum (software development)  Project Management  software  software product management  Software Engineering  software project management  Agile Software Development computer-science design-and-product |
|  9 | Hardware Security                                                   |  1.09772 | graph coloring  Hardware Design  trusted platform module  vulnerability (computing)  security  modular exponentiation  System Security  Cryptography  Systems Design  side-channel attack computer-science computer-security-and-networks                          |

## 10. Kesimpulan 

## References

Chen M, Wang X, Wang J, et al., "Factors Affecting College Students’ Continuous Intention to Use Online Course Platform," *SN Computer Science*, 2021.

S. Inder, "Factors Influencing Student Engagement for Online Courses: A Confirmatory Factor Analysis," *Contemporary Educational Technology*, 2022.

P. Bawa, "Retention in Online Courses: Exploring Issues and Solutions—A Literature Review," *SAGE Open*, 2016.

M. G. Gómez-Zermeño, "Massive open online courses as a digital learning strategy of education for sustainable development," *Journal of Sustainable Development of Energy, Water and Environment Systems*, 8, 577–589, 2020.

T. Soffer, A. Cohen, "Students’ engagement characteristics predict success and completion of online courses," *Journal of Computer Assisted Learning*, 35, 378–389, 2019.
