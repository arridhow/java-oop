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
      <a href="#top">07. Method</a>
      <ul>
        <li><a href="#definisi">Definisi</a></li>
        <li><a href="#membuat-method">Membuat Method</a></li>
        <li><a href="#memanggil-method">Memanggil Method</a></li>
        <li><a href="#parameter-dan-argumen">Parameter dan Argumen</a></li>
        <li><a href="method-dengan-return-value">Method dengan Return Value</a></li>
        <li><a href="#referensi">Referensi</a></li>
      </ul>
    </li>
  </ul>
</details>

## Definisi

- Method (atau di dalam **Pemrograman Prosedural** disebut **Fungsi**) adalah bagian dari kode pemrogramman yang hanya akan berjalan ketika dipanggil.
- Kita bisa melempar Data (atau Parameter) ke dalam **Method**.
- **Method** digunakan agar kita tidak perlu mengulang penulisan kode yang sama (_reusable_).

## Membuat Method

```java
public class Main {
  static void namaMethod() {
    // blok kode
  }
}
```

- `namaMethod()` adalah nama dari **method**.
- `static` mendandakan `namaMethod()` adalah **method** dari _class_ `Main`, bukan objek dari _class_ `Main`.
- `void` menandakan **method** `namaMethod()` tidak mengembalikan nilai apapun (_void_ / kosong).

## Memanggil Method

```java
public class Main {
  static void namaMethod() {
    System.out.println("Halo, Dunia!");
  }

  public static void main(String[] args) {
    namaMethod();
    namaMethod();
    namaMethod();
  }
}
```

- Program diatas akan mengeluarkan _output_ `Halo, Dunia!` sebanyak 3 kali, karna `namaMethod()` dipanggil sebanyak 3 kali.

## Parameter dan Argumen

- Data atau Informasi dapat kita lempar ke **method** sebagai **parameter**.
- **Parameter** merupakan Variabel yang hanya dapat digunakan pada _scope_ **Method** itu sendiri.
- **Argumen** merupakan Data yang disimpan dalam **Parameter**.

```java
public class Main {
  static void cetakNamaUmur(String nama, int umur) {
    System.out.println("Aku "nama + ", " + umur + "tahun");
  }

  public static void main(String[] args) {
    cetakNamaUmur("Dho", 5);
    cetakNamaUmur("Khan", 8);
  }
}
```

- Program diatas akan mengeluarkan output
  ```
  Aku Dho, 5 tahun
  Aku Khan, 8 tahun
  ```

## Method dengan Return Value

```java
public class Main {
  static int aTambahB(int a, int b) {
    return x + y;
  }

  public static void main(String[] args) {
    System.out.println(aTambahB(6, 9));
  }
}
```

- Program diatas akan mengeluarkan output `15`.

## Referensi

[W3School - Method](https://www.w3schools.com/java/java_methods.asp)

[contributors-shield]: https://img.shields.io/github/contributors/arridhow/web-resume.svg?style=for-the-badge
[contributors-url]: https://github.com/arridhow/java-oop/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arridhopradana
