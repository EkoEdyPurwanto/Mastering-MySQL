## Latihan
1. buat database <font color="red">'STORE'</font> , lalu jalankan perintah untuk menampilkan database yg antum buat. <font color="orange">[SCRENSHOOT]</font>
2. buat table <font color="red">'Order'</font> dalam database <font color="red">'STORE'</font> dengan kolom dan type data seperti berikut:
    - **id_pesanan** = type data nya number(bebas), buat kolom ini unik dan auto_increment
    - **nama_pemesan** = type data nya string(bebas) , tidak boleh kosong value nya
    - **nama_barang** = type data nya string(bebas) , tidak boleh kosong value nya
    - **alamat_pemesan** = type data nya string(bebas) , tidak boleh kosong value nya
    - **metode_pembayaran** = batasi value nya dengan type data enum(BCA, BSI, BNI) 
    - **status_pengiriman** = batasi value nya dengan type data enum(In Process, Shipped, Delivered)
    - **harga_produk** = type data nya number(bebas) , tidak boleh kosong value nya
    - **biaya_pengiriman** = type data nya number(bebas) , tidak boleh kosong value nya
    - **total_pembayaran** = type data nya number(bebas) , tidak boleh kosong value nya
    - **order_date** = type data nya timestamp
      lalu jalankan perintah untuk menampilkan table yg antum buat <font color="orange">[SCRENSHOOT]</font> dan tampilkan skema table yang antum buat <font color="orange">[SCRENSHOOT]</font>
3. masukkan data ke dalam table <font color="red">'Order'</font> (2 data),
   untuk kolom namanya wajib menggunakan value di bawah ini:
   id = 1 <font color="blue">ustad.mika</font> 
   dan id yg ke 2 <font color="blue">ustadz.nashrul</font>
   lalu jalankan perintah untuk menampilkan isi table yg antum masukkan sebelumnya. <font color="orange">[SCRENSHOOT]</font>
4. hapus id ke 2 , cek apakah sudah terhapus <font color="orange">[SCRENSHOOT]</font>
5. update value pada kolom = nama, id = 1
   dari 1.ustadz.mika = nama antum<font color="orange">[SCRENSHOOT]</font>
6. ubah nama table dari <font color="red">'Order'</font> ke <font color="red">'Pesanan'</font> <font color="orange">[SCRENSHOOT]</font>
7. export database <font color="red">'STORE'</font> dengan fileName = nama antum, contoh: eko.sql
