penjelasan array

![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125117.jpg)
1. Inisialisasi (Foto 1)
List = []
Ini adalah tahap deklarasi. Di sini, kamu menyiapkan sebuah wadah kosong. Analoginya seperti menyiapkan buku absen yang masih kosong sebelum diisi nama mahasiswa.

![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125137.jpg) 
2. Mengisi Data / Input (Foto 2)
Pada bagian ini, kamu menggunakan perulangan (for i in range(10)).

Konsep Indeks: Array memiliki nomor urut yang dimulai dari 0. Jadi, angka pertama yang dimasukkan akan menempati indeks 0, angka kedua di indeks 1, dan seterusnya.

Method .append(): Fungsi ini digunakan untuk "menempelkan" atau menambahkan data baru ke posisi paling belakang dalam list tersebut secara dinamis.

![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125157.jpg) 
3. Pengolahan Data Statistik (Foto 5)
Foto ini menunjukkan bahwa Array sangat kuat untuk pengolahan data massal menggunakan fungsi bawaan Python:

max(list): Mencari nilai tertinggi di dalam seluruh elemen array.

min(list): Mencari nilai terendah.

sum(list) / len(list): Menjumlahkan seluruh isi array lalu membaginya dengan jumlah elemen (panjang array) untuk mendapatkan rata-rata.

![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125214.jpg) 
![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125258.jpg) 
4. Visualisasi Data (Foto 6 & 9)
Konsep Array sangat krusial dalam pembuatan grafik menggunakan library matplotlib.

Sumbu X biasanya mengambil urutan indeks atau kategori.

Sumbu Y mengambil nilai-nilai yang tersimpan di dalam array tersebut.
Tanpa struktur array, kita akan kesulitan memplot banyak titik datsekaligusus ke dalam sebuah grafik.

![nj](https://github.com/gusmanwijaya-create/ib/blob/main/IMG_20260315_125240.jpg) 
5. Logika Iterasi & Kondisional (Foto 7)
for nilai in list:
Ini adalah konsep traversal (menelusuri isi array). Program akan mengecek satu per satu isi "laci" tadi. Jika nilai di dalam laci tersebut memenuhi syarat (misalnya >= 60), maka akan dikategorikan sebagai "Lulus". Ini  Pytho bagaimana array digunakan untuk memisahkan atau mengelompokkan data berdasarkan kriteria tertentu.

hasil array
![nj](https://github.com/gusmanwijaya-create/ib/blob/main/Screenshot_2026-03-15-12-23-41-740_com.android.chrome.jpg) 
![nj](https://github.com/gusmanwijaya-create/ib/blob/main/Screenshot_2026-03-15-12-23-48-397_com.android.chrome.jpg) 
![nj]() 

3. Analisis tertentuitas
Analisis ini melihat seberapa efisien algoritma yang digunakan dalam kode tersebut:

Kompleksitas Waktu (O(n)):

Proses input menggunakan perulangan for i in range(10), yang artinya berjalan linear sesuai jumlah data (n).

Pencarian nilai max(), min(), dan sum() juga memproses setiap elemen satu per satu, sehingga kompleksitasnya adalah O(n).

Kompleksitas Ruang (O(n)):

Karena kita menyimpan semua 10 input ke dalam satu variabel list, ruang memori yang dibutuhkan akan bertambah besar seiring bertambahnya jumlah input mahasiswa.

4. Refleksi Pembelajaran
Melalui praktikum ini, beberapa poin pembelajaran penting yang didapatkan adalah:

Otomasi Data: Memahami bahwa penggunaan list dan looping jauh lebih efisien daripada menulis kode secara manual untuk setiap data.

Logika Pengkondisian: Penggunaan if-else untuk menentukan kategori "Lulus" atau "Tidak Lulus" memberikan pemahaman tentang cara sistem mengambil keputusan berdasarkan standar nilai tertentu.

Pentingnya Visualisasi: Angka mentah (raw data) terkadang sulit dibaca. Dengan bantuan library matplotlib, data tersebut menjadi jauh lebih mudah dipahami secara visual melalui grafik batang.

Ketelitian Input: Nilai minimum 0 dan maksimum 100 menunjukkan bahwa program dapat menangani rentang nilai yang ekstrim dengan baik.
