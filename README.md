<div id="top"></div>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->



<!-- PROJECT LOGO -->
<br />
<div align="center">

  <h4 align="center">Project UAS Mata Kuliah Visualisasi Data</h4>

  <h1 align="center"> Pembangunan Dashboard Profil Kesehatan Provinsi Jawa Timur </h1>

</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#pendahuluan">Pendahuluan</a>  
    </li>
    <li><a href="#data-dan-sumber-data">Data & sumber data</a></li>
    <li><a href="#metodologi">Metodologi</a></li>
    <li><a href="#visualisasi-persebaran">Visualisasi persebaran</a></li>
    <li><a href="#visualisasi-kesehatan-keluarga">Visualisasi kesehatan keluarga</a></li>
    <li><a href="#visualisasi-kesehatan-lingkungan">Visualisasi kesehatan lingkungan</a></li>
    <li><a href="#visualisasi-sarana-kesehatan">Visualisasi sarana kesehatan</a></li>
    <li><a href="#visualisasi-pengendalian-penyakit">Visualisasi pengendalian penyakit</a></li>
    <li><a href="#visualisasi-karakteristik-umum">Visualisasi karakteristik umum (header)</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## Pendahuluan

<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/dashboardfinal.png" />
</p>

<p align="justify"> 
Pembangunan dashboard profil kesehatan Provinsi Jawa Timur dilaatrbelakangi oleh beberapa hal sebagai berikut.
</p>

* Kesehatan merupakan hak dasar bagi setiap individu. Selain itu, kesehatan juga merupakan modal yang sangat penting bagi pembangunan suatu wilayah. Untuk itu, kesehatan perlu dijadikan prioritas pembangunan untuk mewujudkan sumber daya manusia yang berkualitas dan maju.
* Indonesia berada pada peringkat 45 dan urutan keempat diantara negara Asia Tenggara untuk Global Health Security Index. 
* Dalam pelaksanaan pemerintahan, Indonesia menganut asas desentralisasi yang memberikan wewenang pada pemerintah daerah untuk mengatur wilayahnya sendiri.
* Provinsi Jawa Timur merupakan provinsi terpadat kedua di Indonesia yang memiliki anggaran kesehatan 4 Triliun lebih pada tahun 2020. Dengan kepadatan penduduk yang tinggi, risiko kesehatan lebih tinggi pula.
* Anggaran kesehatan yang tidak sedikit perlu untuk dikelola dengan bijak melalui kebijakan yang efektif dan tepat sasaran. Kebijakan yang tepat perlu didukung dengan data dan informasi yang memadai. 

<p align="justify">
Profil Kesehatan merupakan publikasi tahunan Kementerian Kesehatan yang menggambarkan kondisi kesehatan di suatu wilayah. Namun, publikasinya yang hanya berupa ebook dan kebanyakan data masih berupa tabel, membuat informasi sulit dipahami dan tidak dapat dilihat keterbandingannya. Untuk itu, diperlukan dashboard informasi kesehatan Provinsi Jawa Timur yang berisi data yang telah divisualisasikan untuk dapat mendukung kesehatan masyarakat yang lebih baik. Penelitian ini menghasilkan dashboard informasi kesehatan Provinsi Jawa Timur yang interaktif dan berisi karakteristik umum, persebaran fasilitas/tenaga kesehatan dan penyakit, kesehatan keluarga, kesehatan lingkungan, sarana kesehatan, dan pengendalian penyakit tahun 2020 di Jawa Timur yang dibangun dengan software Tableau.
</p>

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- USAGE EXAMPLES -->
## Data dan sumber data
<p align="justify">
Data yang digunakan dalam penelitian diperoleh dari publikasi Dinas Kesehatan Provinsi Jawa Timur yaitu Profil Kesehatan Provinsi Jawa Timur Tahun 2020. Data yang diolah merupakan data tabular (data dalam tabel) yang dilampirkan dalam publikasi. 
</p>

