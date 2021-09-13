[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Percabangan

Percabangan hanyalah sebuah istilah yang digunakan untuk menyebut alur program
yang bercabang.

Di dalam java, percabangan bisa dibuat menggunakan kata kunci if, else, switch, dan case, dan operator
ternary.

Sebelumnya, kamu perlu tahu dulu tiga bentuk percabangan pada Java:

1. Percabangan IF
2. Percabangan IF/ELSE
3. Percabangan IF/ELSE/IF atau SWITCH/CASE

## Percabangan IF
Percabangan ini hanya memiliki satu pilihan. Artinya, pilihan di dalam IF hanya
akan dikerjakan kalau kondisinya benar.

Tapi kalau salah… tidak akan melakukan apa-apa. Alias lanjut eksekusi ke
perintah berikutnya.

```java
if (suatu kondisi) {
    // maka kerjakan ini
    // kerjakan perintah ini juga
    // …
}
```

## Percabangan IF/Else
Sedangkan percabangan IF/ELSE memiliki pilihan alternatif kalau kondisinya salah.

IF: “Jika kondisi benar maka kerjakan ini, kalau tidak silahkan lanjut”

IF/ESLE: “Jika kondisi benar maka kerjakan ini, kalau salah maka kerjakan yang
itu, setelah itu lanjut”

```java
if (suatu kondisi) {
    // maka kerjakan ini
    // kerjakan perintah ini juga
    // …
else {
    // kerjakan ini kalau
    // semua kondisi di atas
    // tidak ada yang benar
    // …
}
```

## Percabangan IF/ELSE/IF dan SWITCH/CASE

Jika percabangan IF/ESLE hanya memiliki dua pilihan saja. Maka percahangan
IF/ELSE/IF memiliki lebih dari dua pilihan.

```java
if (suatu kondisi) {
    // maka kerjakan ini
    // kerjakan perintah ini juga
    // …
} else if (kondisi lain) {
    // kerjakan ini
    // kerjakan ini juga
    // …
} else if (kondisi yang lain lagi) {
    // kerjakan perintah ini
    // kerjakan ini juga
    // …
} esle {
    // kerjakan ini kalau
    // semua kondisi di atas
    // tidak ada yang benar
    // …
}
```
[contributors-shield]: https://img.shields.io/github/contributors/arridhow/web-resume.svg?style=for-the-badge
[contributors-url]: https://github.com/arridhow/web-resume/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arridhopradana
