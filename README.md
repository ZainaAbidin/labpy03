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




