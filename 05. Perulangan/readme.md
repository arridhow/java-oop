[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Perulangan

Perulangan dalam pemrograman dibagi manjadi dua jenis:

1. Counted loop: Perulangan yang jumlah pengulangannya terhitung atau tentu.
2. Uncounted loop: Perulangan yang jumlah pengulangannya tidak terhitung atau tidak
tentu.

## 1. Counted Loop
Seperti yang sudah dijelaskan, perulangan ini memiliki jumlah pengulangan yang tentu dan terhitung.

Perulangan ini terdiri dari perulangan For dan For each.

Mari kita bahas satu per satu…

### A. Perulangan For
Format penulisan perulangan For di java adalah sebagai berikut:

```java
for( int hitungan = 0; hitungan <= 10; hitungan++ ){
    // blok kode yang akan diulang
}
```

Penjelasan:

variabel hitungan tugasnya untuk menyimpan hitungan pengulangan.
hitungan <= 10 artinya selama nilai hitungannya lebih kecil atau sama dengan 10, maka pengulangan akan terus dilakukan. Dengan kata lain, perualangan ini akan mengulang sebanyak 10 kali.
hitungan++ fungsinya untuk menambah satu (+1) nilai hitungan peda setiap pengulangan.
Blok kode For dimulai dengan tanda ‘{’ dan diakhiri dengan ‘}’.

### B. Perulangan For Each
Perulangan ini sebenarnya digunakan untuk menampilkan isi dari array.

Apa itu array?

Singkatnya, array itu variabel yang menyimpan lebih dari satu nilai dan memiliki indeks.

Selengkapnya, nanti bisa di pelajari pada materi: Mengenal Array di Java.

Lanjut…

Perulangan For Each pada Java, dilakukan juga dengan kata kunci For.

Contohnya seperti ini:
```java
for ( int item : dataArray ) {
    // blok kode yang diulang
}
```

# Uncounted Loop
Seperti yang sudah dijelaskan di awal tadi, perulangan ini tidak jelas jumlah pengulangannya.

Tapi, tidak menutup kemungkinan juga, jumlah pengulangannya dapat ditentukan.

Perulangan uncounted loop terdirid dari perulangan While dan Do/While.


### A. Perulangan While
While bisa kita artikan selama.

Cara kerja perulangan ini seperti percabangan, ia akan melakukan perulangan selama kondisinya bernilai true.

Struktur penulisan perulangan while:

```java
while ( kondisi ) {
    // blok kode yang akan diulang
}
```

### B. Perulangan Do/While
Cara kerja perulangan Do/While sebenarnya sama seperti perulangan While.

Bedanya, Do/While melakukan satu kali perulangan dulu. Kemudian mengecek kondisinya.

Flowchart perulangan do/while
Struktur penulisannya seperti ini:

```java
do {
    // blok kode yang akan diulang
} while (kondisi);
```

[contributors-shield]: https://img.shields.io/github/contributors/arridhow/web-resume.svg?style=for-the-badge
[contributors-url]: https://github.com/arridhow/java-oop/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arridhopradana
