#  E-Restaurant
>Membantu customer untuk memesan melalui aplikasi yang telah disediakan sehingga dapat mengurangi antrian panjang dan mempercepat penyajian pesanan

#### Panduan Import Database
1. Run PgAdmin 4 lalu masukkan password postgre
2. Setelah berhasil masuk, klik kanan pada database yanga ada pada sisi kiri
3. Pilih Create Database dan beri nama database menjadi "e-Rest" lalu klik save
4. Pada database e-Rest klik kanan dan pilih restore
5. Isi atau browse filename berdasarkan path lokasi e-Rest.sql tersimpan
6. Klik Restore dan database siap digunakan


#### Panduan Menggunakan Aplikasi E-restaurant 
- Mengganti connection string local host yang ada pada file Data.cs dan NoPesanan.cs berdasarkan database postgre masing masing, contohnya seperti gambar di bawah
  ![image](https://user-images.githubusercontent.com/79191854/203219352-bad928f9-dc03-4fc7-9a69-c4cd4095a0de.png)
- Kemudian User bisa menjalankan program
- User memasukkan nama dan jumlah pesanan sesuai menu yang tersedia, kemudian klik add order
- Nomor pesanan akan ter generate saat user melakukan add order
- Apabila User ingin membuat pesanan baru, user bisa klik button new order 
- Pada halaman Login, user disini posisinya sebagai admin, dapat melakukan log in dengan memasukkan username dan password yang telah di tetapkan
- Pada halaman admin, User dapat memilih data mana yang akan dihapus berdasarkan no pesanan yang ada, dengan memilih kolom no pesanan, kemudian tekan button delete       order, pesanan akan terhapus
- Pada halaman Admin, User juga dapat melakukan pencarian pada search bar untuk mencari data pada database, dengan meinputkan nama dari customer
- Untuk keluar dari halaman admin, user dapat memilih tombol exit yang ada di pojok kanan atas jendela.



#### HANGRY
Ketua Kelompok : Maria Anastasia Tambunan - 20/460551/TK/511

- Anggota 1 : Adinda Luthfiah S - 20/463587/TK/51579
- Anggota 2 : Wardatul Radhiyyah - 20/456381/TK/50511
  
