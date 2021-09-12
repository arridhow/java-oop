[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<p align="center" id="top">
  <h1 style="padding-bottom:0" align="center">JAVA dan Pemrograman Berorientasi Objek</h1>
  <p align="center">
    Repositori ini dimaksudkan untuk praktikan mata kuliah PBO <a href="https://unri.ac.id/en/">Universitas Riau</a>. Materi dan tugas bisa dilihat pada masing-masing folder pada repo ini.
    <br />
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ul>
    <li>
      <a href="#top">0. Pendahuluan</a>
      <ul>
        <li><a href="#prasyarat">Prasyarat</a></li>
        <li><a href="#hello-world">Hello, World!</a></li>
        <li><a href="#penjelasan-hello-world">Penjelasan Hello, World!</a></li>
        <li><a href="#referensi">Referensi</a></li>
      </ul>
    </li>
  </ul>
</details>

## Prasyarat

- [JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
- Text Editor (Notepad, [Visual Studio Code](https://code.visualstudio.com/download), Etc.)

## Hello, World!

`Hello, World!` di Java.

```java
//Hello, World!
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello, World!");
  }
}
```

- Buat sebuah file dengan nama `HelloWorld.java`
- Salin kode diatas
- Buka Terminal
- Pada direktori file, ketik `javac HelloWorld.java`
- ketik `java HelloWorld`
- Selanjutnya akan keluar tulisan seperti dibawah:

#### `Hello, World`

## Penjelasan `Hello, World!`

### `class HelloWorld`

- Setiap baris kode yang berjalan di Java harus berada di dalam `class`
- `class` di Java harus dimulai dengan huruf besar
- Pada program diatas kita menamakan `class` kita dengan `HelloWorld`
- Java merupakan bahasa pemrograman yang **case-sensitive** artinya `HelloWorld` tidak sama dengan `Helloworld`
- Penamaan `class` di Java biasanya menggunakan aturan [PascalCase](https://wiki.c2.com/?PascalCase)
- Nama file harus sama dengan nama `class`

### `main()` method
- Setiap program Java harus ada di dalam `main()` method
- Compiler Java mengeksekusi `main()` method pertama kali saat program dieksekusi

### `println()` method
- `System.out.println()` merupakan perintah untuk mencetak text ke layar

### Comments di Java
- Comments biasanya digunakan programmer untuk menjelaskan kode dan mempermudah pembacaan kode
- Comments akan diabaikan (tidak dieksekusi) oleh **Compiler**
- **Single-line Comments** pada Java diawali dengan `//` dan diikuti komentar/penjelasan itu sendiri.
- **Multi-line Comments** pada Java diawali dengan `/*`, diikuti komentar/penjelasan itu sendiri, dan dikahiri dengan `*/`


## Referensi

[W3School](https://www.w3schools.com/java)
[ms.sapientia.ro - Java OOP](https://ms.sapientia.ro/~manyi/teaching/oop/oop_java.pdf)
[Progamiz](https://www.programiz.com/java-programming)

[contributors-shield]: https://img.shields.io/github/contributors/arridhow/web-resume.svg?style=for-the-badge
[contributors-url]: https://github.com/arridhow/web-resume/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arridhopradana
