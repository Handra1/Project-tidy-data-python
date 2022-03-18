# Project-tidy-data-python
This project about learning tidy data in python (In Indonesia)

Terdapat banyak variasi bentuk dan format dari sebuah data. Menurut Hadley Wickham, Phd tidy data merupakan cara memformalkan bentuk data dan memberi kita tujuan saat memformat data tersebut. Tidy data menyediakan cara standar untuk mengatur nilai data dalam suatu dataset.
Ada 3 prinsip dari tidy data:
- Kolom mewakili variabel terpisah.
- Baris mewakili pengamatan individu.
- Unit pengamatan untuk tabel
Pada data treatment kita, kolom tidak mewakili variabel terpisah. Karena kolom mewakili nilai yang berbeda untuk setiap variabel treatment. Kita dapat mere-organize nilai dari tabel tersebut menjadi format yang rapi atau tidy data.
kita akan menyimpan data treatment di dalam dataframe bernama df. Kemudian kita input kolom name sebagai id_vars parameter karena nilainya sudah fix atau konstan. Lalu kita input value_vars parameter untuk kolom yang ingin “cairkan” bersama, yaitu treatment a dan treatment b.
