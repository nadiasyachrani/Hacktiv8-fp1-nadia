Python for Data Science - MSIB Batch 4 

Kelompok 3

1. M. Haikal Febrian
2. Naurah Nadzifah Azizi
3. Nadia Syachrani
4. Muhammad Randy

PYTN-KS11

**FINAL PROJECT 1**

# Objektif:

Tujuannya adalah untuk pertama-tama mengeksplorasi informasi tersembunyi atau yang sebelumnya tidak diketahui dengan menerapkan analitik data eksplorasi pada kumpulan data dan untuk mengetahui pengaruh setiap bidang pada harga dengan setiap bidang lain dari kumpulan data. Kemudian kami menerapkan model pembelajaran mesin yang berbeda untuk menyelesaikan analisis. Setelah itu, hasil model pembelajaran mesin yang diterapkan dibandingkan dan dianalisis berdasarkan akurasi, dan kemudian model dengan kinerja terbaik disarankan untuk prediksi lebih lanjut dari label 'Harga'.
# data:

Untuk proyek ini kami mengambil dataset dari kaggle di mana terdapat 57 kolom dan sekitar 6 lakh baris dan file tersebut dalam format csv. Anda dapat melihat atau mengunduh dataset melalui tautan ini: https://www.kaggle.com/brllrb/uber-and-lyft-dataset-boston-ma

# Penerapan Proyek ini:
Kami menggunakan algoritma pembelajaran mesin untuk memprediksi harga Uber, sehingga mudah bagi perusahaan untuk melakukan analisis harga berdasarkan fitur tertentu.

# kesimpulan
## Kesimpulan terhadap EDA :
* Terdapat 12 tempat asal dan tujuan pada dataset ini. Faktor yang dapat mempengaruhi banyaknya tempat asal dan tujuan antara lain populasi di kota Boston, keberadaan objek wisata atau tempat kerja, serta kondisi geografis dan infrastruktur di Boston.

* Terdapat 2 merek taksi online pada dataset ini, yakni Uber dan Lyft. Faktor yang mempengaruhi banyaknya merek antara lain kepopuleran masing-masing merek di Boston, tingkat persaingan antara kedua merek, serta kualitas layanan dan harga yang ditawarkan.

* Cuaca yang paling sering muncul adalah Overcast, yang dapat disebabkan oleh cuaca yang relatif stabil di Boston atau mungkin karena musim tertentu yang sedang berlangsung.

* Rute paling banyak dipesan adalah Financial District, yang dapat disebabkan oleh faktor populasi yang tinggi di wilayah tersebut atau karena banyaknya tempat kerja atau objek wisata di sekitar Financial District.
## Kesimpulan terhadap Model :
* Berdasarkan hasil dari berbagai nilai rasio alpha dan l1, terlihat bahwa model Ridge Regression dengan nilai alpha 1e-10 dan rasio l1 sebesar 0,5 tampil paling baik pada set validasi, dengan skor R^2 sebesar 0,023962 dan nilai MAE dan RMSE yang relatif rendah. Namun, kinerja model secara keseluruhan masih relatif buruk, seperti yang ditunjukkan oleh skor R^2 yang rendah di semua nilai rasio alfa dan l1.

* Nilai set tes yang diprediksi juga dicetak, menunjukkan nilai prediksi model untuk setiap sampel dalam set tes.

* Secara keseluruhan, mungkin perlu mengeksplorasi teknik pemodelan lain atau rekayasa fitur tambahan untuk meningkatkan kinerja model ini.
