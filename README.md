# Shoreline Delineation Google Earth Engine

## Introduction
Halo!
Dalam supplementary code ini akan disajikan code yang digunakan untuk untuk dapat memisahkan perairan dan daratan menggunakan satelit Sentinel-2, Landsat 7 dan Landat 5. Supplementary code ini sebagai pendukung penulisan laporan Praktik Kerja Lapangan (PKL) sehingga pembaca dapat mengakses suplemantary code ini untuk mengetahui penggunaan Google Earth Engine untuk menganalisa perubahan garis pantai di Teluk Jakarta bagian barat pada tahun 2000 sampai 2020. 

Pengguna diharapkan dapat mengimplementasikan code tersebut ke dalam Google Earth Engine Code Editor pengguna. Untuk mencapai hal tersebut dalam suplementary code ini disiapkan modul singkat untuk menjalankan code tersebut. Sehingga pengguna mendapatkan aksesibilitas lebih dari laporan tersebut.

## Operation

Sebelum dapat menggunakan, pengguna diharapkan meminta akses developer serta mendaftar pada Google Earth Engine (GEE). Pengguna dapat mengikuti video, silahkan meng-klik [link ini](https://youtu.be/k3w93HIOjQg/). GEE merupakan aplikasi analisa spasial untuk akedimisi dan non-profit organization secara gratis dan berbayar untuk komersil menggunakan commercial licenses, untuk informasi lebih lanjut silahkan klik [disini](https://earthengine.google.com/faq/).

Untuk dapat menjalankan code tersebut pengguna dapat:

1. Meng-klik link Google Earth Engine dan menjalankan pada Code Editor GEE pengguna. Intruksi tersedia dalam komen setiap fungsi program. Adapun link code Google Earth Engine pada setiap satelit, sebagai berikut:
### Sentinel 2 Shoreline Delineation Random Forest Classifier
>https://code.earthengine.google.com/aed4c5b89e3b78a1eaa49caab0ecb905

### Landsat 7 Shoreline Delineation Random Forest Classifier
>https://code.earthengine.google.com/b0a4c68572afa87b66ab17516b7ceeee

### Landsat 5 Shoreline Delineation Random Forest Classifier
>https://code.earthengine.google.com/f4577732f9fe69181ad623d224570bd4

3. Meng-copy code pada masing-masing folder dan meng-paste pada Code Editor. Opsi kedua ini diharapkan pengguna untuk dapat meng-import data yang dibutuhkan, seperti area. Serta, mendifinisikan sendiri titik sampel daratan dan badan air menggunakan fitur Geometry Imports yang tersedia di GEE.

## Known Issues
Kesalahan paling umum yang mungkin terjadi (di luar variabel pengguna/kesalahan input) adalah masalah memori sisi server. Meskipun GEE adalah layanan gratis, GEE memiliki batasannya, terutama alokasi ruang server untuk tugas yang dimulai oleh pengguna. Ini akan sering dinyatakan sebagai kesalahan waktu habis atau kapasitas memori. Kesalahan yang terjadi saat mencoba memvisualisasikan lapisan (layer) di GUI sering kali dapat ditimpa dengan memperbesar/memperkecil dan/atau menggeser bingkai sedikit untuk memuat ulang lapisan peta. Kesalahan visualisasi biasanya kesalahan non-kritis. Di bawah ini adalah daftar singkat kesalahan sisi server yang umum:
  
  “Tile Error: Too many concurrent aggregations”
  “Tile Error: Earth Engine Capacity Exceeded”
 
Secara anekdot, masalah yang menghasilkan kesalahan ini biasanya terkait dengan pemrosesan area yang luas. Saat mengembangkan code, ditentukan bahwa GEE bekerja lebih efektif ketika menangani area yang lebih kecil, yaitu area kepentingan regional daripada nasional. Saat mengekspor area yang luas, pengguna mungkin mengalami batas waktu tunggu 12 jam. Jika ini terjadi, tugas pengeksporan akan gagal pada 12 jam dan menghasilkan pesan kesalahan yang menyatakan:

  “Error: Computation timed out”
  
Ditambah dengan batas atas GEE, konektivitas internet juga dapat menghadirkan tantangan stabilitas dan run-time saat menggunakan code; namun, itu tetap jauh lebih cepat daripada workstation mandiri, dan setelah satu bagian dari code dimulai, itu akan terus berlanjut bahkan jika konektivitas internet terputus untuk sementara. Ini berarti bahwa produk data perantara - dan kemajuan pengguna - disimpan secara efektif, sampai batas tertentu.

## Conclusion
Dengan suplementary code ini, pembaca laporan diharapkan dapat pemahaman lebih dengan menjalankan Google Earth Engine ini. Jika terdapat isu atau masalah dalam menjalankan code atau memiliki pertanyaan lebih lanjut dapat menghubungi saya pada email: rinaldyterra.16@gmail.com 

Mohon meninjau terlebih dahulu Known Issues dan lakukan Troubleshooting.

Semoga dapat membantu. Atas perhatiannya saya ucapkan Terima Kasih
