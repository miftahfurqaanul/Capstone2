<h1> [NYC TLC Record] </h1>

## 1. Project Overview
 Proyek ini menganalisis data bisnis untuk mengekstrak wawasan, meningkatkan pengambilan keputusan, dan mengidentifikasi tren utama. Fokus utamanya adalah mengoptimalkan alokasi armada, meningkatkan kepuasan pelanggan, dan memaksimalkan pendapatan melalui pemahaman yang mendalam terhadap perilaku konsumen. 

Key Objectives:
- Objective 1: (Analisis data)
- Objective 2: (Intelijen bisnis)
- Objective 3: (Pengambilan keputusan, Optimasi, Personalisasi)

## 2. Data Sources
- [Dataset 1](https://drive.google.com/file/d/1__hjXmaKbcSd6oen-B78zdyIeQ3UfQpJ/view?usp=drive_link) - (Dataset ini berisi informasi terkait demografis, )
- [Dataset 2](https://github.com/muharismrgn/NYC-Taxi-Trip-Data-Analysis/blob/main/data/ext/taxi_zone_lookup.csv) –  (dataset berisi informasi zone taxi.)
- ...

## 3. Technologies Used
- Programming Language: Python (e.g., Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Interactive Dashboard: Tableau
- Version Control: Git
- Others: Jupyter Notebook
- ...

## 4. Project Structure

```
├── README.md          <- The top-level README for developers using this project.
|
├── data
│   ├── raw            <- Data from third party sources.
│   └── cleaned        <- The data that has been cleaned.
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as PowerPoint, PDF, LaTeX, etc.
|   ├── slide          <- Generated PowerPoint
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── src                <- Source code for use in this project.

```

## 5. Summary of Finding
### 5.1 Business Insight
Permintaan layanan taksi cenderung meningkat pada hari kerja dan mencapai puncaknya di sore hari. Wilayah Manhattan merupakan pusat aktivitas layanan taksi dengan volume perjalanan yang paling tinggi. Pilihan tarif dalam kota menjadi preferensi utama pelanggan. Besarnya tip yang diberikan oleh pelanggan secara signifikan dipengaruhi oleh tarif dan jarak tempuh perjalanan.
### 5.2 Actionable Recommendation
`Penjadwalan Armada Taksi`:

- Perlu dilakukan penambahan jumlah armada taksi pada hari kerja, khususnya pada rentang waktu Senin hingga Jumat, dengan penekanan pada hari Rabu dan Kamis. Perlu dilakukan peningkatan jumlah armada taksi yang beroperasi pada sore hari, terutama pada rentang waktu pukul 15.00 hingga 18.00. Operasional taksi perlu dioptimalkan dengan mengurangi jumlah armada yang beroperasi pada akhir pekan dan pada rentang waktu tengah malam hingga dini hari.

`Penargetan Wilayah`:  

- Untuk meningkatkan kepuasan pelanggan dan efisiensi operasional, perlu dilakukan penyesuaian alokasi armada taksi. Wilayah Manhattan, Queens, dan Brooklyn, terutama pada jam sibuk pagi dan sore hari, perlu mendapatkan tambahan armada. Khusus di Brooklyn, mengingat tarif rata-rata yang lebih tinggi pada pagi hari, perlu dipastikan ketersediaan armada yang memadai. Sebaliknya, alokasi armada di wilayah Staten Island dapat dikurangi, terutama pada jam-jam di luar jam sibuk. Sebagai bentuk apresiasi, pengemudi yang beroperasi di wilayah dengan permintaan tinggi dan mencapai target kinerja tertentu dapat diberikan bonus.

`Strategi Berdasarkan Harga`:

- Untuk mengoptimalkan pendapatan dan kepuasan pelanggan, perlu dilakukan penyesuaian strategi layanan taksi. Rute-rute dengan tarif tinggi dan permintaan konsisten, seperti rute East Harlem North ke Upper West Side North, harus menjadi prioritas. Penerapan sistem tarif dinamis, dengan kenaikan tarif sebesar 1-3% saat puncak permintaan dan pemberian diskon 10-15% pada waktu-waktu sepi, dapat meningkatkan efisiensi dan fleksibilitas layanan. Selain itu, analisis data lebih lanjut dapat mengidentifikasi rute-rute potensial lainnya yang dapat memberikan keuntungan bagi perusahaan.

`Opsi Pembayaran`:

-  Untuk meningkatkan kepuasan pelanggan dan mengikuti perkembangan zaman, perusahaan perlu memastikan kelancaran sistem pembayaran kartu kredit yang telah ada. Selain itu, integrasi berbagai metode pembayaran digital seperti e-wallet dapat menjadi nilai tambah. Dengan memberikan fleksibilitas dalam memilih metode pembayaran, diharapkan dapat menarik lebih banyak pelanggan dan meningkatkan volume transaksi.  

`Peningkatan Kualitas Pelayanan`:

- Meskipun kecepatan berkendara tidak secara langsung berbanding lurus dengan jumlah tip, namun kenyamanan dan keamanan perjalanan tetap menjadi prioritas utama pelanggan. Oleh karena itu, perusahaan perlu menerapkan sistem evaluasi kinerja pengemudi yang komprehensif untuk memastikan kualitas layanan. Selain itu, program loyalitas yang menawarkan poin rewards dan diskon untuk setiap perjalanan dapat meningkatkan kepuasan pelanggan dan mendorong mereka untuk menggunakan layanan taksi secara lebih sering

`Promosi dan Penawaran`:

- Untuk meningkatkan pendapatan dan kepuasan pelanggan, perusahaan dapat menerapkan strategi promosi yang beragam. Misalnya, menawarkan diskon 10% untuk semua perjalanan dengan jarak lebih dari 20 kilometer. Selain itu, promo khusus seperti 'Happy Hour' dengan diskon 15% pada jam-jam tertentu di wilayah dengan tarif lebih rendah dapat menarik pelanggan baru. Dengan demikian, perusahaan dapat mengoptimalkan pendapatan dan memperluas basis pelanggan.

## 6. Contact
- Name: Miftah Furqaanul Haq
- Email: miftahfh.01@gmail.com
- Linkedin:
- link tableau : https://public.tableau.com/views/ds1_17332411473120/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
