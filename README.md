# NAMA : RAPHEL AJIE PRATAMA TANOYO
# NIM : 312210348
# KELAS : TI.22.A3

# PRAKTIKUM 9

Disini saya akan menjelaskan tentang latihan pada hari selasa 13-12-2022

# pertama

<img width="528" alt="N1" src="https://user-images.githubusercontent.com/115516830/208499648-dd201478-1f6a-43d8-91e3-790fe24ce67a.png">


Berikut adalah fungsi yang mengubah mengubah suhu suhu dari derajat Kelvin ke derajat Fahrenheit. Karena nol derajat Kelvin sedingin yang didapat. Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback...AssertionError artinya terjadi error pada pernyataan assert.

# kedua

<img width="536" alt="prak 9 2" src="https://user-images.githubusercontent.com/115516730/208420939-e6524b52-b93c-4ebe-ad80-a2767dae238c.png">

contoh ini membuka file, menulis konten di file, dan keluar tidak ada masalah, Ini menghasilkan hasil berikut

Written content in the file successfully

Dan kenapa hasilnya begitu? karena else akan dijalankan ketika try adalah True

# ketiga

<img width="530" alt="prak 9 3" src="https://user-images.githubusercontent.com/115516730/208421362-7a3c5205-c93b-44ec-9c74-435a642fc912.png">

Mengapa muncul error?

Error: can't find file or read data

r adalah read - Membuka file untuk membaca, error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya fh = open("testfile", "r") tambahkan print(fh.readline()) dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan

# keempat

<img width="537" alt="prak 9 4" src="https://user-images.githubusercontent.com/115516730/208421584-cfc7049c-d719-4517-ba92-e98b93501c09.png">

Menghasilkan output:

Error: can\'t find file or read data

Ini bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan

# kelima

<img width="474" alt="prak 9 5" src="https://user-images.githubusercontent.com/115516730/208421861-00db8fbd-5371-4041-9ba5-1ebc101fb158.png">

ketika dijalankan, maka muncul error. Hapus #!/usr/bin/python dan di except ValueError, Argument: ganti koma dengan as seperti except ValueError as Argument:agar tidak error. Jika dijalankan akan muncul error lagi

The argument does not contain numbers
invalid literal for int() with base 10: 'xyz'

kenapa? karena parameter def temp_convert harus mengandung angka

# keenam

<img width="470" alt="prak 9 6" src="https://user-images.githubusercontent.com/115516730/208422073-506acd12-3d12-4d15-8bd7-f5e30ede3d25.png">

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise "Invalid level!", level ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1
