Hasil latihan 1


![Cuplikan layar 2024-11-07 101302](https://github.com/user-attachments/assets/d4067c01-a40e-489b-999f-4ee74e47f70f)

Code


![Cuplikan layar 2024-11-07 101307](https://github.com/user-attachments/assets/9a0d6d2b-268d-4a8e-a483-df19a358a737)

1.Penjelasan alur algoritma program
Import Library:

import random
Fungsi ini digunakan untuk mengimpor pustaka random yang menyediakan berbagai fungsi untuk menghasilkan bilangan acak.

2.Meminta Input dari Pengguna:

python
Salin kode
n = int(input("Masukkan nilai N: "))
Program meminta pengguna untuk memasukkan sebuah bilangan bulat yang akan disimpan dalam variabel n. Nilai n menunjukkan berapa banyak bilangan acak yang akan dihasilkan oleh program.

3.Looping untuk Menghasilkan Bilangan Acak:

python
Salin kode
for i in range(1, n + 1):
Program menggunakan perulangan for dari i = 1 hingga i = n. Setiap iterasi akan menghasilkan satu bilangan acak.

4.Menghasilkan Bilangan Acak:

python
Salin kode
bilangan_acak = random.uniform(1, 5)
Di setiap iterasi, program menggunakan random.uniform(1, 5) untuk menghasilkan bilangan acak desimal di antara 1 dan 5. Nilai ini disimpan dalam variabel bilangan_acak.

5.Menampilkan Hasil Bilangan Acak:

python
Salin kode
print(f"data ke: {i} => {bilangan_acak}")
Program mencetak hasil bilangan acak yang dihasilkan pada setiap iterasi, diikuti oleh indeks data (data ke: i), untuk menunjukkan urutan bilangan acak yang dihasilkan.

6.Akhir Program:

python
Salin kode
print("Selesai")
Setelah perulangan selesai, program mencetak "Selesai" sebagai penanda bahwa seluruh proses telah berakhir.




Hasil latihan 2



![Cuplikan layar 2024-11-07 102849](https://github.com/user-attachments/assets/52fc5d95-7d25-4843-90bd-5dd1fdf6a6ae)


Code


![Cuplikan layar 2024-11-07 102854](https://github.com/user-attachments/assets/51fa2ec0-3cdf-41f1-bc81-2f9736ad55e2)

1.Penjelasan alur algortima program
Inisialisasi Variabel: Program memulai dengan mendefinisikan dua variabel, laba dan total_laba, keduanya diberi nilai awal 0. Variabel laba digunakan untuk menyimpan laba di setiap bulan, sementara total_laba akan menyimpan akumulasi laba dari bulan pertama hingga bulan kedelapan.

2.Loop Perulangan dari Bulan 1 hingga 8: Program menggunakan perulangan for bulan in range(1, 9) untuk menjalankan perhitungan dari bulan pertama (bulan=1) hingga bulan kedelapan (bulan=8). Variabel bulan pada setiap iterasi akan menunjukkan bulan yang sedang dihitung.

3.Menentukan Besar Laba Berdasarkan Bulan: Di dalam setiap iterasi, program menentukan laba berdasarkan aturan laba yang sudah didefinisikan:
Jika bulan adalah 1 atau 2, nilai laba diset ke 0 karena pada bulan-bulan ini tidak ada laba.
Jika bulan adalah 3 atau 4, laba ditetapkan sebesar 10.000.000 rupiah.
Jika bulan adalah 5, 6, atau 7, laba ditetapkan sebesar 40.000.000 rupiah.
Jika bulan adalah 8, laba ditetapkan sebesar 300.000.000 rupiah.
Program memeriksa kondisi-kondisi ini menggunakan struktur kontrol if, elif, dan else untuk menetapkan nilai laba di setiap bulan.

4.Menampilkan Laba Bulanan: Setelah menentukan besar laba pada bulan tersebut, program menampilkan laba bulan itu dengan menggunakan fungsi print. Format tampilan adalah laba bulan ke- {bulan} sebesar: {laba}, di mana variabel bulan dan laba akan menampilkan angka bulan dan jumlah laba masing-masing.

5.Menghitung Total Laba: Di akhir setiap iterasi, program menambahkan nilai laba bulan tersebut ke dalam total_laba menggunakan total_laba += laba. Langkah ini memungkinkan program untuk mengakumulasikan laba bulanan sehingga pada akhir perulangan, total_laba akan berisi total dari semua laba yang diperoleh selama delapan bulan.

6.Menampilkan Total Laba Keseluruhan: Setelah perulangan selesai, program keluar dari loop dan menampilkan total_laba dengan pernyataan print(f"Total laba adalah: {total_laba}"). Pada tahap ini, total_laba telah memuat jumlah keseluruhan laba yang diperoleh selama periode delapan bulan.





Latihan 3



![Cuplikan layar 2024-11-07 103654](https://github.com/user-attachments/assets/0c13291c-888a-4276-a874-2be1beb745ab)

Code


![Cuplikan layar 2024-11-07 103703](https://github.com/user-attachments/assets/5d751320-5a2a-413f-92ba-d06d8c7f5fb1)

Penjelasan alur algoritma
1.Definisi Fungsi atm(): o Program dimulai dengan mendefinisikan fungsi atm(). Fungsi ini akan menjalankan seluruh logika program ATM.

2.Inisialisasi Saldo: o Di dalam fungsi atm(), variabel saldo diinisialisasi dengan nilai 1000000. Ini mewakili saldo awal di rekening pengguna.

3.Perulangan Utama: o while True: memulai sebuah perulangan tak terbatas. Perulangan ini akan terus berjalan hingga pengguna memilih untuk keluar dari program. o Di dalam perulangan, program akan terus menampilkan menu pilihan kepada pengguna.

4.Menampilkan Menu: o Program menampilkan saldo saat ini dan dua pilihan:

5.Tarik Uang

6.Keluar

7.Meminta Input Pengguna: o Pengguna diminta untuk memilih salah satu opsi dengan memasukkan angka 1 atau 2. Pilihan pengguna disimpan dalam variabel pilihan.

8.Percabangan Kondisi: o Pilihan 1 (Tarik Uang): Pengguna diminta untuk memasukkan jumlah uang yang ingin ditarik. Jumlah penarikan diperiksa apakah lebih kecil atau sama dengan saldo yang ada. Jika saldo mencukupi, maka saldo akan dikurangi dengan jumlah penarikan dan menampilkan pesan "Penarikan berhasil!". Jika saldo tidak mencukupi, maka akan ditampilkan pesan "Saldo tidak mencukupi!". o Pilihan 2 (Keluar): Perulangan akan dihentikan dengan perintah break. o Pilihan Tidak Valid: Jika pengguna memasukkan pilihan selain 1 atau 2, maka akan ditampilkan pesan "Pilihan tidak valid!".

9.Panggilan Fungsi: o Di akhir program, fungsi atm() dipanggil untuk memulai eksekusi program. Algoritma dalam Bentuk Langkah-langkah Sederhana:

10.Mulai program.

11.Inisialisasi saldo dengan nilai tertentu.

12.Tampilkan menu pilihan kepada pengguna.

13.Minta pengguna memilih opsi.

14.Jika pengguna memilih "Tarik Uang": o Minta pengguna memasukkan jumlah yang ingin ditarik.

