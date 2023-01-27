# Belajar Mongodb

Repository ini hasil fork dari repo Progrramer Zaman Now dan berisi data dari repo sebelumnya dan tambahan dari aku dalam belajar mongodb.
Catatan ini aku buat seminimal mungkin untuk penggunaan dasar.

## Mongo Shell

MongoDB memiliki shell yang bernama mongosh , pada versi 4 bernama mongo saja.
cara masuk kedalam mongo shell pastikan sudah menginstall mongodb terlebih dahulu.
```
mongsh
```
Untuk menampilkan database yang dipakai sekarang dapat menggunakan command db setelah masuk ke dalam mongosh.
```
db
```
untuk membuat database baru bisa menggunakan command use nama_db , maka akan langsung masuk kedalam database tersebut.
```
use belajar
db
```
## Mongodb Authentification

sebelum menjalankan command mongo shell lebih lanjut , kita di anjurkan untuk membuat authentification atau menambah pengguna username dan passwword untuk dapat melakukan manipulasi database pada mongodb.


