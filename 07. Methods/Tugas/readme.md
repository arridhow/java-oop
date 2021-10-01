# Praktikum PBO

## Tugas `07. Method`

---

#### Start

1 Oktober 2021

#### Deadline

8 Oktober 2021, 23:59 WIB.

#### Penalty

**nilai - (0.1% \* menit keterlambatan)**

#### Intruksi

- Fork Repository ini ([Tutorial](https://www.portaljawa.com/cara-fork-github-repository-dengan-mudah/))
- Kerjakan tugas berdasarkan file yang telah dibuat pada folder ini
- Poin per-soal adalah 100 poin yang kemungkinan akan dipecah menjadi sub-masalah yang memiliki poin tersendiri yang jika dijumlahkan akan kembali menjadi 100 poin
- Untuk mempermudah pembacaan, setiap algoritma atau kode blok **wajib** ditulis komentar
- Kerapihan program menjadi pertimbangan nilai, gunakan identasi yang baik.
- **Push** file tugas yang telah dikerjakan ke akun github masing-masing ([Tutorial](https://brianrakhmat.github.io/blog/begini-caranya-mengupload-project-ke-github/))
- Kirim **link file yang sudah di-push di github masing-masing** dan **sceenshoot hasil testcase** lalu kirim ke `arridho.pradana3990@student.unri.ac.id` dengan format subjek `PraktikumPBO-*nim*-*namaLengkap*-*xx.materi*` contoh : `PraktikumPBO-1907113990-arridhoPradana-07.method`
- Catatan : Waktu pengerjaan dan kecurangan dapat dilihat, _kerjain sendiri ye_.
- Catatan (lagi) : Siapin diri buat wawancara tugas satu-satu dengan waktu yang tidak ditentukan ;)

---

## [100 Poin] `T07AFraction`

Variabel $e1$ dan $d1$ dapat merepresentasikan pecahan $\frac{e1}{d1}$, sedangkan variabel $e2$ dan $d2$ menjadi $\frac{e2}{d2}$. Dimana $e1, d1, e2, d2$ merupakan bilangan bulat.

#### [50 Poin] `sumFraction()`

Buatlah method `sumFraction()` untuk menghitung penjumlahan kedua pecahan $\frac{e1}{d1}$ dan $\frac{e2}{d2}$. Hasil penjumlahan disimpan ke dalam variabel
$es$ dan $ds$ ($\frac{es}{ds}$) lalu dicetak dengan format keluaran `es / ds`, contoh `2 / 3`.
Hint : $\frac{es}{ds} = \frac{e1 * d2 + e2 * d1}{d1 * d2}$

#### [20 Poin] `productFraction()`

Buatlah method `sumFraction()` untuk menghitung perkalian kedua pecahan $\frac{e1}{d1}$ dan $\frac{e2}{d2}$. Hasil perkalian disimpan ke dalam variabel
$ep$ dan $dp$ ($\frac{ep}{dp}$) lalu dicetak dengan format keluaran `ep / dp`, contoh `2 / 3`.
Hint : $\frac{ep}{dp} = \frac{e1 * e2}{d1 * d2}$

#### [10 Poin] `printFraction()`

Buatlah method `printFraction()` untuk mencetak hasil keluaran penjumlahan ataupun perkalian pecahan untuk mengurangi *redundant* code.

#### [10 Poin] *Testcase*
- $\frac{1}{2} + \frac{1}{3}$
- $\frac{1}{3} + \frac{3}{4}$
- $\frac{1}{2} * \frac{2}{3}$
- $\frac{1}{4} * \frac{2}{3}$

#### [10 Poin] Solusi Optimal
Jika kita menggunakan rumus pada hint diatas untuk menlakukan penjumlahan $\frac{1}{2} + \frac{1}{2}$, hasil yang diperoleh adalah $\frac{2}{4}$, sedangkan $\frac{2}{4}$ masih bisa sederhakan lagi menjadi $\frac{1}{2}$. Buatlah solusi untuk menyederhakan hasil akhir pecahan (penjumlahan maupun perkalian).

----
#### Selamat Mengerjakan! 🤯🤯
- Tidak ada solusi yang benar-benar tepat. Jadi kerjakan sendiri sesuai kemampuan masing-masing
- Gunakanlah Text Editor ataupun IDE yang serasa paling nyaman, gak mesti VSCode, tapi disarankan sih 😎😎