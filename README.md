# Exercise - LOOP

## Nama: Muhammad Rayhan Rohadi

### Nomor 1

#### Penjelasan:

1. Pertama-tama, saya membuat sebuah `FOR LOOP` dengan inisialisasi variabel `i` sama dengan `1`, kondisi looping selama `i` kurang dari atau sama dengan `100`, dan setiap kali looping berjalan increment nilai `i` dengan `1`.
2. Di dalam `FOR LOOP`, saya menggunakan method `document.write()` untuk menampilkan teks "User ke-n" di setiap baris di HTML. Saya menggabungkan string "User ke-" dengan nilai variabel `i` dan menambahkan tag `<br>` untuk membuat baris baru setiap kali looping berjalan.

### Nomor 2

#### Penjelasan:

1. Pertama-tama, saya membuat sebuah variabel `nilai` dengan nilai awal `0`.
2. Kemudian membuat sebuah `FOR LOOP` dengan inisialisasi variabel `i` sama dengan `1`, kondisi looping selama `i` kurang dari atau sama dengan `10`, dan setiap kali looping berjalan increment nilai `i` dengan `1`.
3. Di dalam `FOR LOOP`, saya melakukan penambahan nilai variabel `nilai` sebesar `2` pada setiap pengulangan dan menampilkan hasil penambahan tersebut menggunakan method `document.write()` di HTML. Saya menggabungkan string "Nilai setelah penambahan ke-" dengan nilai variabel `i` dan nilai variabel `nilai` dan menambahkan tag `<br>` untuk membuat baris baru setiap kali looping berjalan.

### Nomor 3

#### Penjelasan:

1. Pertama-tama, saya membuat sebuah `FOR LOOP` dengan inisialisasi variabel `i` sama dengan `0`, kondisi looping selama `i` kurang dari atau sama dengan `20`, dan setiap kali looping berjalan increment nilai `i` dengan `1`.
2. Di dalam `FOR LOOP`, saya menggunakan statement kondisional `IF ELSE` untuk mengecek apakah nilai variabel `i` adalah bilangan genap atau ganjil. Untuk mengecek bilangan genap, saya menggunakan operator modulus `%` dengan nilai `2` dan memeriksa apakah hasilnya adalah `0`. Jika `i` modulus `2` sama dengan `0`, maka nilai tersebut adalah bilangan genap. Jika nilai variabel `i` bukan bilangan genap, maka akan dianggap sebagai bilangan ganjil.
3. Kemudian, tinggal menampilkan keterangan "bilangan genap" atau "bilangan ganjil" di HTML pada setiap nilai variabel `i` yang diiterasi menggunakan method `document.write()` dan menambahkan tag`<br>` untuk membuat baris baru setiap kali looping berjalan.

### Nomor 4

#### Penjelasan:

1. Pertama-tama, saya akan mendefinisikan variabel `count` dengan nilai awal `0`. Variabel ini akan digunakan untuk menghitung jumlah kali user memilih 'OK'.
2. Selanjutnya, saya membuat sebuah fungsi `showConfirm()` yang akan menampilkan konfirmasi pop up menggunakan `confirm()`.
3. Di dalam fungsi `showConfirm()` akan menyimpan hasil dari konfirmasi pop up ke dalam variabel `result`.
4. Kemudian menggunakan statement kondisional `if` untuk memeriksa apakah user memilih 'OK' atau 'Cancel'. Jika user memilih 'OK', maka nilai variabel `count` akan diincrement dan fungsi `showConfirm()` akan dipanggil kembali. Jika user memilih 'Cancel', maka program akan menampilkan teks "Perulangan sudah dilakukan sebanyak (jumlah klik OK yang dilakukan user)" menggunakan `alert()`.
5. Fungsi `showConfirm()` akan dipanggil pertama kali di akhir program, sehingga konfirmasi pop up akan ditampilkan terus menerus sampai user memilih 'Cancel'.

### Nomor 5

#### Penjelasan:

1. Pertama-tama, saya mendefinisikan variabel `answer` dengan jawaban yang benar.
2. Kemudian membuat sebuah fungsi `quiz()` yang akan menampilkan `prompt()` untuk meminta inputan dari user.
3. Fungsi `quiz()` menyimpan hasil inputan dari user ke dalam variabel `userAnswer`.
4. Selanjutnya menggunakan statement kondisional IF untuk memeriksa apakah jawaban dari user sudah benar atau belum. Jika jawaban benar, maka program akan menampilkan `alert()` "Selamat! Jawaban kamu benar!". Jika jawaban salah, maka program akan memanggil kembali fungsi `quiz()` untuk menampilkan `prompt()` yang sama hingga jawaban dari user benar.
5. Fungsi `quiz()` dipanggil pertama kali di akhir program, sehingga kuis akan dimulai dengan menampilkan `prompt()` untuk meminta inputan dari user. Ketika jawaban dari user sudah benar, program akan menampilkan teks "Selamat! Jawaban kamu benar!"