_Berikut tautan sumber data yang digunakan yaitu [Profil Kesehatan Provinsi Jawa Timur Tahun 2020](https://dinkes.jatimprov.go.id/userfile/dokumen/PROFIL%20KESEHATAN%202020.pdf.)_

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ROADMAP -->
## Metodologi

<p align="justify">
Penelitian ini dilakukan dengan mengikuti metodologi yang dapat dilihat pada gambar berikut.
</p>

<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/sarana.png" width="300" height="600" />
</p>

<p align="justify">
Sebelum melakukan visualisasi, perlu dilakukan data preprocessing terlebih dahulu. Berikut langkah-langkahnya.

1. Split publikasi Profil Kesehatan Jawa Timur Tahun 2020 untuk memisahkan bagian isi dan lampiran. Selanjutnya hanya lampiran yang digunakan karena berisi data lengkap.
2. Convert lampiran yang berupa pdf ke format excel agar memudahkan (tidak perlu input manual satu per satu).
3. Lalu dilakukan preprocessing pada excel hasil convert yang disesuaikan dengan [hasil seleksi data atau data apa saja yang akan ditampilkan](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/KONTEN%20DASHBOARD%20VISDAT.docx). 
4. Dataset hasil preprocessing ada pada tautan berikut
   * [Data Kab/kota](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/Data%20Kota%20Prov.xlsx)
   * [Data Kesehatan Lingkungan](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/Kesehatan%20Lingkungan.xlsx)
   * [Data Pengendalian Penyakit](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/Pengendalian%20P.xlsx)
   * [Data Sarana Kesehatan](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/Sarana.xlsx)
   * [Data info umum](https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/info%20umum.xlsx)
5. Setelah dataset siap olah, connect dataset ke Tableau.
</p>

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- PERSEBARAN -->
## Visualisasi persebaran

Menampilkan persebaran tenaga kesehatan, fasilitas kesehatan, dan penyakit di Provinsi Jawa Timur. Divisualisasikan menggunakan **choropleth map**.

* Tenaga kesehatan meliputi: dokter umum, dokter spesialis, dokter gigi, dokter gigi spesialis, perawat, bidan, apoteker, tenaga kefarmasian, ahli laboratorium, dan ahli gizi.
* Fasilitas kesehatan meliput: rumah sakit dan puskesmas.
* Penyakit meliputi: hipertensi, demam berdarah, diabetes melitus, HIV, TBC, ODGJ (Orang Dengan Gangguan Jiwa).

Berikut visualisasi persebaran fasilitas, tenaga kesehatan, dan penyakit.
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/persebaran.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- KESEHATAN KELUARGA -->
## Visualisasi kesehatan keluarga

Menampilkan kondisi kesehatan keluarga kabupaten/kota atau provinsi Jawa Timur yang diwakili oleh beberapa variabel signifikan. Divisualisasikan menggunakan **parallel coordinate plot**.

Berikut variabel yang digunakan
* presentase ibu melahirkan dibantu dengan tenaga medis di fasilitas kesehatan,
*	presentase imunisasi Tetanus 1 pada wanita usia subur,
*	presentase peserta KB aktif,
*	presentase bayi diberi ASI eksklusif,
*	presentase pelayanan kesehatan pada Balita,
*	presentase imunisasi dasar lengkap anak,
*	presentase Balita kurang gizi,
*	presentase masyarakat usia produktif yang mendapat pelayanan kesehatan sesuai standar, dan
*	presentase pelayanan kesehatan pada Lansia.

Berikut visualisasi kesehatan keluarga.
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/kes%20keluarga.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- KESEHATAN LINGKUNGAN -->
## Visualisasi kesehatan lingkungan
Menampilkan kondisi kesehatan lingkungan kabupaten/kota atau provinsi Jawa Timur yang diwakili oleh beberapa variabel signifikan. Tujuannya untuk membandingkan antara wilayah satu dengan yang lainnya. Divisualisasikan menggunakan **radar chart**.


Berikut variabel yang digunakan
* presentase desa yang melaksanakan STBM (Sanitasi Total Berbasis Masyarakat),
*	presentase keluarga dengan akses sanitasi layak,
*	presentase sarana air minum dengan risiko rendah/sedang,
*	presentase sarana air minum memenuhi syarat,
*	presentase tempat pengolahan makanan sehat, dan
*	presentase tempat umum sehat.

Berikut visualisasi kesehatan lingkungan.
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/kes%20lingkungan.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- SARANA KESEHATAN -->
## Visualisasi sarana kesehatan

Menampilkan sarana kesehatan di Provinsi Jawa Timur. Tujuannya untuk melihat jenis, jumlah, dan keterbandingan antarjenis dan kategori-kategorinya (hierarki data). Oleh karena itu, divisualisasikan menggunakan **tree map**.

Berikut hierarki variabel yang digunakan
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/Hierarki%20Sarana.png" width="400" height="600" />
</p>

<p align="justify">Visualisasi sarana kesehatan dibuat fitur drill-down sehingga dapat interaktif yang jika di-click akan muncul kategori dari jenis sarana tersebut. Berikut visualisasi sarana kesehatan.
</p>
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/sarana.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- PENGENDALIAN PENYAKIT -->
## Visualisasi pengendalian penyakit

Menampilkan pengendalian penyakit kabupaten/kota atau Provinsi Jawa Timur. Tujuannya untuk melihat seberapa baik pengendalian penyakit (1-100%) angka tinggi atau mendekati 100% menunjukkan pengendalian penyakit baik dan menyeluruh. Oleh karena itu, divisualisasikan menggunakan **percentage bar chart** sehingga terlihat target 100%-nya.

Berikut variabel yang digunakan.
-	Diabetes melitus dengan pelayanan sesuai standar.
-	Diare yang dilayani.
-	Hipertensi yang dilayani.
-	Kesembuhan Covid19.
-	Malaria dengan pelayanan sesuai standar.
-	ODGJ berat mendapat pelayanan.
-	Pencegahan pneumonia pada Balita.
-	TBC yang berhasil diobati.

Berikut visualisasi pengendalian penyakit.
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/pengendalian.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- KARAKTERISTIK UMUM -->
## Visualisasi karakteristik umum

Menampilkan karakteristik umum Provinsi Jawa Timur. Tujuannya agar pengguna dapat mendapat gambaran umum mengenai jumlah kabupaten/kota, jumlah penduduk, dan total anggaran kesehatan Provinsi Jawa Timur. Oleh karena itu, divisualisasikan menggunakan **text visualization**.

Berikut visualisasi karakteristik umum.
<p align="center">
<img src = "https://github.com/IftitahAthiyyah/Project-UAS-Visdat/blob/master/images/karakteristik%20umum.png" />
</p>

<p align="right">(<a href="#top">back to top</a>)</p>


<h4>
Akses dashboard di Tableau Public
[DASHBOARD PROFIL KESEHATAN](https://public.tableau.com/shared/KQBQT6226?:display_count=n&:origin=viz_share_link)
</h4>
