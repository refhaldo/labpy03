# Tugas Praktikum 3
## Latihan 1 : latihan1.py
### 1. Penjelasan Program
Program ini digunakan untuk menampilkan bilanga acak yang kurang dari o.5.
### 2. Kode Program
Berikut ini adalah kode dari program tersebut :

        print ('Masukan nilai N: 5')
        import random
        jumlah = 5
        a = 0
        for i in range(jumlah):
          x = random.uniform(.0,.5)
          a += 1
        print ('data ke:',a,'=>',x)
        print('Selesai')
### 3. Eksekusi Program
![image](https://github.com/refhaldo/labpy03/blob/master/latihan1.png?raw=true)
## Latihan 2 : latihan2.py
### 1.Penjelasan Program
Program ini digunakan untuk mencari angka terbesar dari angka yang di inputkan.
### 2. Kode Program
Berikut ini adalah kode dari program tersebut :

        max=0
        while True:
	        a=int(input('Masukan bilangan:'))
	        if max<a:
	         max=a
	        if a==0:
	         break
        print ('Bilangan terbesar adalah:',max)

**Keterangan**
Program diatas akan berhenti melakukan inputan apabila kita menginputkan angka 0.
### 3. Eksekusi Program
![image](https://github.com/refhaldo/labpy03/blob/master/latihan2.png?raw=true)
## Tugas Praktikum 3 : program1.py
### 1.Penjelasan Program
Program ini digunakan untuk menentukan laba selama 8 bulan dari seorang pengusaha yang memulai usahanya dengan modal awal 100 juta, bila pada bulan pertama dan kedua belum mendapatkan laba, pada bulan ketiga baru mulai mendapatkan laba sebesar 1% dan pada bulan ke 5, pendapatan meningkat 5%, selanjutnya pada bulan ke 8 mengalami penurunan keuntungan sebesar 2%, sehingga laba menjadi 3%.
### 2.Kode Program
Berikut ini adalah kode dari program tersebut :

        a = 100000000
        for x in range(1,9):
	        if(x>=1 and x<=2):
		        b=a*0
        		print('laba bulan ke-',x,'sebesar:',b)
	        if(x>=3 and x<=4):
        		c=a*0.1
	        	print('laba bulan ke-',x,'sebesar:',c)
	        if(x>=5 and x<=7):
		        d=a*0.5
	        	print('laba bulan ke-',x,'sebesar:',d)
	        if(x==8):
		        e=a*0.2
		        print('laba bulan ke-',x,'sebesar:',e)
        total = b+b+c+c+d+d+d+e
        print('Total laba adalah:', total)

**Keterangan**  
*a = 100000000** adalah keterangan modal.  
*for x in range(1,9):* adalah list dari laba yang didapat selama 8 bulan.  
*if(x>=1 and x<=2):* adalah perintah untuk menentukan laba bulan ke-1 dan ke-2.  
*if(x>=3 and x<=4):* adalah perintah untuk menentukan laba bulan ke-3 dan ke-4.  
*if(x>=5 and x<=7):* adalah perintah untuk menentukan laba bulan ke-5, ke-6, dan ke-7.  
*if(x==8):* adalah perintah untuk menentukan laba bulan ke-8.  
*total = b+b+c+c+d+d+d+e* adalah perintah untuk menghitung total dari semua laba.  
###  3. Eksekusi Program
![image](https://github.com/refhaldo/labpy03/blob/master/program1.png?raw=true)
# PENUTUP
Sekian penjelasan dari ke-tiga program diatas.  
**TERIMAKASIH**
