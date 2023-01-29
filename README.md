# Praktikum3

Tugas pertemuan ke 6 Bahasa Pemrograman

Nama : Ramadhan Ardi Iman Prakoso

NIM : 312210722

Kelas : TI.22.C.9

Prodi : Teknik Informatika

Anda harus install Pycharm di https://www.jetbrains.com/pycharm/download/#section=windows , Dan anda pilih yang Community

![Gambar 1](img/1.png)

next saja semua perintahnya

![Gambar 2](img/2.png)

tunggu hingga selesai

![Gambar 3](img/3.png)

Jika sudah selesai maka program siap di gunakan

# Cara Menjalankan Pycharm

## Latihan 1

Pertama-tama anda harus Klik New project lalu kasih nama project anda(sesuai yang anda mau), Dan anda harus pilih yang Previously Configurred interperter lalu klik yang add interperter dan pilih yang System interperter dan anda klik yang versi Python anda seperti gambar di bawah ini

![Gambar 4](img/4.png)

![Gambar 5](img/5.png)

Selanjutnya anda membuat file Python baru di project anda tadi dan anda kasih nama file sesuai yang anda inginkan

![Gambar 6](img/6.png)

masukan code dari latihan1 anda lalu Run

# penggunaan end

print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('Z')

# penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='-----')

# string format
print(0, 10 ** 0)
print(1, 10 ** 1)
print(2, 10 ** 2)
print(3, 10 ** 3)
print(4, 10 ** 4)
print(5, 10 ** 5)
print(6, 10 ** 6)
print(7, 10 ** 7)
print(8, 10 ** 8)
print(9, 10 ** 9)
print(10, 10 ** 10)

# string format
print('{0:>3} {1:>16}'.format(0, 10 ** 0))
print('{0:>3} {1:>16}'.format(1, 10 ** 1))
print('{0:>3} {1:>16}'.format(2, 10 ** 2))
print('{0:>3} {1:>16}'.format(3, 10 ** 3))
print('{0:>3} {1:>16}'.format(4, 10 ** 4))
print('{0:>3} {1:>16}'.format(5, 10 ** 5))
print('{0:>3} {1:>16}'.format(6, 10 ** 6))
print('{0:>3} {1:>16}'.format(7, 10 ** 7))
print('{0:>3} {1:>16}'.format(8, 10 ** 8))
print('{0:>3} {1:>16}'.format(9, 10 ** 9))
print('{0:>3} {1:>16}'.format(10, 10 ** 10))

![Gambar 7](img/7.png)

![Gambar 8](img/8.png)

lalu hasil run nya

![Gambar 9](img/9.png)

# Latihan 2

buat latihan baru "latihan2"

lalu masukkan code program

a=input("masukkan nilai a:")
b=input("masukkan nilai b:")
print("variabel a=",a)
print("variabel b=",b)
print("hasil penggabungan {1}&{0}=%s".format(a,b) %(a+b))

#konversi nilai variabel
a=int(a)
b=int(b)
print("hasil penjumlahan {1}+{0}=%s".format(a,b) %(a+b))
print("hasil penjumlahan {1}/{0}=%s".format(a,b) %(a/b))

![Gambar 10](img/10.png)

lalu hasil run nya menjadi

![Gambar 11](img/11.png)

# Latihan 3

buat file baru "latihan3"

![Gambar 12](img/12.png)

masukkan code programnya

string = ""

x = int(input("Masukkan angka :"))
bar = x
# Looping Baris
while bar >= 0:
# Looping Kolom Spasi Kosong
kol = bar
while kol > 0:
	string = string + "   "
	kol = kol - 1
# Looping Kolom Bintang Sisi Kiri
kiri = 1
while kiri < (x - (bar-1)):
	string = string + " * "
	kiri = kiri + 1
# Looping Kolom Bintang Sisi Kanan
kanan = 1
while kanan < kiri -1:
	string = string + " * "
	kanan = kanan + 1

string = string + "\n\n"
bar = bar - 1

bar = 1
# Looping Baris
while bar <= x:
kol = bar+1
# Looping Kolom Spasi Kosong
while kol > 1:
	string = string + "   "
	kol = kol - 1
# Looping Kolom Bintang Sisi Kiri
kiri = 0
while kiri < (x - bar):
	string = string + " * "
	kiri = kiri + 1
# Looping Kolom Bintang Sisi Kanan
kanan = kiri
while kanan > 1:
	string = string + " * "
	kanan = kanan - 1

string = string + "\n\n"
bar = bar + 1
print (string)

![Gambar 13](img/13.png)

![Gambar 14](img/14.png)

Hasil Run

![Gambar 15](img/15.png)

# Menghitung Luas Dan Keliling Lingkaran

buat file baru "praktikum3"

print('menghitung luas dan keliling lingkarang')
print('________________________________________')

r=float(input('masukkan nilai jari - jari :'))

phi=3.14
diameter=2*r

print('\nluasnya =', str("%.2f" % luas))
print('kelilingnya =', str("%.2f" % keliling))

![Gambar 16](img/16.png)

Hasil Run

![Gambar 17](img/17.png)

# Flowchart Menghitung luas dan keliling lingkaran

![Gambar 18](img/18.png)

# SELESAI