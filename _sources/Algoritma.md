---
title: Algoritma

---

# Algoritma 
## Definisi Algoritma

### Algoritm Sequential Search

### Algoritma Binary Search 

## Pseudocode adalah

## Definisi Algoritma
Algoritma adalah suatu langkah atau metode yang telah direncanakan secara matang agar berurutan dan tersusun rapi, serta sering digunakan untuk menyelesaikan suatu masalah dengan  memberikan petunjuk tindakan.

Karakteristik Algoritma
Agar suatu instruksi dapat menjadi suatu algoritma, instruksi tersebut harus mempunyai beberapa ciri-ciri. 

Pertama, apabila algoritma memerlukan input, maka algoritma yang ada harus didefinisikan secara jelas. Selanjutnya algoritma yang ada jelas dan tidak ambigu, setiap proses, langkah dan instruksi yang ada harus jelas dalam segala hal. Terakhir, tentu algoritma mempunyai tujuan yang ingin dicapai.

Jenis-jenis Algoritma
Algoritma sendiri dibagi ke dalam beberapa jenis. Yuk, kita lihat jenis-jenis algoritma yang kami lansir dari Nesaba Media. 

1. Algoritma Rekursif
Algoritma rekursif adalah jenis algoritma yang akan melakukan perulangan sendiri hingga masalahnya terpecahkan. Selain itu, algoritma akan memanggil dirinya sendiri berulang kali hingga masalahnya terpecahkan.

2. Algoritma Divide and Conquer
Algoritma Divide and Conquer merupakan salah satu jenis algoritma yang membagi suatu masalah menjadi beberapa bagian. Langkah-langkah algoritma membagi dan menaklukkan antara lain membagi masalah menjadi bagian-bagian yang sama dan kemudian mencari  solusi utama setelah diperoleh solusi untuk sub-bagiannya.

3. Algoritma Dynamic Programming
Algoritma pemrograman dinamis (Algoritma dynamic programming) merupakan algoritma yang bekerja dengan cara mencari solusi dari setiap bagian terkecil dari suatu permasalahan, hasilnya  akan disimpan untuk menyelesaikan permasalahan baru di masa yang akan datang.

4. Algoritma Greedy
Algoritma greedy merupakan algoritma yang digunakan untuk mencari permasalahan optimasi. Cara kerja algoritma  ini adalah mencari solusi optimal  lokal apapun konsekuensi yang  diterimanya, sehingga dapat ditemukan solusi optimal  global.

5. Algoritma Brute Force
Algoritma brute force ini merupakan jenis algoritma dengan konsep yang paling sederhana. Algoritma ini menggunakan iterasi dari setiap solusi yang ditemukan untuk menemukan solusi yang paling sesuai dengan permasalahan yang ada.
https://bakrie.ac.id/articles/628-ini-dia-pengertian-algoritma-beserta-karakteristiknya.html#:~:text=Sederhananya%2C%20algoritma%20adalah%20suatu%20langkah,masalah%20dengan%20memberikan%20petunjuk%20tindakan.
## Algoritma Sequential Search
Sequential search adalah teknik pencarian data yang dilakukan dengan cara membandingkan setiap elemen data satu per satu, mulai dari elemen pertama hingga elemen yang dicari ditemukan. Proses ini terus berlanjut hingga data ditemukan atau seluruh elemen telah diperiksa.

Algoritma ini termasuk salah satu algoritma pencarian yang paling sederhana dan sering digunakan dalam situasi di mana data tidak memiliki struktur tertentu.

Fungsi Sequential Search
1. Digunakan untuk mencari data dengan melakukan proses membandingkan setiap elemen larik secara beruntun satu persatu, mulai dari elemen pertama, sampai elemen yang dicari ditemukan, atau seluruh elemen sudah diperiksa .
2. Dapat digunakan untuk pengelolaan data, seperti fungsi pencarian data barang pada master data barang .
3. Dalam konteks pengujian kecepatan pencarian, Algoritma Sequential Search dapat digunakan dengan fungsi microtime untuk mengevaluasi kecepatan pencarian data

Cara Kerja Sequential Search
Algoritma Sequential Search bekerja dengan melakukan perbandingan satu persatu secara beruntun dalam kumpulan data dengan data yang dicari sampai data tersebut ditemukan atau tidak ditemukan.


