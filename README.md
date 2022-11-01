NAMA   : SALMAN AL HARITS

NIM    : 312210152

KELAS  : TI.22.A.1

MATKUL : BAHASA PEMROGRAMAN

Hallo,kali ini kita akan menggunakan aplikasi yang bernama pycharm
seperti biasa ini adalah tutorial cara penginstalan dan cara pemakaian pycharm

# Penginstalan
1. Anda bisa menginstal pycharm  di https://www.jetbrains.com/pycharm/download/#section=windows ,lalu pilih yang comunity
  ![donwload pycharm](https://user-images.githubusercontent.com/115677440/199348035-9a98cc4a-51e5-412f-9062-dde6764e2ab2.png)
  
2.Setelah itu anda bisa buka folder pycharm di file explorer masing-masing

3.Lalu klik dan run as administrator

4.Klik next saja hingga penginstalan selesai

# Cara menjalankan Pycharm
Sebelumnya kita membuat file dengan cara
1.Pertama kita akan membuat project dengan nama,Di sini saya namakan Praktikum3

2.Setelah itu anda pilih Previously Configurred interperter lalu klik yang add interperter
  dan pilih yang System interperter dan anda klik yang versi Python anda
  ![project 1](https://user-images.githubusercontent.com/115677440/199350622-56869658-7578-44a5-9221-f59354484d0b.png)

  ![create](https://user-images.githubusercontent.com/115677440/199350444-78c6a4e8-ed9b-4a59-845b-758803f49413.png)

3.Selanjutnya membuat file Python baru di dalam project yang sudah kita buat seperti berikut
![file](https://user-images.githubusercontent.com/115677440/199350724-d844ea9c-dbbb-46e6-b68e-06cf3bdf536b.png)
![Screenshot (101)](https://user-images.githubusercontent.com/115677440/199350842-2b050414-db33-4142-87c7-b8c1ce2c4df8.png)

4.Setelah itu kita akan membuat 3 file latihan untuk dijalankan di pycharm

# Latihan 1
1. Kita akan memasukan perintah sebagai berikut

2.
#Penggunaan AND

print ('A', end='')

print ('B', end='')

print ('C', end='')

print ()

print ('X')

print ('Y')

print ('Z')

#Penggunaan separator
w, x, y, z = 10, 15, 20, 25

print(w, x, y, z, sep = ',')

print(w, x, y, z, sep = '')

print(w, x, y, z, sep = ':')

print(w, x, y, z, sep = '-----')

#String format
print (0,10**0)

print (1,10**1)

print (2,10**2)

print (3,10**3)

print (4,10**4)

print (5,10**5)

print (6,10**6)

print (7,10**7)

print (8,10**8)

print (9,10**9)

print (10,10**10)

#String format
print ('{0:>3} {1:>16}'.format(0, 10**0))

print ('{0:>3} {1:>16}'.format(1, 10**1))

print ('{0:>3} {1:>16}'.format(2, 10**2))

print ('{0:>3} {1:>16}'.format(3, 10**3))

print ('{0:>3} {1:>16}'.format(4, 10**4))

print ('{0:>3} {1:>16}'.format(5, 10**5))

print ('{0:>3} {1:>16}'.format(6, 10**6))

print ('{0:>3} {1:>16}'.format(7, 10**7))

print ('{0:>3} {1:>16}'.format(8, 10**8))

print ('{0:>3} {1:>16}'.format(9, 10**9))

print ('{0:>3} {1:>16}'.format(10, 10**10))

![latihan 1](https://user-images.githubusercontent.com/115677440/199351020-19c51231-e514-4700-a095-53a099b3cd0f.png)
![latihan (2)](https://user-images.githubusercontent.com/115677440/199351006-de52ab9b-f5d6-4a3e-82c7-0944158402dd.png)

3.Setelah itu ini adalah hasil setelah di run
![run 1](https://user-images.githubusercontent.com/115677440/199351376-f60b57f2-547f-479b-86ec-e6ef7897efc1.png)
![run 1 (2)](https://user-images.githubusercontent.com/115677440/199351366-fc4de54d-fade-4fba-a1a2-70f4f64d169d.png)

# Latihan 2
1.Kita akan memasukan perintah sebagai berikut
2.
a = input ("masukan nilai a:")
b = input ("masukan nilai b:")
print ("variable a=",a)
print ("variable b=",b)
print ("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

#konversi nilai variable
a = int(a)
b = int (b)
print ("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print ("hasil pembagian {1}/{0}=%s".format(a,b) %(a/b))
