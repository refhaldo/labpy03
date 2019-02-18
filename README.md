# Tugas Praktikum 3
# Latihan 1: latihan1.py
**1. Penjelasan**

Program ini digunakan untuk menampilkan bilanga acak yang kurang dari o.5
**2. Kode Program**

        print ('Masukan nilai N: 5')
        import random
        jumlah = 5
        a = 0
        for i in range(jumlah):
          x = random.uniform(.0,.5)
          a += 1
        print ('data ke:',a,'=>',x)
        print('Selesai')
