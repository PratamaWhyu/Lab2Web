|*Nama|NIM|Kelas|Matkul*|
|----|---|-----|------|
|Pratama Wahyu Prasetyo|312310395|TI.23.A4|Pemograman Web 1|

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![image](https://github.com/user-attachments/assets/4dd573d8-f4f9-4166-961b-932c6df7fc8f)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
Deklarasi  h1 {...} ini menargetkan semua elemen h1 pada seluruh halaman web, jadi Setiap elemen h1 yang ada di dalam dokumen HTML akan mendapatkan gaya yang didefinisikan dalam blok ini.
Deklarasi dengan #intro h1 {...} ini lebih spesifik, karena menargetkan elemen h1 yang ada di dalam elemen dengan id intro.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

dikarenakan  inline CSS ini memiliki prioritas tertinggi. Gaya yang ditulis langsung pada elemen HTML akan selalu dijalankan jika ada konflik dengan gaya lain.
contoh
![image](https://github.com/user-attachments/assets/39bfa105-c1d0-444e-aa09-6658a28f3d99)

![image](https://github.com/user-attachments/assets/e862d5e7-90b6-4330-8eb9-13fedc2acbe5)
hasil
![image](https://github.com/user-attachments/assets/56c0474a-1aa0-41be-b164-ab67f4ed587e)


4.Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
jika ada elemen yang memiliki deklarasi CSS dengan ID dan Class, maka gaya dari ID akan menjadi prioritas karena spesifisitasnya lebih tinggi dibandingkan dengan class
![image](https://github.com/user-attachments/assets/25c02904-43c7-484c-ad4a-1bf3f199c893)
![image](https://github.com/user-attachments/assets/1cf92f23-3d44-42ef-8e86-b7986f584b52)

