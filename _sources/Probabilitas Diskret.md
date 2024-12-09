---
title: Probabilitas Diskrit

---

# mencatat dan menambah konsep probabilitas diskrit teorema bayes

# Distribusi Probabilitas Diskrit
Distribusi probabilitas diskrit adalah suatu daftar atau distribusi di mana
variabel randomnya mengasumsikan masing-masing nilainya dengan probabilitas
tertentu. Variabel diskrit memiliki jumlah nilai kemungkinan yang terbatas atau
jumlah yang tak terhingga dari nilai-nilai yang dapat dihitung. Kata “dihitung” berarti bahwa variabel random tersebut dapat dicacah dengah menggunakan angka 1, 2, 3 dst. 
Misalnya, jumlah panggilan telepon yang diterima setelah siaran TV mengudara
adalah contoh variabel diskrit, karena bisa dihitung.
# Distribusi Binominal
Distribusi Binomial adalah suatu distribusi probabilitas yang dapat digunakan
bilamana suatu proses sampling dapat diasumsikan sesuai dengan proses Bernoulli.
Misalnya, dalam perlemparan sekeping uang logam sebanyak 5 kali, hasil setiap
ulangan mungkin muncul sisi gambar atau sisi angka. Begitu pula, bila kartu diambil
berturut-turut, kita dapat memberi label “berhasil” bila kartu yang terambil adalah
kartu merah atau “gagal” bila yang terambil adalah kartu hitam. Ulangan-ulangan
tersebut bersifat bebas dan peluang keberhasilan setiap ulangan tetap sama, yaitu sebesar setengah.

Penerapan Teorema Bayes sangat luas dan tidak terbatas pada bidang keuangan. Misalnya, Teorema Bayes dapat digunakan untuk menentukan keakuratan hasil uji medis dengan mempertimbangkan seberapa besar kemungkinan seseorang mengidap penyakit dan keakuratan umum pengujian tersebut. Teorema Bayes mengandalkan penggabungan distribusi probabilitas sebelumnya untuk menghasilkan probabilitas posterior .

Dalam inferensi statistik Bayesian, probabilitas sebelumnya adalah probabilitas terjadinya suatu peristiwa sebelum data baru dikumpulkan. Dengan kata lain, probabilitas ini merupakan penilaian rasional terbaik atas probabilitas hasil tertentu berdasarkan pengetahuan terkini sebelum eksperimen dilakukan.

Probabilitas posterior adalah probabilitas yang direvisi dari suatu peristiwa yang terjadi setelah mempertimbangkan informasi baru. Probabilitas posterior dihitung dengan memperbarui probabilitas sebelumnya menggunakan teorema Bayes. Dalam istilah statistik, probabilitas posterior adalah probabilitas terjadinya peristiwa A, mengingat peristiwa B telah terjadi.

# Pertimbangan Khusus
Teorema Bayes memberikan probabilitas suatu peristiwa berdasarkan informasi baru yang terkait atau mungkin terkait dengan peristiwa tersebut. Rumus tersebut juga dapat digunakan untuk menentukan bagaimana probabilitas terjadinya suatu peristiwa dapat dipengaruhi oleh informasi baru yang bersifat hipotetis, dengan asumsi bahwa informasi baru tersebut akan terbukti benar.

Misalnya, coba ambil satu kartu dari setumpuk kartu yang berjumlah 52 kartu.

# Contoh Numerik Teorema Bayes
Sebagai contoh numerik, bayangkan ada tes narkoba yang keakuratannya 98%, artinya 98% waktunya, tes tersebut menunjukkan hasil positif yang sebenarnya bagi seseorang yang menggunakan narkoba, dan 98% waktunya, tes tersebut menunjukkan hasil negatif yang sebenarnya bagi mereka yang bukan pengguna narkoba.

Selanjutnya, asumsikan 0,5% orang menggunakan obat tersebut. Jika seseorang yang dipilih secara acak dinyatakan positif menggunakan obat tersebut, perhitungan berikut dapat dilakukan untuk menentukan kemungkinan orang tersebut benar-benar menggunakan obat tersebut, dengan ketentuan sebagai berikut:

A = Probabilitas bahwa hasil tes positif adalah benar
B = Persentase orang yang menggunakan narkoba
A x B = probabilitas bahwa hasil tes positif itu benar
( 1 - A ) x ( 1 - B ) = Peluang hasil tes negatif adalah benar
Rumusnya akan terlihat seperti ini:

( A x B ) / [ ( A x B ) + { ( 1 - A ) x ( 1 - B ) } ] = Peluang Mengonsumsi Obat
Dengan menggunakan nilai-nilai tersebut, perhitungannya adalah sebagai berikut:

( 0,98 x 0,005 ) / [ ( 0,98 x 0,005 ) + { ( 1 - 0,98 ) x ( 1 - 0,005 ) } ] =
0,0049 / ( 0,0049 + 0,0199 ) = 19,76%
Teorema Bayes memperlihatkan bahwa meskipun seseorang dinyatakan positif dalam skenario ini, ada kemungkinan sebesar 19,76% orang tersebut mengonsumsi obat dan kemungkinan sebesar 80,24% tidak mengonsumsinya.
