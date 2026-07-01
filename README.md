# cluster-sampling-sleep-study
A cluster sampling project to estimate the average sleep duration and sleep quality among Statistics students.
# 🌙 Sleep Matters: Estimasi Rata-Rata Durasi dan Kualitas Tidur Mahasiswa Statistika Universitas Mataram Menggunakan Cluster Sampling

![Language](https://img.shields.io/badge/Language-R-blue)
![Method](https://img.shields.io/badge/Method-Cluster%20Sampling-green)
![Analysis](https://img.shields.io/badge/Analysis-Survey-orange)

## 📖 Project Description

Penelitian ini bertujuan untuk mengestimasi rata-rata durasi tidur dan kualitas tidur mahasiswa Program Studi Statistika Universitas Mataram menggunakan metode **Cluster Sampling** berdasarkan angkatan.

Data penelitian diperoleh melalui penyebaran kuesioner kepada mahasiswa Statistika yang dipilih sebagai sampel dari cluster angkatan. Variabel yang diamati meliputi durasi tidur, pola atau kebiasaan tidur, kualitas tidur, serta dampak tidur terhadap aktivitas akademik.

Analisis dilakukan menggunakan pendekatan statistika survei untuk memperoleh estimasi rata-rata, standar error (SE), interval kepercayaan 95%, serta ukuran presisi estimasi. Hasil penelitian diharapkan dapat memberikan gambaran mengenai kondisi tidur mahasiswa Statistika sekaligus menjadi bahan evaluasi dalam meningkatkan kesehatan dan produktivitas akademik mahasiswa.

## 🎯 Objectives

- Mengestimasi rata-rata durasi tidur mahasiswa Statistika Universitas Mataram.
- Mendeskripsikan kualitas tidur mahasiswa berdasarkan hasil kuesioner.
- Mendeskripsikan pola atau kebiasaan tidur mahasiswa.
- Mengidentifikasi dampak pola tidur terhadap aktivitas akademik mahasiswa.
- Menyajikan hasil estimasi menggunakan metode Cluster Sampling berdasarkan angkatan.

## 📂 Struktur Repository

```text
Sleep-Matters/
│
├── README.md
├── Executive_Summary.pdf
│
├── data/
│   └── Data_Mentah.xlsx
│
├── randomisasi/
│   └── Hasil_Randomisasi_Cluster.xlsx
│
├── kuesioner/
│   └── Kuesioner_Tidur_Mahasiswa.pdf
│
├── validitas-reliabilitas/
│   ├── Data_Uji_Validitas.xlsx
│   └── Hasil_Uji_Validitas_Reliabilitas.pdf
│
├── script/
│   ├── Uji_Validitas_Reliabilitas.R
│   └── Analisis_Cluster_Sampling.R
│
└── hasil/
    ├── Output_Analisis.pdf
    ├── Tabel_Hasil_Estimasi.pdf
    └── Visualisasi_Hasil.pdf
```

---

### Penjelasan Folder

- **README.md** : Dokumentasi lengkap penelitian.
- **Executive_Summary.pdf** : Ringkasan penelitian dan hasil utama.
- **data/** : Berisi data mentah hasil pengisian kuesioner.
- **randomisasi/** : Berisi hasil proses pemilihan sampel menggunakan Cluster Sampling berdasarkan angkatan.
- **kuesioner/** : Berisi instrumen penelitian yang digunakan dalam survei.
- **validitas-reliabilitas/** : Berisi data serta hasil uji validitas dan reliabilitas instrumen.
- **script/** : Berisi seluruh sintaks analisis menggunakan software R.
- **hasil/** : Berisi output analisis, tabel estimasi, dan visualisasi hasil penelitian.

## 📚 Background

Tidur merupakan salah satu kebutuhan fisiologis yang sangat penting bagi mahasiswa karena berperan dalam menjaga kesehatan fisik, fungsi kognitif, serta kemampuan belajar. Durasi dan kualitas tidur yang baik dapat membantu meningkatkan konsentrasi, daya ingat, serta produktivitas akademik. Sebaliknya, pola tidur yang kurang baik dapat menyebabkan rasa kantuk di siang hari, menurunkan fokus belajar, hingga berdampak pada performa akademik mahasiswa.

Mahasiswa Statistika sering kali dihadapkan pada berbagai tuntutan akademik, seperti penyelesaian tugas, praktikum, proyek analisis data, hingga persiapan ujian. Aktivitas tersebut berpotensi memengaruhi kebiasaan tidur, baik dari segi durasi maupun kualitas tidur. Oleh karena itu, diperlukan informasi yang dapat menggambarkan kondisi tidur mahasiswa secara objektif melalui pendekatan statistika.

Penelitian ini menggunakan metode **Cluster Sampling** dengan **angkatan sebagai cluster** untuk memperoleh sampel mahasiswa Program Studi Statistika Universitas Mataram. Pendekatan ini dipilih karena lebih efisien dalam proses pengambilan sampel ketika populasi telah terbagi ke dalam kelompok-kelompok yang jelas, yaitu berdasarkan angkatan.

Melalui penelitian ini diharapkan diperoleh estimasi rata-rata durasi tidur serta gambaran mengenai kualitas tidur mahasiswa Statistika Universitas Mataram. Hasil penelitian diharapkan dapat menjadi informasi awal dalam memahami kondisi pola tidur mahasiswa sekaligus menjadi bahan pertimbangan dalam upaya meningkatkan kesehatan dan produktivitas akademik.

## 🎯 Research Objectives

Penelitian ini bertujuan untuk mengestimasi rata-rata durasi tidur dan menggambarkan kualitas tidur mahasiswa Program Studi Statistika Universitas Mataram menggunakan metode **Cluster Sampling**. Secara khusus, penelitian ini bertujuan untuk:

- Mengestimasi rata-rata durasi tidur mahasiswa Program Studi Statistika Universitas Mataram.
- Mendeskripsikan pola dan kualitas tidur mahasiswa berdasarkan hasil kuesioner.
- Mendeskripsikan dampak pola tidur terhadap aktivitas akademik mahasiswa.
- Menyajikan hasil estimasi beserta ukuran ketelitiannya menggunakan pendekatan statistika survei.

## 🔬 Research Methodology

Penelitian ini menggunakan pendekatan **kuantitatif** dengan metode survei. Pengumpulan data dilakukan menggunakan kuesioner yang disebarkan kepada mahasiswa Program Studi Statistika Universitas Mataram.

### Population

Populasi penelitian adalah seluruh mahasiswa Program Studi Statistika Universitas Mataram angkatan **2023, 2024, dan 2025**.

### Sampling Technique

Teknik sampling yang digunakan adalah **Cluster Sampling** dengan **angkatan sebagai cluster**. Pemilihan cluster dilakukan secara acak (*simple random selection*) menggunakan Microsoft Excel. Setelah cluster terpilih, responden pada cluster tersebut dijadikan sampel penelitian.

### Data Collection

Data dikumpulkan menggunakan kuesioner yang terdiri atas pertanyaan mengenai:

- Durasi tidur
- Pola tidur
- Kualitas tidur
- Dampak tidur terhadap aktivitas akademik

Sebelum analisis utama dilakukan, instrumen penelitian diuji menggunakan **uji validitas** dan **uji reliabilitas** terhadap sebagian responden untuk memastikan bahwa setiap butir pertanyaan mampu mengukur variabel penelitian secara konsisten.

### Data Analysis

Data yang telah memenuhi uji validitas dan reliabilitas kemudian dianalisis menggunakan pendekatan statistika survei. Analisis meliputi:

- Data cleaning
- Statistik deskriptif
- Estimasi rata-rata durasi tidur
- Analisis deskriptif terhadap pola tidur, kualitas tidur, dan dampak tidur terhadap aktivitas akademik
- Perhitungan Standard Error (SE)
- Perhitungan Interval Kepercayaan 95%
- Interpretasi hasil penelitian

## 📊 Analysis Workflow

Analisis data pada penelitian ini dilakukan secara bertahap sesuai dengan tahapan penelitian survei menggunakan metode **Cluster Sampling**.

```text
Start
  │
  ▼
Menentukan Populasi Penelitian
(Mahasiswa Statistika Angkatan 2023–2025)
  │
  ▼
Menentukan Cluster
(Angkatan sebagai cluster)
  │
  ▼
Randomisasi Cluster
(Microsoft Excel)
  │
  ▼
Penyebaran Kuesioner
  │
  ▼
Pengumpulan Data Responden
  │
  ▼
Uji Validitas dan Reliabilitas
(±15 Responden)
  │
  ▼
Cleaning Data
  │
  ▼
Analisis Data
  ├── Statistik Deskriptif
  ├── Estimasi Rata-rata Durasi Tidur
  ├── Analisis Pola Tidur
  ├── Analisis Kualitas Tidur
  ├── Analisis Dampak Tidur terhadap Aktivitas Akademik
  ├── Standard Error (SE)
  └── Confidence Interval (95%)
  │
  ▼
Interpretasi Hasil
  │
  ▼
Kesimpulan dan Rekomendasi
  │
  ▼
Finish
```
## 📈 Statistical Analysis

Data yang telah memenuhi uji validitas dan reliabilitas dianalisis menggunakan pendekatan **statistika deskriptif** dan **estimasi parameter**.

Analisis yang dilakukan meliputi:

1. **Statistik deskriptif**
   - Karakteristik responden.
   - Distribusi frekuensi dan persentase.
   - Rata-rata skor setiap indikator.

2. **Estimasi rata-rata**
   - Mengestimasi rata-rata durasi tidur mahasiswa.
   - Menghitung Standard Error (SE).
   - Menghitung Interval Kepercayaan 95%.

3. **Analisis indikator**
   - Pola tidur.
   - Kualitas tidur.
   - Dampak tidur terhadap aktivitas akademik.

Hasil analisis kemudian diinterpretasikan untuk memberikan gambaran mengenai kondisi tidur mahasiswa Program Studi Statistika Universitas Mataram.

# 📊 Analisis Data

Analisis data pada penelitian ini dilakukan menggunakan **bahasa pemrograman R** melalui beberapa tahapan, mulai dari proses **import data**, **uji validitas**, **uji reliabilitas**, **pengolahan data**, **analisis statistik deskriptif**, hingga **estimasi rata-rata durasi tidur** serta **interpretasi hasil penelitian**.

Seluruh tahapan analisis disusun berdasarkan metode **Cluster Sampling**, di mana data penelitian diperoleh dari kelas yang terpilih melalui proses randomisasi, kemudian dilakukan penyebaran kuesioner kepada responden yang memenuhi kriteria penelitian.
Adapun alur analisis data dalam penelitian ini adalah sebagai berikut:

1. Import Data
2. Uji Validitas Instrumen
3. Uji Reliabilitas Instrumen
4. Pengolahan Data Penelitian
5. Analisis Statistik Deskriptif
6. Estimasi Rata-rata Durasi Tidur
7. Analisis Variabel Durasi Tidur
8. Analisis Variabel Pola/Kebiasaan Tidur
9. Analisis Variabel Kualitas Tidur
10. Analisis Variabel Dampak Tidur terhadap Aktivitas Akademik
11. Visualisasi Hasil Analisis
12. Kesimpulan

# 1. Import Data

## Tujuan

Tahap ini bertujuan untuk mengimpor data hasil survei ke dalam R, memilih variabel penelitian, serta memastikan seluruh data siap digunakan untuk proses analisis berikutnya.

Data yang diimpor merupakan hasil penyebaran kuesioner kepada responden yang diperoleh melalui teknik **Cluster Sampling**.

---
## Sintaks

```r
#========================================================
# 1. IMPORT DATA
#========================================================

# Install package (cukup sekali)
install.packages("readxl")

# Memanggil package
library(readxl)

# Mengimpor data
data <- read_excel("DATA MENTAH RESPONDEN.xlsx")

# Melihat struktur data
str(data)

# Melihat nama variabel
names(data)

# Melihat beberapa data pertama
head(data)

# Menampilkan jumlah baris dan kolom
dim(data)

# Memilih variabel penelitian
data_penelitian <- data[,6:18]

# Melihat struktur variabel penelitian
str(data_penelitian)
```

---

## Keterangan

- `read_excel()` digunakan untuk mengimpor data hasil survei dari file Excel.
- `str()` digunakan untuk melihat struktur dan tipe data setiap variabel.
- `names()` digunakan untuk menampilkan nama seluruh variabel pada data.
- `head()` digunakan untuk melihat enam data pertama sebagai proses pengecekan awal.
- `dim()` digunakan untuk mengetahui jumlah responden dan jumlah variabel.
- `data[,6:18]` digunakan untuk memilih variabel penelitian, yaitu:
  - 1 variabel durasi tidur.
  - 12 item pertanyaan skala Likert mengenai pola tidur, kualitas tidur, dan dampak tidur terhadap aktivitas akademik.

Tahap ini memastikan data telah berhasil diimpor dan siap digunakan pada proses **uji validitas**, **uji reliabilitas**, serta **analisis statistik deskriptif dan estimasi**.

# 2. Uji Validitas Instrumen

## Tujuan

Uji validitas dilakukan untuk mengetahui apakah setiap butir pertanyaan pada kuesioner mampu mengukur variabel yang ingin diteliti. Pengujian dilakukan menggunakan **korelasi Pearson Product Moment** antara skor setiap item dengan skor total berdasarkan data dari **15 responden** yang dipilih dari hasil pengumpulan data awal.

Suatu item dinyatakan **valid** apabila memiliki nilai **p-value < 0,05** atau nilai **r hitung > r tabel**.

---

## Sintaks R

```r
# Memanggil package
library(readxl)

# Mengimpor data uji validitas (15 responden)
validitas <- read_excel("data/Data_Uji_Validitas.xlsx")

# Hanya item Likert
item <- validitas[,7:16]

item <- data.frame(lapply(item, as.numeric))

skor_total <- rowSums(item)

hasil_validitas <- data.frame()

for(i in 1:ncol(item)){
  
  hasil <- cor.test(item[,i], skor_total)
  
  hasil_validitas <- rbind(
    hasil_validitas,
    data.frame(
      Item = names(item)[i],
      r_hitung = round(hasil$estimate,3),
      p_value = round(hasil$p.value,4),
      Keputusan = ifelse(hasil$p.value<0.05,
                         "Valid",
                         "Tidak Valid")
    )
  )
}

hasil_validitas

---

## Keterangan

- `read_excel()` digunakan untuk mengimpor data uji validitas.
- `item <- validitas[,6:17]` digunakan untuk memilih seluruh item kuesioner.
- `rowSums()` digunakan untuk menghitung skor total responden.
- `cor.test()` digunakan untuk menghitung korelasi Pearson antara setiap item dengan skor total.
- Nilai **p-value < 0,05** menunjukkan bahwa item pertanyaan **valid**.
- Hasil pengujian akan menampilkan nilai **r hitung**, **p-value**, dan keputusan valid atau tidak valid untuk setiap item.

## Output

| No | Item | r-hitung | p-value | Keputusan |
|---|---|---:|---:|---|
|1|Saya tidur sekitar 7–9 jam setiap malam.|0.690|0.0044|Valid|
|2|Saya memiliki jam tidur yang teratur setiap hari.|0.708|0.0032|Valid|
|3|Saya biasanya tidur sebelum pukul 23.00.|0.776|0.0007|Valid|
|4|Saya sering begadang hingga larut malam.|-0.742|0.0015|Valid*|
|5|Saya mudah tertidur ketika mulai beristirahat.|0.596|0.0190|Valid|
|6|Saya jarang terbangun di tengah malam.|0.526|0.0441|Valid|
|7|Saat bangun pagi, tubuh saya terasa segar.|0.799|0.0004|Valid|
|8|Saya merasa kualitas tidur saya baik.|0.815|0.0002|Valid|
|9|Saya merasa mengantuk saat mengikuti perkuliahan.|-0.662|0.0072|Valid*|
|10|Saya mampu berkonsentrasi dengan baik saat belajar.|0.601|0.0177|Valid|

---

## Interpretasi Hasil

Berdasarkan hasil uji validitas, seluruh butir pernyataan yang digunakan dalam instrumen penelitian memiliki **nilai p-value kurang dari 0,05**, sehingga seluruh item dinyatakan **valid**.

Nilai korelasi (r-hitung) berkisar antara **0.526 hingga 0.815** untuk item positif, sedangkan dua item negatif memiliki nilai korelasi sebesar **-0.742** dan **-0.662**. Nilai negatif tersebut disebabkan karena kedua pernyataan merupakan **item unfavorable (reverse statement)** yang arah skornya berlawanan dengan konstruk kualitas tidur.

Secara keseluruhan, hasil ini menunjukkan bahwa setiap butir pernyataan mampu mengukur aspek yang ingin diteliti, sehingga instrumen layak digunakan pada tahap analisis selanjutnya.

---
# 3. Uji Reliabilitas Instrumen

## Tujuan

Uji reliabilitas dilakukan untuk mengetahui tingkat konsistensi instrumen penelitian dalam mengukur variabel yang diteliti. Pada penelitian ini, reliabilitas diukur menggunakan metode **Cronbach's Alpha**.

Sebelum dilakukan uji reliabilitas, dilakukan **reverse coding** terhadap item yang bersifat negatif (*unfavorable item*) agar seluruh item memiliki arah penilaian yang sama.

Instrumen dinyatakan reliabel apabila nilai **Cronbach's Alpha ≥ 0,70**.

---

## Sintaks R

```r
library(psych)

# Reverse coding item negatif
item[,4] <- 6 - item[,4]
item[,9] <- 6 - item[,9]

# Menghitung reliabilitas
hasil_reliabilitas <- alpha(item)

# Menampilkan hasil
hasil_reliabilitas

# Nilai Cronbach Alpha
hasil_reliabilitas$total$raw_alpha
```

---

## Keterangan

- `library(psych)` digunakan untuk memanggil package **psych**.
- `item[,4] <- 6 - item[,4]` digunakan untuk melakukan **reverse coding** pada item "Saya sering begadang hingga larut malam."
- `item[,9] <- 6 - item[,9]` digunakan untuk melakukan **reverse coding** pada item "Saya merasa mengantuk saat mengikuti perkuliahan."
- `alpha(item)` digunakan untuk menghitung nilai Cronbach's Alpha.
- `hasil_reliabilitas$total$raw_alpha` digunakan untuk menampilkan nilai Cronbach's Alpha.

---

## Output

```r
> hasil_reliabilitas$total$raw_alpha

[1] 0.9008793
```

---

## Interpretasi Hasil

Berdasarkan hasil analisis menggunakan package **psych** pada software **R**, diperoleh nilai **Cronbach's Alpha sebesar 0,9009**.

Nilai tersebut lebih besar dari batas minimum reliabilitas (**0,70**), sehingga instrumen penelitian dinyatakan **reliabel**. Hal ini menunjukkan bahwa seluruh butir pertanyaan memiliki tingkat konsistensi internal yang sangat baik dalam mengukur konstruk kualitas dan durasi tidur mahasiswa.

Sebelum pengujian reliabilitas dilakukan, dua butir pertanyaan yang bersifat negatif (*unfavorable item*) telah dilakukan **reverse coding** agar arah penilaian seluruh item menjadi konsisten.

---

## Kesimpulan

Hasil uji reliabilitas menunjukkan nilai **Cronbach's Alpha sebesar 0,9009**, sehingga instrumen penelitian memenuhi kriteria **sangat reliabel (excellent reliability)**. Oleh karena itu, seluruh butir pertanyaan yang telah dinyatakan valid dapat digunakan pada tahap pengumpulan data penelitian utama.
