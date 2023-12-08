1. Buatlah perulangan hingga 100 menggunakan Python dengan output sebagai berikut:
   
---jawaban---
   
![readmi 2](https://github.com/yumajuliana/yumajuliana/assets/150018196/86ff408d-8a9d-4ba7-bf2b-e4f4d513b4a2)

your_name = "your name"

for i in range(1, 101):

if i % 10 == 0:

print(your_name * 3) 

else:

print(i, end=' ')
        
---Penjelasan kode :---

your_name = "your name" -> kode ini adalah kode yang mendifinisan subuah variabel dengan nama your name dan juga memberikan nilai string your name kode ini tidak digunakan dalam loop 

for i in range(1, 101): -> ini adalah loop for yang akan berinteraksi dari anka 1- 100 dengan variabel i dan kode ini akan mengambil nilai dari rentang 1-100 

 if i % 10 == 0: -> kode ini di gunakan untuk pengecekan pada setiap interaksi melakukan pengecekan dengan apakah nilai i habis dibagi dengan 10 sedangkan 10 ini modulus = 0 yang artinya adalah bahwa i merupakan kelipatan dari 10 

  print(your_name * 3)  -> kode ini di gunakan untuk mencetak kata your name dimana jika kondisi tersebut terpenuhi makan akan mencetak kata your name sebanyak tiga kali dengan kode  print(your_name * 3) 

print(i, end=' ')   ->  kode ini di gunakan untuk jika kondisi i tidak terpenuhi yang artinya i bukan kelipatan 10 maka kode ini akan mencetak nilai i sendiri dengan kode print(i, end=' ')   untuk menggantikan karakter baris baru yang di cetak oleh fungsi print.


![luaran readmi 2](https://github.com/yumajuliana/yumajuliana/assets/150018196/d0873178-9c7f-4195-b3a2-6ce9682470d7)

ini adalah hasi output dari kode diatas 

2. Buatlah program bebas, dengan menerapkan if else pada:
   
a. For Loops

b. While Loops

---jawaban---

a. For Loops

![kode readmi 3](https://github.com/yumajuliana/yumajuliana/assets/150018196/830d1651-6d86-4793-9725-a0d7c6f9a80f)

batas_bawah = 1

batas_atas = 10

jumlah_ganjil = 0

jumlah_genap = 0

for angka in range(batas_bawah, batas_atas + 1):

if angka % 2 == 0:

jumlah_genap += 1

else:
 
 jumlah_ganjil += 1
 
print(f"Jumlah bilangan genap dalam rentang {batas_bawah}-{batas_atas}: {jumlah_genap}")

---penjelasan kode---

batas_bawah = 1  -> kode ini digunakan untuk menentukan batas bawah rentang nilainya adalah 1-10 sedangkan batas bawahnya adalah 1 "batas_atas = 10" sedangkan kode ini adalah di gukan untuk menentukan batas 

jumlah_ganjil = 0 -> variabel ini digunakan untuk menyimpan jumlah bilangan ganjil dari rentang nilai yang telah ditentukan yaitu 1-10  variabel ini di inisialisasi dengan nilai 0 "jumlah_genap = 0" sedangkan kode ini digunkan untuk menyimpan jumlah bilangan genap dari rentang nilai 1-10 variabel ini juga di inisialisasi dengan nilai 0 

for angka in range(batas_bawah, batas_atas + 1): -> ini adalah for loops yang akan berinteraksi dengan semua angka dalam rentang batas bawah hinngga batas atas untuk setiap interasksi itu dilakukan pengecekan dengan "if angka % 2 == 0:" maka ini akan memeriksa apakah angka tersebut habis dibagi dengan 2 jika habis dibagi 2 makan angka tersebut merupakan bilangan genap jika kondisi terpenuhi makan jumlah genap akan ditambah satu dengan kode ini "jumlah_genap += 1" jika tidak (else) akan di eksekusi dan jumlah ganjil akan di tambah 1 kemudian jika loop sudah selesai maka kode "print" akan mencetak hasilnya

---luaran / ouput dari kode di atas 

![luaran readmi 3](https://github.com/yumajuliana/yumajuliana/assets/150018196/f3ece849-429c-49ad-a8f4-8386bc784e5d)




 


