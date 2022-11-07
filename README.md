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
#perulangan 
 1) latihan perulangan seperti berikut
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







