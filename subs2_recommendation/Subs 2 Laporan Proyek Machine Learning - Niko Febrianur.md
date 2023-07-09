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

## 5. Solution Statements

## 6. Data Understanding

Kumpulan data ini dihapus dari informasi yang tersedia untuk umum di situs web Coursera pada september 2021 dan dimasukkan secara manual jika data dihapus dengan tidak benar. 

Dataset dapat diunduh di: [Coursera courses dataset 2021](https://www.Kaggle.Com/datasets/khusheekapoor/Coursera-courses-dataset-2021).

### Sample data


### Variabel-variabel pada dataset Coursera Courses 2021 adalah sebagai berikut:


### Pendalaman Data Understanding


### Visualisasi proses Data Understanding


## 7. Data Preparation

## 8. Modeling

### Tahapan yang dilakukan

### Kelebihan dan kekurangan
 
## 9. Evaluation

## 10. Kesimpulan 

## References
Chen M, Wang X, Wang J, et al., "Factors Affecting College Students’ Continuous Intention to Use Online Course Platform," *SN Computer Science*, 2021.
S. Inder, "Factors Influencing Student Engagement for Online Courses: A Confirmatory Factor Analysis," *Contemporary Educational Technology*, 2022.
P. Bawa, "Retention in Online Courses: Exploring Issues and Solutions—A Literature Review," *SAGE Open*, 2016.
