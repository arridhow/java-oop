[![Contributors][contributors-shield]][contributors-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

# Operator
Operator dalam pemrograman digunakan untuk melakukan operasi tertentu.

Misalkan kita ingin menjumlahkan nilai dari variabel x dan y, maka kita bisa
menggunakan operator penjumlahan (+).

Ada enam jenis kelompok operator dalam pemrograman Java:

<ul>
    <li>Operator Artimatika</li>
    <li>Operator Penguasan</li>
    <li>Operator Pembanding</li>
    <li>Operator Logika</li>
    <li>Operator Bitwise</li>
    <li>Operator Ternary</li>
</ul>

<h1>Operasi Aritmatika</h1>

| Nama	        | Simbol    |
| ------------- | --------- |
| Penjumlahan   | +         |
| Pengurangan   | -         |
| Perkalian	    | *         |
| Pembagian	    | /         |
| Sisa Bagi	    | %         |

<h1>Operasi Penugasan</h1>

|Nama Operator|	Sombol|
|---|---|
|Pengisian Nilai|	=|
|Pengisian dan Penambahan	|+=|
|Pengisian dan Pengurangan|	-=|
|Pengisian dan Perkalian	|*=|
|Pengisian dan Pembagian	|/=|
|Pengisian dan Sisa bagi	|%=|

<h1>Operasi Pembanding</h1>

|Nama	|Simbol|
|--|--|
|Lebih Besar	|>|
|Lebih Kecil	|<|
|Sama Dengan	|==|
|Tidak Sama dengan|	!=|
|Lebih Besar Sama dengan|	>=|
|Lebih Kecil Sama dengan|	<=|

<h1>Operasi Logika</h1>

|Nama	|Simbol di Java|
|--|-|
|Logika AND|	&&|
|Logika OR|	\|\| |
|Negasi/kebalikan|	!|

<h1>Opeasi Bitwise</h1>

|Nama	|Simbol di Java|
|--|--|
|AND	&|
|OR	\| |
|XOR	|^|
|Negasi/kebalikan|	~|
|Left Shift|	<<|
|Right Shift|	>>|
|Left Shift (unsigned)	|<<<|
|Right Shift (unsigned)|	>>>|

<h1>Operasi Tenary</h1>
Simbolnya menggunakan tanda tanya (?) dan titik-dua (:) untuk memisah jawabannya.

```
Pertanyaan ? kondisi true : kondisi false
```
contoh :
```java
public class OperatorTernary {
    public static void main(String[] args) {

        boolean suka = true;
        String jawaban;

        // menggunakan operator ternary
        jawaban = suka ? "iya" : "tidak";

        // menampilkan jawaban
        System.out.println(jawaban);

    }
}
```
[contributors-shield]: https://img.shields.io/github/contributors/arridhow/web-resume.svg?style=for-the-badge
[contributors-url]: https://github.com/arridhow/web-resume/graphs/contributors
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/arridhopradana
