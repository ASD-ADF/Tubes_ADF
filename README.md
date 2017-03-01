# TUBES STRUKTUR DATA 2016-2

* Kelompok : max 2 orang
* Topik : bebas

### Syarat untuk kelompok 2 orang : 
- pembagian tugas pengerjaan prosedur/fungsi yang jelas
- BERIKAN KETERANGAN NIM YANG MENGERJAKAN DI SETIAP FUNGSI/PROSEDUR

### [5 POIN] ABSTRACT DATA TYPE
* List Parent dan List Child (parent.h dan child.h)
	- 1 single linked list
	- 1 double linked list
	- infotype parent dan child minimum memiliki 1 atribut ID dan 5 atribut lainnya (bebas)
* List Relasi (relasi.h)
	- 1 list relasi (single atau double, bebas)
	- elemen relasi berisi address parent, address child, dan address relasi (next)

### FUNGSI DAN PROSEDUR DASAR
* <b>[10 POIN]</b> Fungsi dan Prosedur Dasar List Parent dan Child (parent.cpp dan child.cpp)
	- Masing-masing 3 prosedur insert dan 3 prosedur delete (first, last, after)
	- fungsi findElm, mencari elemen berdasarkan ID
	- prosedur printInfo, menampilkan data lengkap ID dan 1 atribut saja
	- fungsi/prosedur dasar lainnya: alokasi, createList, dealokasi
* <b>[5 POIN]</b> Fungsi dan Prosedur Dasar List Relasi (relasi.cpp)
	- 3 prosedur insert dan 3 prosedur delete (first, last, after)
	- fungsi findElm, mencari elemen berdasarkan address parent dan address child
	- prosedur printInfo, menampilkan ID parent dan ID child saja
	- fungsi/prosedur dasar lainnya: alokasi, createList, dealokasi
	
### MENU APLIKASI (aplikasi.cpp)
 1. <b>[5 POIN]</b> Insert Data Parent
	- menerima input ID dan atribut
	- mengecek apakah ID sudah ada 
	- insert data ke list dalam
	- hasil insert terurut berdasarkan ID
 2. <b>[5 POIN]</b> Insert Data Child
	- menerima input ID dan atribut
	- mengecek apakah ID sudah ada 
	- insert data ke list dalam
	- hasil insert terurut berdasarkan ID
 3. <b>[5 POIN]</b> View Data Parent
	- sesuai printInfo Parent
	- menampilkan pesan jika data kosong
 4. <b>[5 POIN]</b> View Data Child
	- sesuai printInfo Child
	- menampilkan pesan jika data kosong
 5. <b>[5 POIN]</b> Search Data Parent
	- menerima input ID 
	- findElm
	- menampilkan detil data jika ID ditemukan (ID dan 5 atribut)
 6. <b>[5 POIN]</b> Search Data Child
	- menerima input ID 
	- findElm
	- menampilkan detil data jika ID ditemukan (ID dan 5 atribut)
 7. <b>[5 POIN]</b> Relasikan Parent dengan Child (Insert Data Relasi)
	- menerima input ID parent dan ID child
	- mengecek apakah ID parent dan ID child ada
	- mengalokasikan elemen relasi, insert last ke list Relasi
 8. <b>[5 POIN]</b> View Data Relasi
	- sesuai printInfo Relasi
	- menampilkan pesan jika data kosong
 9. <b>[5 POIN]</b> Search Data Relasi
	- menerima input ID parent dan ID child
	- mengecek apakah ID parent dan ID child ada
	- menampilkan status apakah ada relasi dari ID parent dan ID child
 10. <b>[5 POIN]</b> Putus Relasi Parent dengan Child (Delete Data Relasi)
	- menerima input ID parent dan ID child
	- mengecek apakah ID parent dan ID child ada
	- mengecek apakah ada elemen relasi yang menghubungkan elemen parent dengan child
	- menghapus elemen relasi jika ditemukan (dealokasi)
 11. <b>[10 POIN]</b> Delete Data Parent
	- menerima input ID
	- menghapus semua relasi dengan elemen jika ID ditemukan (dealokasi)
	- menghapus data jika ID ditemukan (dealokasi)
 12. <b>[10 POIN]</b> Delete Data Child
	- menerima input ID
	- menghapus semua relasi dengan elemen jika ID ditemukan (dealokasi)
	- menghapus data jika ID ditemukan (dealokasi)
 13. <b>[10 POIN]</b> Urutkan Data Relasi
	- mengurutkan data relasi berdasarkan ID parent

### Contoh lihat di Tubes2016_2.rar
#### parent.h
![parent.h](/parent.h.jpg)
#### child.h
![child.h](/child.h.jpg)
#### parent.h
![relasi.h](/relasi.h.jpg)
#### aplikasi.h
![aplikasi.h](/aplikasi.h.jpg)
#### aplikasi.cpp
![aplikasi.cpp](/aplikasi.cpp.jpg)
