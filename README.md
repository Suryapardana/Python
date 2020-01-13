# Pengenalan Python
![python-logo](https://user-images.githubusercontent.com/47344288/72213664-3fe11880-3525-11ea-8d36-93bf35c0dfdf.png)

Python adalah bahasa pemrograman interpretatif multiguna. Tidak seperti bahasa lain yang susah untuk dibaca dan dipahami,
python lebih menekankan pada keterbacaan kode agar lebih mudah untuk memahami sintaks. Hal ini membuat Python sangat mudah dipelajari baik untuk pemula maupun untuk yang sudah menguasai bahasa pemrograman lain.

Bahasa ini muncul pertama kali pada tahun 1991, dirancang oleh seorang bernama Guido van
Rossum. Sampai saat ini Python masih dikembangkan oleh Python Software Foundation. Bahasa
Python mendukung hampir semua sistem operasi, bahkan untuk sistem operasi Linux, hampir
semua distronya sudah menyertakan Python di dalamnya.
Dengan kode yang simpel dan mudah diimplementasikan, seorang programmer dapat lebih
mengutamakan pengembangan aplikasi yang dibuat, bukan malah sibuk mencari syntax error.

print("Follow github suryapardana")

Hanya dengan menuliskan kode print seperti yang diatas, anda sudah bisa mencetak apapun yang
anda inginkan di dalam tanda kurung (). Dibagian akhir kode pun, anda tidak harus
mengakhirnya dengan tanda semicolon ;

# Instalasi Python
Sebelum Anda menggunakan Python, Anda harus menginstalnya terlebih dahulu di sistem operasi komputer Anda. Saat ini Python memiliki 2 versi yang berbeda, yaitu Python versi 3.4.3 dan Python versi 2.7.10. Disini kita akan belajar bahasa pemrograman Python menggunakan versi terbaru 3.4.3

Cara menginstal python sangat mudah, ikuti panduan dibawah ini. Dibawah adalah panduan cara instal python di platform Linux, Windows dan Mac OS.

## 1.1 Linux
```
- Buka browser, kunjungi http://www.python.org/downloads/source/
- Download versi terbaru Python berbentuk file zip untuk Unix/Linux
- Ekstrak file zip yang baru saja di download
- Edit file Modules/Setup jika Anda ingin kostumisasi Python
- Jalankan ./configure script
- make
- make install
```
Langkah ini akan menginstal Python di lokasi standar /usr/local/bin dan library di /usr/local/lib/pythonXX dimana XX adalah versi terbaru Python yang anda gunakan.

 ## 1.2 Windows
```
- Buka browser, kunjungi http://www.python.org/downloads/windows/
- ATAU, klik direct link https://www.python.org/ftp/python/3.4.3/python-3.4.3.msi
- Buka (klik 2x) file installer python yang baru saja di download
- Ikuti langkah instalasi sampai selesai
```

##  1.3 Mac OS
```
- Buka browser, kunjungi http://www.python.org/download/mac/
- Download versi terbaru Python untuk Macintosh
- Buka file yang baru saja di download
- Ikuti langkah instalasi sampai selesa
```
# Integrated Daveloper Environment
IDE adalah sebuah software aplikasi yang memberikan Anda fasilitas bermanfaat ketik membuat program. Biasanya sebuah IDE terdiri dari source code editor build automation tool dan debugger.
Untuk menulis sebuah program, bisa menggunakan text editor atau IDE nya. Bagi yang sudah mahir, menulis program dengan text editor bukanlah menjadi masalah. Tetapi untuk pemula, akan lebih mudah menggunakan IDE. IDE untuk Python sangatlah banyak, tersedia bermacam-macam IDE dengan kelebihan dan kekurangan masing-masing.

Beberapa IDE untuk Python yang cukup populer adalah :

- Komodo
- LiClipse
- NetBeans
- PyCharm
- Kdevelop
- PyDev
- Wing IDE
- dan masih banyak lainnya

 (http://wiki.python.org/moin/IntegratedDevelopmentEnvironments).

# Menjalankan Python
Untuk menjalankan Python ada banyak cara yang bisa dilakukan. Anda bisa menggunakan sheel, terminal atau menggunakan IDE (Integrated Development Environment). Di bawah ini adalah langkah-langkah menjalankan Python dengan cara yang paling mudah.

## 2.1 Linux
- Buka terminal (Ctrl + Alt + T)
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

atau 

- Gunakan teks editor, misalnya gedit.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

 ## 2.2 Windows

- Buka Python sheel, Anda bisa mencarinya di tombol Start.
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit()

## 2.3 Macintosh

- Buka terminal.
- Ketik python maka Anda akan masuk ke sheel Python. 
- Tuliskan script Python Anda, contoh: print("Selamat datang di Python"). jika sudah tekan tombol Enter, dan script Python akan dijalankan/eksekusi.
- Untuk keluar dari sheel Python ketik exit() atau 
- Gunakan teks editor.
- Buat file baru, dan ketikan script python Anda, contoh: print("Selamat datang di Python").
- Save As dengan ekstensi .py (contoh: cetak.py).
- Jalankan file dengan menggunakan Terminal.
- Buka terminal (Ctrl + Alt + T).
- Masuk ke direktori dimana file Python Anda disimpan (contoh: cd /Users/admin/Desktop/).
- Jalankan script Python dengan menggunakan python diikuti dengan nama file (contoh: python cetak.py).
- Script Python Anda akan dieksekusi/dijalankan.

# Syntax Dasar Python
Dibawah ini adalah contoh fungsi Python yang digunakan untuk mencetak. Di Python untuk mencetak cukup gunakan fungsi print(), dimana sesuatu yang akan dicetak harus diletakkan diantara kurung buka dan kurung tutup, bahkan di Python versi 2.x Anda tidak harus menggunakan tanda kurung kurawal, cukup pisahkan dengan spasi.
Jika ingin mencetak tipe data String langsung, Anda harus memasukanya ke dalam tanda kutip terlebih dahulu.

print("Hello World")

Saat anda menjalankan script diatas, Anda akan melihat output berupa text Hello World

# Komentar Python

Komentar (comment) adalah kode di dalam script Python yang tidak dieksekusi atau tidak dijalankan mesin. Komentar hanya digunakan untuk menandai atau memberikan keterangan tertulis pada script.
Komentar biasa digunakan untuk membiarkan orang lain memahami apa yang dilakukan script. atau untuk mengingatkan kepada programmer sendiri jika suatu saat kembali mengedit script tersebut.
Untuk menggunakan komentar anda cukup menulis tanda pagar #, diikuti dengan komentar Anda.
Dibawah ini adalah contoh penggunaan komentar pada Python.
```
#Ini adalah komentar

#Tulisan ini tidak akan dieksekusi

#komentar dengan tanda pagar hanya bisa digunakan

#untuk

#satu

#baris

print("Hello World") #ini juga komentar

#print("Welcome")

#komentar bisa berisi spesial karakter !@#$%^&*(

#mencetak nama

print("Budi")

#mencetak angka/integer

print(123)
```

Saat anda menjalankan script diatas, Anda akan melihat output berupa Hello World, Budi dan 123, karena tulisan/komentar yang ditulis tidak dieksekusi.

# Python Case Sensitive
Python bersifat case sensitif, ini artinya huruf besar dan huruf kecil memiliki perbedaan.
Sebagai contoh jika Anda menggunakan fungsi print dengan huruf kecil print() akan
berhasil. Lain hal jika anda menggunakan huruf kapital Print() atau PRINT(), akan
muncul pesan error.
Aturan ini berlaku untuk nama variabel ataupun fungsi-fungsi lainya

# Tipe Data

Tipe data adalah suatu media atau memori pada komputer yang digunakan untuk menampung informasi.

Python sendiri mempunyai tipe data yang cukup unik bila kita bandingkan dengan bahasa pemrograman yang lain.

Berikut adalah tipe data dari bahasa pemrograman Python :

| Tipe Data     | Contoh                    | Penjelasan                                                                        |
| ------------- |-------------------------- | --------------------------------------------------------------------------------- |
| Boolean       |	`True` atau `False`	    | Menyatakan benar `True` yang bernilai `1`, atau salah `False` yang bernilai `0`   |
| String        |	`"Ayo belajar Python"`  | Menyatakan karakter/kalimat bisa berupa huruf angka, dll (diapit tanda `"` atau `'`)|
| Integer       |	`25` atau `1209`        | Menyatakan bilangan bulat                                                         |
| Float         |	`3.14` atau `0.99`      | Menyatakan bilangan yang mempunyai koma                                           |
| Hexadecimal   |	`9a` atau `1d3`	        | Menyatakan bilangan dalam format heksa (bilangan berbasis 16)                     |
| Complex       |	`1 + 5j  `              | Menyatakan pasangan angka real dan imajiner                                       |
| List          |	`['xyz', 786, 2.23]`    | Data untaian yang menyimpan berbagai tipe data dan isinya bisa diubah-ubah        |
| Tuple         |	`('xyz', 768, 2.23)`    | Data untaian yang menyimpan berbagai tipe data tapi isinya tidak bisa diubah      |
| Dictionary    |	`{'nama': 'adi','id':2}`| Data untaian yang menyimpan berbagai tipe data berupa pasangan penunjuk dan nilai |

Untuk mencoba berbagai macam tipe data, silahkan coba script Python dibawah ini.
```
{% highlight python %}
#tipe data Boolean
print(True)

#tipe data String
print("Ayo belajar Python")
print('Belajar Python Sangat Mudah')

#tipe data Integer
print(20)

#tipe data Float
print(3.14)

#tipe data Hexadecimal
print(9a)

#tipe data Complex
print(5j)

#tipe data List
print([1,2,3,4,5])
print(["satu", "dua", "tiga"])

#tipe data Tuple
print((1,2,3,4,5))
print(("satu", "dua", "tiga"))

#tipe data Dictionary
print({"nama":"Budi", 'umur':20})
#tipe data Dictionary dimasukan ke dalam variabel biodata
biodata = {"nama":"Andi", 'umur':21} #proses inisialisasi variabel biodata
print(biodata) #proses pencetakan variabel biodata yang berisi tipe data Dictionary
type(biodata) #fungsi untuk mengecek jenis tipe data. akan tampil <class 'dict'> yang berarti dict adalah tipe data dictionary
{% endhighlight %}
```
# Variabel Python

Variabel adalah lokasi memori yang dicadangkan untuk menyimpan nilai-nilai. Ini berarti bahwa ketika Anda membuat sebuah variabel Anda memesan beberapa ruang di memori. Variabel menyimpan data yang dilakukan selama program dieksekusi, yang nantinya isi dari variabel tersebut dapat diubah oleh operasi - operasi tertentu pada program yang menggunakan variabel.

Variabel dapat menyimpan berbagai macam tipe data. Di dalam pemrograman Python, variabel mempunyai sifat yang dinamis, artinya variabel Python tidak perlu didekralasikan tipe data tertentu dan variabel Python dapat diubah saat program dijalankan.


Penulisan variabel Python sendiri juga memiliki aturan tertentu, yaitu :
1. Karakter pertama harus berupa huruf atau garis bawah/underscore `_`
2. Karakter selanjutnya dapat berupa huruf, garis bawah/underscore `_` atau angka
3. Karakter pada nama variabel bersifat sensitif (case-sensitif). Artinya huruf kecil dan huruf besar dibedakan. Sebagai contoh, variabel `namaDepan` dan `namadepan` adalah variabel yang berbeda.

Untuk mulai membuat variabel di Python caranya sangat mudah, Anda cukup menuliskan variabel lalu mengisinya dengan suatu nilai dengan cara menambahkan tanda sama dengan `=` diikuti dengan nilai yang ingin dimasukan.

Dibawah ini adalah contoh penggunaan variabel dalam bahasa pemrograman Python


```
{% highlight python %}
#proses memasukan data ke dalam variabel
nama = "John Doe"
#proses mencetak variabel
print(nama)

#nilai dan tipe data dalam variabel  dapat diubah
umur = 20               #nilai awal
print(umur)             #mencetak nilai umur
type(umur)              #mengecek tipe data umur
umur = "dua puluh satu" #nilai setelah diubah
print(umur)             #mencetak nilai umur
type(umur)              #mengecek tipe data umur

namaDepan = "Budi"
namaBelakang = "Susanto"
nama = namaDepan + " " + namaBelakang
umur = 22
hobi = "Berenang"
print("Biodata\n", nama, "\n", umur, "\n", hobi)

#contoh variabel lainya
inivariabel = "Halo"
ini_juga_variabel = "Hai"
_inivariabeljuga = "Hi"
inivariabel222 = "Bye" 

panjang = 10
lebar = 5
luas = panjang * lebar
print(luas)
{% endhighlight %}
```

# Operator Python
Operator adalah konstruksi yang dapat memanipulasi nilai dari operan. 

Sebagai contoh operasi 3 + 2 = 5. Disini `3` dan `2` adalah operan dan `+` adalah operator.

Bahasa pemrograman Python mendukung berbagai macam operator, diantaranya :
- [Operator Aritmatika (Arithmetic Operators)](#operator-aritmatika)
- [Operator Perbandingan (Comparison (Relational) Operators)](#operator-perbandingan)
- [Operator Penugasan (Assignment Operators)](#operator-penugasan)
- [Operator Logika (Logical Operators)](#operator-logika)
- [Operator Bitwise (Bitwise Operators)](#operator-bitwise)
- [Operator Keanggotaan (Membership Operators)](#operator-keanggotaan)
- [Operator Identitas (Identity Operators)](#operator-identitas)
 
### Operator Aritmatika <a name="operator-aritmatika"></a>

| Operator| 	Contoh	 | Penjelasan |
| --- | --- | --- |
| Penjumlahan `+`| 	`1 + 3 = 4` | 	Menjumlahkan nilai dari masing-masing operan atau bilangan |
| Pengurangan `-`| 	`4 - 1 = 3`	 | Mengurangi nilai operan di sebelah kiri menggunakan operan di sebelah kanan |
| Perkalian `*`| 	`2 * 4 = 8`	 | Mengalikan operan/bilangan |
| Pembagian `/`| 	`10 / 5 = 2`	 | Untuk membagi operan di sebelah kiri menggunakan operan di sebelah kanan |
| Sisa Bagi `%`| 	`11 % 2 = 1`	 | Mendapatkan sisa pembagian dari operan di sebelah kiri operator ketika dibagi oleh operan di sebelah kanan |
| Pangkat `**`| 	`8 ** 2 = 64`	 | Memangkatkan operan disebelah kiri operator dengan operan di sebelah kanan operator |
| Pembagian Bulat `//`| 	`10 // 3 = 3` |	Sama seperti pembagian. Hanya saja angka dibelakang koma dihilangkan |

Dibawah ini adalah contoh penggunaan Operator Aritmatika dalam bahasa pemrograman Python
```
{% highlight python %}
#OPERATOR ARITMATIKA

#Penjumlahan
print(13 + 2)
apel = 7
jeruk = 9
buah = apel + jeruk #
print(buah)

#Pengurangan
hutang = 10000
bayar = 5000
sisaHutang = hutang - bayar
print("Sisa hutang Anda adalah ", sisaHutang)

#Perkalian
panjang = 15
lebar = 8
luas = panjang * lebar
print(luas)

#Pembagian
kue = 16
anak = 4
kuePerAnak = kue / anak
print("Setiap anak akan mendapatkan bagian kue sebanyak ", kuePerAnak)

#Sisa Bagi / Modulus
bilangan1 = 14
bilangan2 = 5
hasil = bilangan1 % bilangan2
print("Sisa bagi dari bilangan ", bilangan1, " dan ", bilangan2, " adalah ", hasil)

#Pangkat
bilangan3 = 8
bilangan4 = 2
hasilPangkat = bilangan3 ** bilangan4
print(hasilPangkat)

#Pembagian Bulat
print(10//3) 
#10 dibagi 3 adalah 3.3333. Karena dibulatkan maka akan menghasilkan nilai 3
{% endhighlight %}
```
### Operator Perbandingan <a name="operator-perbandingan"></a>

Operator perbandingan (comparison operators) digunakan untuk membandingkan suatu nilai dari masing-masing operan.

| Operator	| Contoh	| Penjelasan| 
| --- | --- | --- |
| Sama dengan `==` | 	`1 == 1`  | bernilai True	Jika masing-masing operan memiliki nilai yang sama, maka kondisi bernilai benar atau True. | 
| Tidak sama dengan `!=` |	`2 != 2`  | bernilai False	Akan menghasilkan nilai kebalikan dari kondisi sebenarnya. | 
| Tidak sama dengan `<>` |	`2 <> 2`  | bernilai False	Akan menghasilkan nilai kebalikan dari kondisi sebenarnya. | 
| Lebih besar dari `>` |	`5 > 3`  | bernilai True	Jika nilai operan kiri lebih besar dari nilai operan kanan, maka kondisi menjadi benar. | 
| Lebih kecil dari `<` |	`5 < 3`  | bernilai True	Jika nilai operan kiri lebih kecil dari nilai operan kanan, maka kondisi menjadi benar. | 
| Lebih besar atau sama dengan `>=` |	`5 >= 3`  | bernilai True	Jika nilai operan kiri lebih besar dari nilai operan kanan, atau sama, maka kondisi menjadi benar. | 
| Lebih kecil atau sama dengan `<=` |	`5 <= 3`  | bernilai True	Jika nilai operan kiri lebih kecil dari nilai operan kanan, atau sama, maka kondisi menjadi benar. | 


### Operator Penugasan <a name="operator-penugasan"></a>

Operator penugasan digunakan untuk memberikan atau memodifikasi nilai ke dalam sebuah variabel.

| Operator	| Contoh	| Penjelasan | 
| --- | --- | --- |
| Sama dengan `=`	 | `a = 1` | 	Memberikan nilai di kanan ke dalam variabel yang berada di sebelah kiri. | 
| Tambah sama dengan `+=` | 	`a += 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri ditambah dengan nilai di sebelah kanan. | 
| Kurang sama dengan `-=`	 | `a -= 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dikurangi dengan nilai di sebelah kanan. | 
| Kali sama dengan `*=` | 	`a *= 2` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dikali dengan nilai di sebelah kanan. | 
| Bagi sama dengan `/=` | 	`a /= 4` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan. | 
| Sisa bagi sama dengan `%=`	 | `a %= 3` | 	Memberikan nilai variabel dengan nilai variabel itu sendiri dibagi dengan nilai di sebelah kanan. Yang diambil nantinya adalah sisa baginya. | 
| Pangkat sama dengan `**=` | 	`a **= 3`	 | Memberikan nilai variabel dengan nilai variabel itu sendiri dipangkatkan dengan nilai di sebelah kanan. | 
| Pembagian bulat sama dengan `//=` | 	`a //= 3`	 | Membagi bulat operan sebelah kiri operator dengan operan sebelah kanan operator kemudian hasilnya diisikan ke operan sebelah kiri. | 


### Prioritas Eksekusi Operator di Python
Dari semua operator diatas, masing-masing mempunyai urutan prioritas yang nantinya prioritas pertama akan dilakukan paling pertama, begitu seterusnya sampai dengan prioritas terakhir. 
```
| Operator |	Keterangan | 
| --- | --- | --- |
| `**` |	Aritmatika | 
| `~, +, -` |	Bitwise | 
| `*, /, %, //` |	Aritmatika |
| `+, -`	 |Aritmatika |
| `>>, <<` |	Bitwise |
| `&`	 |Bitwise |
| `^, |`  |	Bitwise |
| `<=, <, >, >=` |	Perbandingan |
| `<> , ==, !=` |	Perbandingan |
| `=, %=, /=, //=, -=, +=, *=, **=` |	Penugasan |
| `is, is not` |	Identitas |
| `in, not in` |	Membership (Keanggotaan) |
| `not, or, and` |	Logika |
```

# Kondisi
### Kondisi If

Pengambilan keputusan (kondisi if) digunakan untuk mengantisipasi kondisi yang terjadi saat jalanya program dan menentukan tindakan apa yang akan diambil sesuai dengan kondisi.

Pada python ada beberapa statement/kondisi diantaranya adalah `if`, `else` dan `elif` Kondisi `if` digunakan untuk mengeksekusi kode jika kondisi bernilai benar `True`.

Jika kondisi bernilai salah `False` maka statement/kondisi `if` tidak akan di-eksekusi.

Dibawah ini adalah contoh penggunaan kondisi if pada Python
```
{% highlight python %}
#Kondisi if adalah kondisi yang akan dieksekusi oleh program jika bernilai benar atau TRUE

nilai = 9

#jika kondisi benar/TRUE maka program akan mengeksekusi perintah dibawahnya
if(nilai > 7):
    print("Selamat Anda Lulus")

#jika kondisi salah/FALSE maka program tidak akan mengeksekusi perintah dibawahnya
if(nilai > 10):
    print("Selamat Anda Lulus")
{% endhighlight %}
```
Dari contoh diatas, jika program dijalankan maka akan mencetak string `"Selamat Anda Lulus Ujian"` sebanyak 1 kali yaitu pada if pertama. Di if kedua statement bernilai salah, jadi perintah `print("Selamat Anda Lulus")` tidak akan dieksekusi.


### Kondisi If Else
Pengambilan keputusan (kondisi if else) tidak hanya digunakan untuk menentukan tindakan apa yang akan diambil sesuai dengan kondisi, tetapi juga digunakan untuk menentukan tindakan apa yang akan diambil/dijalankan jika kondisi tidak sesuai.

Pada python ada beberapa statement/kondisi diantaranya adalah if, else dan elif Kondisi if digunakan untuk mengeksekusi kode jika kondisi bernilai benar.

Kondisi if else adalah kondisi dimana jika pernyataan benar `True` maka kode dalam if akan dieksekusi, tetapi jika bernilai salah `False` maka akan mengeksekusi kode di dalam else.

Dibawah ini adalah contoh penggunaan kondisi if else pada Python
```
{% highlight python %}
#Kondisi if else adalah jika kondisi bernilai TRUE maka akan dieksekusi pada if, tetapi jika bernilai FALSE maka akan dieksekusi kode pada else

nilai = 3
#Jika pernyataan pada if bernilai TRUE maka if akan dieksekusi, tetapi jika FALSE kode pada else yang akan dieksekusi.
if(nilai > 7):
    print("Selamat Anda Lulus")
else:
    print("Maaf Anda Tidak Lulus")
{% endhighlight %}
```
Pada contoh diatas, jika program dijalankan maka akan mencetak string `"Maaf Anda Tidak Lulus"` karena pernyataan pada if bernilai `False`

### Kondisi Elif

Pengambilan keputusan (kondisi if elif) merupakan lanjutan/percabangan logika dari "kondisi if". Dengan elif kita bisa membuat kode program yang akan menyeleksi beberapa kemungkinan yang bisa terjadi. Hampir sama dengan kondisi "else", bedanya kondisi "elif" bisa banyak dan tidak hanya satu. 

Dibawah ini adalah contoh penggunaan kondisi elif pada Python
```
{% highlight python %}
#Contoh penggunaan kondisi elif

hari_ini = "Minggu"

if(hari_ini == "Senin"):
    print("Saya akan kuliah")
elif(hari_ini == "Selasa"):
    print("Saya akan kuliah")
elif(hari_ini == "Rabu"):
    print("Saya akan kuliah")
elif(hari_ini == "Kamis"):
    print("Saya akan kuliah")
elif(hari_ini == "Jumat"):
    print("Saya akan kuliah")
elif(hari_ini == "Sabtu"):
    print("Saya akan kuliah")
elif(hari_ini == "Minggu"):
    print("Saya akan libur")
{% endhighlight %}
```
Pada contoh diatas, jika program dijalankan maka akan mencetak string `"Saya akan libur"`.

# Loop python


Secara umum, pernyataan pada bahasa pemrograman akan dieksekusi secara berurutan. Pernyataan pertama dalam sebuah fungsi dijalankan pertama, diikuti oleh yang kedua, dan seterusnya. Tetapi akan ada situasi dimana Anda harus menulis banyak kode, dimana kode tersebut sangat banyak. Jika dilakukan secara manual maka Anda hanya akan membuang-buang tenaga dengan menulis beratus-ratus bahkan beribu-ribu kode. Untuk itu Anda perlu menggunakan pengulangan di dalam bahasa pemrograman Python.

Di dalam bahasa pemrograman Python pengulangan dibagi menjadi 3 bagian, yaitu :
- While Loop
- For Loop
- Nested Loop

### While Loop
Pengulangan While Loop di dalam bahasa pemrograman Python dieksesusi statement berkali-kali selama kondisi bernilai benar atau `True`.

Dibawah ini adalah contoh penggunaan pengulangan While Loop.

```
{% highlight python %}
#Contoh penggunaan While Loop

count = 0
while (count < 9):
    print ('The count is:', count)
    count = count + 1

print ("Good bye!")
{% endhighlight %}
```
### For Loop
Pengulangan `for` pada Python memiliki kemampuan untuk mengulangi item dari urutan apapun, seperti `list` atau `string`.

Dibawah ini adalah contoh penggunaan pengulangan While Loop.
```
{% highlight python %}
#Contoh pengulangan for sederhana
angka = [1,2,3,4,5]
for x in angka:
    print(x)

#Contoh pengulangan for
buah = ["nanas", "apel", "jeruk"]
for makanan in buah:
    print("Saya suka makan", makanan)
{% endhighlight %}
```
### Nested Loop
Bahasa pemrograman Python memungkinkan penggunaan satu lingkaran di dalam loop lain. Bagian berikut menunjukkan beberapa contoh untuk menggambarkan konsep tersebut. 

Dibawah ini adalah contoh penggunaan Nested Loop.
```
{% highlight python %}
#Contoh penggunaan Nested Loop

i = 2
while(i < 100):
    j = 2
    while(j <= (i/j)):
        if not(i%j): break
        j = j + 1
    if (j > i/j) : print(i, " is prime")
    i = i + 1

print "Good bye!"
{% endhighlight %}
```

# Number

Number adalah tipe data Python yang menyimpan nilai numerik. Number adalah tipe data yang tidak berubah. Ini berarti, mengubah nilai dari sejumlah tipe data akan menghasilkan objek yang baru dialokasikan.

Objek Number dibuat saat Anda memberikan nilai pada-nya. Sebagai contoh : `angkaPertama = 1`
`angkaKedua = 33 `

Python mendukung beberapa tipe data Number diantaranya :
- Int
- Float
- Complex

Berikut ini adalah beberapa contoh dari Tipe data Number pada Python :

| Int |	Float |	Complex |
| --- | --- | --- |
| 20 |	0.1 |	3.14j |
| 300 |	1.20 |	35.j |
| -13 |	-41.2 |	3.12e-12j |
| 020 |	32.23+e123 |	.873j |
| -0103 |	-92. |	-.123+0J |
| -0x212 |	-32.52e10 |	3e+123J |
| 0x56 |	60.2-E13 |	4.31e-4j |


### Konversi Tipe Data Number Python
Pada Python Anda bisa mengkonversi tipe data dengan menggunakan fungsi. Dibawah ini adalah beberapa fungsi untuk mengkonversi tipe data number Python. 
- `int(x)`
untuk meng-konversi x menjadi plain integer.
- `long(x)`
untuk meng-konversi x menjadi long integer.
- `float(x)`
untuk meng-konversi x menjadi floating point number.
- `complex(x)`
untuk meng-konversi x menjadi complex number dengna real part x dan imaginary part zero.
- `complex(x, y)`
untuk meng-konversi x dan y menjadi complex number dengan real part x dan imaginary part y. x dan numeric expressions y. 


### Fungsi Matematika Python
Pada bahasa pemrograman Python terdapat fungsi untuk melakukan perhitungan matematis, berikut adalah daftarnya :

| Nama |	Penggunaan |	Penjelasan |
| --- | --- | --- |
| Absolute |	`abs(x)` |	Nilai absolut dari x:(positive) jarak antara x and 0. |
| Ceiling |	`ceil(x)` |	Ceiling dari x: integer terkecil yang kurang dari x. |
| Cmp |	`cmp(x, y)` |	-1 if x < y, 0 if x == y, or 1 if x > y. Tidak berlaku lagi dengan Python 3. Sebaliknya gunakan return (x>y)-(x |
| Eksponen |	`exp(x)` |	Nilai eksponen dari x: ex |
| Fabs |	`fabs(x)` |	Nilai absolut dari x. |
| Floor |	`floor(x)` |	The floor of x: the largest integer not greater than x. |
| Floor |	`floor(x)` |	Nilai dasar dari x: internet terbesar tidak lebih besar dari x. |
| Log |	`log(x)` |	Logaritma dari x, untuk x > 0. |
| Log 10 |	`log10(x)` |	Basis 10 logaritma dari x, untuk x > 0. |
| Max |	`max(x1, x2,...)`	 | Argumen terbesar: Nilai terdekat dengan tak terhingga positif |
| Min |	`min(x1, x2,...)` |	Argumen terkecil: nilai yang paling mendekati tak berhingga negatif. |
| Modf |	`modf(x)` |	Bagian pecahan dan bilangan bulat dari x dalam tupel dua item. Kedua bagian memiliki tanda yang sama dengan x. Bagian integer dikembalikan sebagai float. |
| Pow |	`pow(x, y)` |	Nilai x ** y. |
| Round |	`round(x [,n])` |	X dibulatkan menjadi n digit dari titik desimal. Putaran Python jauh dari nol sebagai tie-breaker: round (0.5) adalah 1.0 dan round (-0.5) adalah -1.0. |
| Akar Kuadrat |	`sqrt(x)` |	Akar kuadrat x untuk x> 0. |


### Fungsi Nomor Acak Python
Nomor acak digunakan untuk aplikasi permainan, simulasi, pengujian, keamanan, dan privasi. Python mencakup fungsi berikut yang umum digunakan. Berikut adalah daftarnya :

| Nama | 	Penggunaan | 	Penjelasan | 
| --- | --- | --- |
| Choice | 	`choice(seq)` | 	Item acak dari list, tuple, atau string. | 
| RandRange | 	`randrange ([start,] stop [,step])` | 	Elemen yang dipilih secara acak dari jangkauan (start, stop, step). | 
| Random | 	`random()` | 	A random float r, sehingga 0 kurang dari atau sama dengan r dan r kurang dari 1 | 
| Seed | 	`seed([x])` | 	Menetapkan nilai awal integer yang digunakan dalam menghasilkan bilangan acak. Panggil fungsi ini sebelum memanggil fungsi modul acak lainnya. Tidak ada pengembalian | 
| Shuffle | 	`shuffle(lst)` | 	Mengacak daftar dari daftar di tempat. Tidak ada pengembalian | 
| Floor	| `floor(x)`	 | The floor of x: the largest integer not greater than x. | 
| Uniform| 	`uniform(x, y)` | 	Sebuah float acak r, sedemikian rupa sehingga x kurang dari atau sama dengan r dan r kurang dari y. | 


### Fungsi Trigonometri Python
Python mencakup fungsi berikut yang melakukan perhitungan trigonometri. Berikut adalah daftarnya :
```
| Nama |	Penggunaan	Penjelasan |
| --- | --- | --- |
| Acos |	`acos(x)` |	Kembalikan kosinus x, di radian. |
| Asin |	`asin(x)` |	Kembalikan busur sinus x, dalam radian. |
| Atan |	`atan(x)` |	Kembalikan busur singgung x, di radian. |
| Atan 2 |	`atan2(y, x)`	 | Kembali atan (y / x), di radian. |
| Kosinus |	`cos(x)` |	Kembalikan kosinus x radian. |
| Hypot	 | `hypot(x, y)` |	Kembalikan norma Euclidean, sqrt (x * x + y * y). |
| Sin |	`sin(x)` |	Kembalikan sinus dari x radian. |
| Tan |	`tan(x)` |	Kembalikan tangen x radian. |
| Derajat |	`degrees(x)` |	Mengonversi sudut x dari radian ke derajat. |
| Radian |	`radians(x)` |	Mengonversi sudut x dari derajat ke radian. |
```
### Konstanta Matematika Python
Modul ini juga mendefinisikan dua konstanta matematika. Berikut adalah daftarnya :

| Nama |	Penggunaan	| Penjelasan| 
| --- | --- | --- |
| Pi	| `pi`	| Konstanta Pi matematika| 
| e	| `e`	| Konstanta e matematika| 
