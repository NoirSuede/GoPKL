# GoPKL
GoPKL bertujuan untuk mensimulasi sebuah program hipotesis yang dapat menghubungkan tukang kaki-lima yang menjual usaha mereka dengan berkeliling, dengan orang-orang yang membutuhkan usaha mereka via sebuah applikasi.
Saya minta maaf karena program ini tidak bisa memiliki kapabilitas untuk memanggil dari database Excel, karena dari sejak saya mulai belajar pemrogramman komputer-komputer yang saya gunakan sangat bandel ketika saya mencoba untuk menggunakan header buatan orang

## About
Program ini dibuat oleh kelompok 6:
-Nathanael Eugene Kristantio - 1706036816

## Installation
File program bisa dibuka dengan mengunakan sebuah program IDE yang mendukung C seperti DevC++ atau CodeBlocks, dan lalu bisa dicomplie dengan menggunakan compiler favorit.

## Code Explanation
Dibawah ini merupakan penjelasan utama dari setiap fungsi yang berada dalam file program:

`scanf("%d", &masakan);
Fungsi ini bertujuan untuk mendapatkan jenis makanan yang pengguna inginkan, agar program bisa mencarikan pengguna dengan para pengusaha yang memiliki jenis usaha sama dengan yang dipilih saja

'tunggu = rand()%10000 + 1;
Fungsi ini bertujuan untuk mensimulasi waktu yang dibutuhkan program untuk menghubungkan pengguna dengan pengusaha yang paling dekat dalam rentang 10 detik, apabila lebih dari 10 detik program belum menemukan sebuah pengusaha maka program akan menampilkan pesan "No gerobak that sells the food you want is found"

`switch(masakan){
Fungsi ini bertujuan untuk menuntun program untuk hanya mencari pengusaha yang jenisnya sesuai dengan yang telah dipilih pengguna

`bubur/mie/martabak = rand()%2 + 1;
Fungsi ini bertujuan untuk mensimulasi program menemukan pengusaha-pengusaha yang berbeda, dengan cara mengacak daripada tiga pengusaha untuk para ketiga jenis usaha.


## License
This code is released into the public domain free of any restrictions. The author requests acknowledgement if the code is used, but does not require it. This code is provided free of any liability and without any quality claims by the author.
Saya minta maaf karena program ini , sepertinya laptop saya tidak mau menerima 
