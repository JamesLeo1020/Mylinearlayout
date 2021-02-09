# Mylinearlayout
![Alt Text](https://github.com/leo-chan1020/Mylinearlayout/blob/master/Mylinearlayout.jpg)
# MyRelativeLayout
![Alt Text](https://github.com/leo-chan1020/Mylinearlayout/blob/master/MyRelativeLayout.jpg)
# MyIntent
![Alt Text](https://github.com/leo-chan1020/MyIntent/blob/master/1MyIntent.jpg)
![Alt Text](https://github.com/leo-chan1020/MyIntent/blob/master/2MyIntent.jpg)

#Berikan penjelasan dari perbedaan linear layout, relative layout, dan constrain layout.
Linear Layout adalah jenis layout dimana user menempatkan 1 objek per baris atau kolom secara sejajar. Jadi di dalam setiap baris atau kolom hanya ada 1 objek 
yang bisa ditempatkan . Linear Layout ini ada dua jenis . Yaitu :
Linear Layout Vertical (Objek per baris/kesamping) 
Linear Layout Horizontal (Objek per kolom/kebawah)

Relative Layout adalah jenis layout yang memiliki karakteristik dalam menempatkan view secara relatif (Baca apa itu relatif disini).
Relatif disini berarti posisi dari setiap view bergantung kepada view yang lain. Simplenya adalah, kita bebas untuk menempatkan objek 
yang diinginkan sesuka hati kita. Penempatan satu objek bisa dimana saja mau di sisi kanan, kiri, atas, ataupun bawah dari objek lain. 
Jika tidak di tetapkan, maka objek dapat menumpuk antara satu objek dengan objek yang lain. 
Intinya dalam relative layout itu tata letak objek harus benar-benar diperhatikan.

Constarint Layout memungkinkan kita membuat tata letak yang besar dan kompleks dengan tampilan datar. Ini hampir mirip dengan Relative Layout 
karena semua tampilan ditata berdasarkan hubungan antara satu objek dengan yang lain, tetapi lebih fleksibel daripada RelativeLayout dan lebih 
mudah digunakan dengan Editor Layout Android Studio.


#Jelaskan method onCreate dan onPause pada activity.
onCreate
Anda harus menerapkan callback ini, yang aktif saat sistem pertama kali membuat aktivitas. Pada pembuatan aktivitas, aktivitas memasuki status Dibuat. 
Dalam metode onCreate(), Anda menjalankan logika startup aplikasi dasar yang hanya boleh terjadi sekali selama siklus aktivitas. Misalnya, implementasi 
onCreate() mungkin mengikat data ke daftar, mengaitkan aktivitas dengan ViewModel, dan membuat instance beberapa variabel lingkup class. Metode ini menerima 
parameter savedInstanceState, yang merupakan objek Bundle yang berisi status aktivitas yang sebelumnya disimpan. Jika aktivitas belum pernah ada sebelumnya,
nilai objek Bundle adalah nol.

onPause
Sistem akan memanggil metode ini sebagai indikasi pertama bahwa pengguna meninggalkan aktivitas Anda (meskipun tidak selalu berarti aktivitas sedang ditutup); 
hal ini menunjukkan bahwa aktivitas tidak lagi di latar depan (meskipun mungkin masih terlihat jika pengguna berada dalam mode multi-jendela). 
Gunakan metode onPause() untuk menjeda atau menyesuaikan operasi yang tidak boleh dilanjutkan (atau harus dilanjutkan dalam jumlah sedang) sementara Activity 
berada dalam status Dijeda, dan Anda berharap untuk segera melanjutkan. Ada beberapa alasan mengapa suatu aktivitas dapat memasuki status ini.
