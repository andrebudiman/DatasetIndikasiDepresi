# DatasetIndikasiDepresi
Data Crawling Twitter Data

Data yang digunakan berjumlah 10801 data dan sudah melalui proses anotasi yang melibatkan psikolog dalam klasifikasi data awal.
Data yang digunakan kemudian dilanjutkan dengan proses normalisasi data secara manual untuk mengurangi noise dan mengurangi jumlah fitur yang akan dibentuk.

Data yang dihasilkan merupakan data dengan periode waktu : 18 November 2020 s/d 7 Desember 2020 dan merupakan data yang berasal dari pulau Jawa, Bali, dan Sumatera dengan menggunakan kata kunci khusus yang memiliki arti negatif sebagai acuan sistem dalam melakukan penarikan data..

Terdapat beberapa hal lain yang dihasilkan melalui proses crawling Twitter data:
1. Id_Tweet
2. Location
3. Username
4. Raw_Tweet (tweet)
5. deEmoji (tweet + Reg[Ex] untuk remove emoji dan beberapa hal lain)

Dataset memliliki 2 kategori utama: 
1. Terindikasi Depresi
2. Tidak Terindikasi Depresi
