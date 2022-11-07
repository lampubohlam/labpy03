# tugas 7
  Nama : abdul aziz
   Kelas :TI.22.A.1
   NIM : 312210022
# kondisi dan perulangan
# latihan 1
buat program sederhana dengan input 2 menggunakan if
seperti  gambar berikut :![Screenshot (96)](https://user-images.githubusercontent.com/116137169/200239331-aa288c1d-628c-4927-9c97-4a023ceed599.png)


lalu jalankan programnya dan masukan Nilai A dan nilai B, dan programnnya akan mencari bilangan terbesar seperti gambar berikut ![Screenshot (97)](https://user-images.githubusercontent.com/116137169/200239699-e60b0836-63af-4d07-903e-abe4d8222a3c.png)
print('Menentukan bilangan terbesar dari 2 bilangan')
        
        
        
              print('Menentukan bilangan terbesar dari 2 bilangan')
              a = int(input("Masukkan nilai A:"))
              b = int(input("Masukkan nilai B:"))
              if a > b:
                 print("A =", a, "yang terbesar")
              elif b > a:
                 print("B=", b, "yang terbesar")   
    
# latihan2
selanjutnya kita akan mengurutkan bilangan yang terkecil ke yang terbesar
  buatlah file baru terlebih dahulu
  lalu masukan coding seperti berikut
  ![Screenshot (98)](https://user-images.githubusercontent.com/116137169/200241094-a1832f0d-d4d0-4113-b859-1775cc4b3e61.png)
dan jalankan filenya maka akan seperti ini
  ![Screenshot (98)](https://user-images.githubusercontent.com/116137169/200241408-231c6255-ef4b-409c-acec-009625ac8b70.png)
  lalu masukan angka yang ingin di urutkan
  contoh angka pertama=1
               kedua  =14
               ketiga =12
                "jika coding sukses maka urutannya akan benar 1,12,14" seperti gambar berikut
                ![Screenshot (99)](https://user-images.githubusercontent.com/116137169/200241810-223001ff-a14b-4f09-93df-a8334d2eba3f.png)

           
           
       print("_____Mengurutkan bilangan dari yang terkecil ke yang terbesar_____")
       print("Masukan 3 bilangan yang akan diurutkan:")
       a = int(input("masukkan bilangan 1 = "))
       b = int(input("masukkan bilangan 2 = "))
       c = int(input("masukkan bilangan 3 = "))

           if a < b and a < c:
           if b < c:
            print(a, b, c)
       else:
          print(a, c, b)
       elif b < a and b < c:
          if a < c:
            print(b, a, c)
       else:
          print(b, c, a)
       else:
         if a < b:
          print(c, a, b)
       else:
        print(c, b, a)
 # perulangan 
 1)  latihan perulangan seperti berikut
 ![perulangan](https://user-images.githubusercontent.com/116137169/200244639-6a6f9914-535c-41c0-9280-4f6a829325f5.png)
  buat file terlebih dahulu 
petana-tama masukan kode coding seperti gambar dibawah ini
  ![Screenshot (100)](https://user-images.githubusercontent.com/116137169/200244957-d8d54d3d-445d-4817-94d9-65d8bd1c7ae4.png)
 lalu klik run dan jalankan programnya
 ![Screenshot (101)](https://user-images.githubusercontent.com/116137169/200245763-5b7ed363-5cf2-4b94-92ca-af35657db341.png)
   
   berikut codingnya
   
          for i in range(0,10):
    print()
    print(i, end="\t")
    for j in range(1,10):
        print(i+j,end="\t")
        
 2) latihan2 
 
 menampilkan bilangan n acak yang lebih kecil dari 0,5 
 seperti gambar berikut
 kombinasikanlah while dan for
 buatlah programnya seperti berikut
 ![Screenshot (104)](https://user-images.githubusercontent.com/116137169/200248269-0c468bdf-794e-473b-a22b-2e0f1a4b339b.png)
 lalu masukan berapa perulangan yang ingin dimasukan,disini saya memasukan 10
 lakukan jalankan file nya
 ![Screenshot (106)](https://user-images.githubusercontent.com/116137169/200248503-3b042f89-8f48-4567-9ebe-072ed361c7fa.png)
 
 
 
from random import random
n = int(input ("masukan beberapa perulangan"))
while n==n: 
    break
for i in range(n):
    bil = random( )%0.5
    print('perulangan ke : ',bil)
    

# modul praktikum 2&3
 buatlah program berikut untuk menentukan nilai mana yang lebih besar
![Screenshot (107)](https://user-images.githubusercontent.com/116137169/200251259-37fd922e-1f9a-416b-9d36-e95f28c9865c.png)
lalu run file
![Screenshot (109)](https://user-images.githubusercontent.com/116137169/200251836-459b687a-67d1-44db-bcfc-9df0c841a71e.png)
   
   print("_____Abdul aziz____")
a, b, c =(
    int(input("masukan nilai a: " )),
    int(input("masukan nilai b: ")),
    int(input("masukan nilai c: "))
)
if a>b and a<c:
    print("A yang terbesar")
elif b>a and b>c:
    print("B yang terbesar")
else:
    print("C yang terbesar")
# algoritma
membuat algoritma dari latihan 1
masukan import fungsi Random terlebih dahulu
masukan n=int input("masukan nilai")
masukan kombinasi for
masukan nilai jumlah (n) : 5
Mencetak data ke 1 sampai 5 dengan nilai kurang dari 0,5.![Screenshot (111)](https://user-images.githubusercontent.com/116137169/200254295-1af28c5f-0098-4e14-be3f-a6dcb796c16b.png)
jalankan file dan masukan nilai
dan sukses
    print("bilangan acak yang lebih kecil dari o.5")
import random

n = int(input("masukan nilai:"))
a = 0
for c in range(n):
    a += 1
    b = random.uniform(.0, .5)
    print("data ke:", a, "==>", b)

print("succes")

2) algoritma 2
   buatlah program berikut ini untuk menentukan angka/bilangan terbesar dari berapapun banyak nilai yang akan di input
   dan diakhiri dengan angka 0
   
   ![Screenshot (112)](https://user-images.githubusercontent.com/116137169/200255919-fc8f9bdd-ee5d-4a5a-a93a-accb6b258722.png)

# algoritma program
  1.Mulai

2.Mencetak latihan1

3.Mencetak "Program menghitung laba dengan modal awal 100 juta"

4.Membuat Note

5.Mencetak Bulan pertama dan kedua = 0%

6.Mencetak bulan ke 3 = 1%

7.Mencetak bulan ke 5 = 5%

8.Mencetak bulan ke 8 = 2%

9.integer a = 100.000.000( modal awal)

10.Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.

11.Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8

12.bulan pertama dan kedua laba adalah 0

13.bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan

14.bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan

15.Bulan ke 8 mmendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.

16.Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat.

17.Selesai![Screenshot (113)](https://user-images.githubusercontent.com/116137169/200256432-a33e666a-a313-4a36-b006-7296d5544153.png)
![Screenshot (114)](https://user-images.githubusercontent.com/116137169/200256701-82a5e8f5-5fea-430d-86c4-f3206d3eaf12.png)

    








