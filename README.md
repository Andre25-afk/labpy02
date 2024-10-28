# LAPORAN PRAKTIKUM 2

## CODE PROGRAM PEMESANAN TIKET BIOSKOP

### Step 1 : Input Harga Tiket
Masukan/input Harga Reguler dan Harga VIP, Reguler = Rp50.000 dan VIP = Rp100.000 :
![gambar1](ss/1.png)

### Step 2 : Perintah Input untuk Tipe Tiket
Selanjutnya, beri perintah input untuk menentukan tipe tiket apa yang akan diambil, (Reguler/VIP?) Member(Ya/Tidak?) :
![gambar1](ss/2.png)

### Step 3 : Seleksi Tipe Tiket dan Kartu Member untuk diskon
Beri seleksi untuk menentukan Tipe Tiket yang diambil, Reguler atau VIP tarik inputan dari Step 2, lalu input diskon 20% jika memiliki Kartu Member :
![gambar1](ss/3.png)

### Step 4 : Total harga 
Masukan Total Harga Tiket yang diambil, tarik inputan dari step 3 untuk menemukan totalnya :
![gambar1](ss/4.png)

### Step 5 : Output 
Print output dari Total Harga Tiket yang sudah diambil :
![gambar1](ss/5.png)

### Step 6 : Test Code Program
Uji coba code program dengan menginput Tiket VIP dan memiliki Kartu Member, maka total harganya adalah Rp80.000:
![gambar1](ss/10.png)

## FLOWCHART PEMESANAN TIKET BIOSKOP

### Step 1 : Start
Buat titik start untuk awalan untuk memulai sesuatu dengan bentuk terminator :


### Step 2 : Input 
Lalu buat Input untuk Tipe Tiket yang akan diambil, dan Input untuk Member :


### step 3 : Decision Tiket Reguler dan VIP
Selanjutnya lakukan seleksi, jika reguler YA maka akan mengarah ke harga tiket Rp50.000, jika TIDAK maka akan mengarah ke Tiket VIP yang berharga Rp100.000 :


### Step 4 : Decision Tiket Member
Setelah itu, dari step sebelumnya Input member menuju Decision Tiket Member, Tiket Reguler dan Tiket VIP mengikuti jalur menuju Decision Tiket Member juga untuk seleksi apakah memiliki Kartu Member atau Tidak, jika YA maka akan dapat diskon 20%, jika tidak menuju step selanjutnya :
 

### Step 5 : End
Step selanjutnya print output Total Harga yang harus dibayar, lalu menuju titik berhenti :




## CODE PROGRAM KALKULATOR SEDERHANA

### Step 1 : Perintah Input angka1 dan angka2
Masukan perintah Input angka1 dan angka2 dengan menggunakan Integer :
![gambar1](ss/6.png)

### Step 2 : Perintah Input Operator 
Selanjutnya beri perintah Input untuk menentukan Operator (Pertambahan +, Pengurangan -, Perkalian *, Pembagian /) :
![gambar1](ss/7.png)

### Step 3 : Seleksi Operator
Kemudian lakukan seleksi Operator :
Jika operator Penjumlahan maka angka1 + angka2
Jika operator Pengurangan maka angka1 - angka2
Jika operator Perkalian maka angka1 * angka2
Jika operator Pembagian ada dua hal 
	Jika angka2 != 0 maka angka1 / angka2
	Jika angka2 = 0 maka eror
![gambar1](ss/8.png)

### Step 4 : Print Output
Langkah terakhir buat output untuk menampilkan hasil dari perhitungan :
![gambar1](ss/9.png)

### Step 5 : Uji Coba
Uji coba code program kalkulator sederhana dengan menginput angka1 = 70, dan angka2 = 65 dengan operator pengurangan :
![gambar1](ss/11.png)


## FLOWCHART KALKULATOR SEDERHANA

### Step 1 : Start
Buat titik awal mulai dengan terminator :


### Step 2 : Input angka1 dan angka2
Langkah selanjutnya buat input untuk angka1 dan angka2 :


### Step 3 : Input Operator
Kemudian buat input Operator untuk menentukan Operator yang dipakai :


### Step 4 : Decision Operator
Lakukan lah seleksi Operator yang dipakai (Penjumlahan +, Pengurangan -, Perkalian *, Pembagian /) :


### Step 5 : Decision Pembagian
Kembali ke alur pembagian, lakukan decision pembagian jika angka2 = 0 (Ya/Tidak)? :
Ya = Eror
Tidak = Lakukan Pembagian 


### Step 6 : Output
Print output Hasil dari semua Operator yang diinputkan :


### Step 7 : End
Buat titik akhir berhenti untuk menghentikan proses :



## KESIMPULAN
Dari Laporan Praktikum 2 diatas, saya dapat mengambil kesimpulan penggunaan if, elfi dan else sangat berguna untuk menentukan seleksi. Decision ini digunakan untuk mencari hasil dari 2 kasus yang sudah ditampilkan, penentuan Tiket Bioskop Reguler dan VIP jika memiliki Kartu Member maka akan mendapatkan diskon 20%, maka dari itu penggunaan Struktur Kondisi sangat penting didalam Code Pemrograman Python atau pun Flowchart.

Pada kasus 2 yang diminta untuk membuat kalkulator sederhana, dalam kasus ini pada jalur Pembagian diberikan decision untuk menentukan angka2 != 0, jika angka2 = 0 maka akan eror ini dikarenakan pembagian tidak boleh NOL (0).