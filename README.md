#### Nama : Adrian Aryaputra Hamzah
#### NPM : 2206811474
#### Kelas : ADPRO - B
#### ASDOS : GEN

# TUTORIAL - 10
## Refleksi

##### 1.2 Understanding how it works
![alt text](image.png)
Berdasarkan hasil output dari kode yang diberikan, dapat dipahami bahwa fungsi asynchronous (async) akan dieksekusi di luar aliran utama (main thread) yang memanggilnya. Akibatnya, kemungkinan output "... hey hey" akan muncul sebelum ".. howdy!" dan "... done!" karena kode "... hey hey" berada di luar fungsi asynchronous.
Hal ini terjadi karena program akan melanjutkan eksekusi dan mencetak "hey hey", sementara fungsi asynchronous masih menunggu hasil dari operasi asynchronous yang sedang dijalankan (dalam hal ini, future).