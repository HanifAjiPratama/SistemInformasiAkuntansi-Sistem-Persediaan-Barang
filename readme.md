# Sistem Informasi Akuntansi - Sistem-Persediaan-Barang

## 📖 Pendahuluan
Dibuat untuk memenuhi tugas mata kuliah Sistem Informasi Akuntansi

Hanif Aji Pratama<br>

12030122140345<br>

Sistem Informasi Akuntansi<br>

Kelas A (S1 Akuntansi)<br>

## ℹ️ Deskripsi
Sistem Persediaan Barang adalah aplikasi berbasis Web untuk mengatur dan mencatat keluar masuk barang di masing-masing gudang dalam satu perusahaan, yang meliputi pencatatan barang masuk dari Supplier dan pencatatan barang keluar.

## 📜 Fitur Utama
  1. Fitur Login
    <ul type="square">
    <li>otentifikasi pengguna sebagai pengaman</li>
    <li>Masing-masing user punya tempat sendiri</li>
    </ul>
    
  2. Fitur Admin
     <ul type="square">
     <li>Bisa mengelola data barang yang keluar atau masuk</li>
     <li>Bisa mengelola data supplier</li>
     </ul>
 
  3. Fitur Kasir
    <ul type="square">
    <li>mencatat transaksi yang terjadi</li>
		</ul>

  4. Fitur Pemilik
     <ul type="square">
		 <li>Terdapat laporan penjualan harian, bulanan, dan tahunan</li>
	 	 <li>Bisa mengelola data user</li>
		 </ul>
	 
  ## 🔑 Akun tersedia
  <strong>Login default : </strong>
  1. Login Admin :
  <ul type="square">
    <li>username = admin </li>
    <li>password = admin</li>
   
  </ul>
 
  2. Login Kasir
   <ul type="square">
    <li>username = kasir</li>
    <li>password = kasir</li>
     
  </ul>

  3. Login Pemilik
	 <ul type="square">
	  <li>username = pemilik</li>
	  <li>password = pemilik</li>

   </ul>

  <h2 id="download">🐱‍💻 Panduan Menjalankan & Install Aplikasi</h2>

Untuk menjalankan aplikasi atau web ini kamu harus install XAMPP dan mempunyai setidaknya satu web browser yang terinstall di komputer anda.

```bash
# Clone repository ini atau download di
$ git clone https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang.git

# Buat database
Buat database dengan nama "persediaan" di DMBS [phpmyadmin, dll]

# Upload database
Arahkan folder ke Sistem-Persediaan-Barang/database/persediaan.sql & upload ke dbms [phpmyadmin]

# Cut Folder SistemInformasiAkuntansi-Sistem-Persediaan-Barang
Paste di folder xampp/htdocs

# Buka browser
localhost/SistemInformasiAkuntansi-Sistem-Persediaan-Barang

# Enjoy, jika ingin login maka liat panduan akun diatas
```

<p></p>

## 💾 Database MySQL (phpMyAdmin)

* **Struktur Database Persediaan**<br>

    ![Screenshot 2023-12-02 175505](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/2b1818a8-3813-4ab8-8754-152309672b4f)

* **Alur Primary Key**<br>

    ![Screenshot 2023-12-02 181428](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/70f994a9-a671-440a-a287-81759cdfa96d)

## ⌗ Flowchart dan Entity Relationship Diagram

* **Flowchart**<br>

    ![flowuas](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/26094767-761a-477b-9bba-a82653ca737d)

* **Entity Relationship Diagram**<br>

    ![ERD](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/16616bb5-011f-404d-b4ac-91b8d9f129fe)
  


## 🔎 Tampilan Sistem Persediaan Barang Secara Lengkap

* **Log in page**<br>
    Tampilan Log in Page. anda bisa memasukkan username dan admin sesuai dengan role anda (admin, pemilik, atau kasir)

    ![login page](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/27d6b14a-1e50-4f08-a1c5-c6a65b2a2158)

* **Dashboard admin**<br>
    Pada halaman ini tersedia beberapa informasi seperti foto di bawah ini 

    ![dashbord admin](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/89044a74-66ec-492e-a439-6809f30bdbac)


* **Fitur Kelola Data Supplier**<br>

    ![data supplier](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/ba1abb62-0e18-4228-95c7-000e12f202fb)

	 ![create new supplier](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/916a868b-1082-49f4-9392-3e461034c307)
  
* **Fitur Kelola Data Produk**<br>

    ![produk masuk](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/944635cf-0090-4ab2-9991-c99955b78039)
  
   ![produk keluar](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/34be899b-3feb-48f6-b025-c34ba08f6fe0)

* **Transaksi Supplier**<br>

    ![transaksi supplier](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/da6c38c6-9345-49d6-a78c-ea508101140b)
  
   ![tambah transaksi supplier](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/b34a8504-4473-4da0-a9c0-92c0b0aa6603)

    ![detail transaksi](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/d7a73322-e78f-45ee-83c7-366d0763af98)
  
* **Dashboard Kasir**<br>

    ![dasb kasir](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/a9df47f5-38d0-485b-92dd-08641d71622c)
  

* **Transaksi**<br>

    ![daftar transaksi](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/5c23068f-2102-4b28-953d-4d4a0b40b1ad)
  
    ![penambahan transaksi](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/778727b1-5c5d-4432-82f7-02bdd59647ec)

  	![invoice transaksi](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/3e37352a-7a90-47cd-88f6-d12e19d58649)


* **Dashboard Pemilik**<br>

    ![dashboard pemilik](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/39383237-d02f-4cf7-bf75-7fff365382e7)

  
* **Kelola Data User**<br>

   ![kelola data user](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/3805edea-b85c-4957-8059-d5d4034f7ae5)


* **Laporan Penjualan**<br> 

   ![laporan penjualan](https://github.com/HanifAjiPratama/SistemInformasiAkuntansi-Sistem-Persediaan-Barang/assets/152667922/88ff7da7-3c5e-4465-a29b-cf120da4f5a7)

  
## 💻 Dibuat dengan
* PHP - Scripting languaga versi 7 
* MySQL - Database management system

  
## ⚠️ Disclaimer
* Code licensed under MIT License
* untuk menjalankan aplikasi
http://localhost/persediaan/index.php/controllerLogin