found = False

while not found and i < len(data):
if data[i] == target:
found = True
else:
i += 1

if found:
return i # Mengembalikan indeks elemen yang ditemukan
else:
return -1 # Mengembalikan -1 jika elemen tidak ditemukan

https://fikti.umsu.ac.id/algoritma-sequential-search-pengertian-fungsi-dan-cara-kerjanya/

### Algoritma Binary Searh
mumnya algoritma pencarian biner dikenal sebagai pencarian setengah interval atau pencarian logaritmik. Metode pencarian biner merupakan salah satu metode yang cepat dan efisien untuk menemukan nilai target tertentu dari sekumpulan item yang dipesan. Hal ini dikarenakan cara kerja algoritma pencarian biner yang memulai di tengah daftar yang diurutkan. Maka hal tersebut secara efektif memotong setengah ruang pencarian dengan menentukan apakah akan naik atau turun daftar berdasarkan nilai median.

https://tekno.kompas.com/read/2022/12/03/03000047/pengertian-binary-search-cara-kerja-dan-keunggulannya.


### Algoritma Binary Search
Umumnya algoritma pencarian biner dikenal sebagai pencarian setengah interval atau pencarian logaritmik. Metode pencarian biner merupakan salah satu metode yang cepat dan efisien untuk menemukan nilai target tertentu dari sekumpulan item yang dipesan. Hal ini dikarenakan cara kerja algoritma pencarian biner yang memulai di tengah daftar yang diurutkan. Maka hal tersebut secara efektif memotong setengah ruang pencarian dengan menentukan apakah akan naik atau turun daftar berdasarkan nilai median.

Berikut langkah-langkah dalam kerja algoritma pencarian biner:
1. Proses pencarian dimulai dengan menempatkan elemen tengah dari larik data yang diurutkan Setiap data yang menggunakan algoritma pencarian biner harus diurutkan terlebih dahulu, sehingga baru bisa melanjutkan proses kerja selanjutnya. Apabila data belum urut, maka data yang ada perlu diurutkan lebih dahulu 
2. Kemudian nilai kunci dibandingkan dengan elemennya
3. Apabila nilai kunci lebih kecil dari elemen tengah, maka penelusuran akan menganalisis nilai atas hingga elemen tengah untuk perbandingan dan pencocokan
4.  Akan tetapi, apabila nilai kunci lebih besar dari elemen tengah, maka penelusuran menganalisis nilai yang lebih rendah ke elemen tengah untuk perbandingan dan pencocokan

https://tekno.kompas.com/read/2022/12/03/03000047/pengertian-binary-search-cara-kerja-dan-keunggulannya.

## Pseudocode adalah
Pseudocode adalah penulisan kode semu yang dibuat dengan bahasa sederhana agar mudah dipahami oleh orang awam dari berbagai latar belakang teknis. 

Beberapa penulisan bahasa pemrograman seperti JavaScript yang tujuan utamanya adalah untuk mudah dibaca manusia, terkadang masih sedikit sulit untuk dipahami. Dalam hal ini, pseudocode adalah salah satu solusinya. 

Ciri-Ciri Pseudocode
Agar Anda semakin menguasai konsep apa itu pseudocode, pahami ciri-ciri pseudocode di bawah ini. 

1. Tidak memiliki aturan baku secara sintaks, sehingga setiap tim pengembang dapat menyusun pseudocode sesuai gaya dan preferensi mereka. 
2. Pseudocode umumnya ditulis dengan bahasa Inggris untuk memudahkan integrasi ke dalam bahasa pemrograman.
3. Pseudocode bukan termasuk bahasa pemrograman karena hanya berfungsi sebagai kode semu yang bersifat sementara. 
4. Pseudocode umumnya lebih ringkas dibandingkan dengan algoritma dalam bahasa pemrograman yang sesungguhnya
Penulisannya tidak menggunakan bentuk diagram karena sering kali ditulis dalam urutan suatu kejadian atau permasalahan.
5. Penulisannya tidak menggunakan bentuk diagram karena sering kali ditulis dalam urutan suatu kejadian atau permasalahan.
6. Pseudocode menggunakan bahasa yang mudah dipahami secara universal sehingga dapat diakses dan dimengerti oleh berbagai pihak, terlepas dari latar belakang pemrograman mereka.

Fungsi Pseudocode:
1. Dokumentasi Awal dari Pengembangan Program
Fungsi pertama pseudocode adalah sebagai dokumentasi awal yang digunakan dalam pengembangan program. 

Artinya, sebelum programmer mulai menulis kode sebenarnya dalam bahasa pemrograman tertentu, mereka dapat menggambarkan langkah-langkah dan alur kerja program menggunakan pseudocode. 

Maka dari itu, pseudocode umumnya sangat bermanfaat dalam proses perancangan dan dokumentasi rencana kerja sebelum melakukan implementasi yang lebih rinci.

2. Mempermudah Keterbacaan Algoritma
Jika dibandingkan dengan kode sumber yang ditulis dalam bahasa pemrograman, pseudocode dapat lebih mudah dipahami oleh berbagai pihak, termasuk tim programmer yang mungkin tidak terbiasa dengan bahasa pemrograman tertentu. 

3. Menafsirkan Alur Flowcharyt
Dalam proses pengembangan program, pseudocode juga membantu merinci langkah-langkah yang harus diambil dalam suatu proses tanpa terikat pada bahasa pemrograman tertentu. 
Dengan pseudocode, pengembang dapat lebih mudah memahami konsep yang ada dalam flowchart dengan sintaks dan logika kode yang diperlukan dalam bahasa pemrograman tertentu. 

4. Memudahkan Komunikasi Antar Tim 
Salah satu tujuan utama digunakannya pseudocode adalah memfasilitasi komunikasi antar tim developer agar semakin efektif dan efisien. 

5. Mengurangi Kesalahan Penulisan Kode
Pada dasarnya, pseudocode adalah kode semu yang juga digunakan untuk membantu menavigasi keberadaan bug pada suatu program sebelum algoritma asli mulai disusun. 

6. Bersifat Universal dan Tidak Terikat pada Bahasa Pemrograman
Pseudocode bersifat universal dan tidak terikat pada bahasa pemrograman tertentu. Sehingga, setiap pengembang dari berbagai latar belakang daoat berkontribusi dan memahami algoritma tanpa harus memiliki pengetahuan mendalam tentang bahasa pemrograman yang digunakan dalam implementa
https://cmlabs.co/id-id/seo-guidelines/pseudocode-adalah

## Big O algoritmaBig-O
Notation adalah cara untuk mengkonversi keseluruhan langkah-langkah suatu algoritma kedalam bentuk Aljabar, yaitu dengan menghiraukan konstanta yang lebih kecil dan koefisien yang tidak berdampak besar terhadap keseluruhan kompleksitas permasalahan yang diselesaikan oleh algoritma tersebut.

https://medium.com/bee-solution-partners/penjelasan-sederhana-tentang-time-complexity-dan-big-o-notation-4337ba275cfe#:~:text=Big%2DO%20Notation%20adalah%20cara,yang%20diselesaikan%20oleh%20algoritma%20tersebut.

## Hitung Big O Algoritm Sequential Search
- Waktu kompleksitas (time complexity)
Time Complexity adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan Space Complexity adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang Time Complexity.
Time Complexity adalah seberapa lama waktu yang diperlukan untuk menjalankan suatu algoritma. Sedangkan Space Complexity adalah seberapa besar memori yang kita gunakan untuk menjalankan suatu algoritma. Dan disini kita hanya akan membahas tentang Time Complexity.

https://medium.com/bee-solution-partners/penjelasan-sederhana-tentang-time-complexity-dan-big-o-notation-4337ba275cfe

- Ruang kompleksitas (space komplexity)
Kompleksitas Ruang: 
Definisi –

Pemecahan masalah menggunakan komputer memerlukan memori untuk menampung data sementara atau hasil akhir saat program sedang dijalankan. Jumlah memori yang dibutuhkan oleh algoritma untuk menyelesaikan masalah yang diberikan disebut kompleksitas ruang algoritma.

Kompleksitas ruang suatu algoritma mengukur jumlah ruang yang diambil oleh suatu algoritma untuk dijalankan sebagai fungsi dari panjang input. Pertimbangkan sebuah contoh: Misalkan sebuah masalah untuk menemukan frekuensi elemen array .
https://www.geeksforgeeks.org/time-complexity-and-space-complexity/



