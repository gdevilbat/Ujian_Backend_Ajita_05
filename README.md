# Soal Ujian Purwadhika Back-End Dev

![Lintang_Purwadhika](https://static.wixstatic.com/media/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png/v1/fill/w_246,h_39,al_c,usm_0.66_1.00_0.01/2e6af2_f69a4271c3534ae1869a7ed63e278b2b~mv2.png)

**Materi Back End Web Dev dapat diakses di [klik sini!](https://github.com/LintangWisesa/Purwadhika-JC05-03_BackEndWeb)**

#

### **Soal 1 - MySQL Database**

1. Tuliskan langkah-langkah/urutan query MySQL untuk membuat sebuah database **"Toko"** yang memiliki tabel **"Produk"** dengan data sebagai berikut:

    ![Soal_1.1](https://3.bp.blogspot.com/-7hiJnB9dKxs/W0U6tSXbP0I/AAAAAAAAERU/mwIGEQ9rQZoIzpucw16AHha_iJB3-IXgACLcBGAs/s1600/Soal_2a.png)

2. Dari tabel **"Produk"** di database **"Toko"**, tuliskan query MySQL untuk menampilkan seluruh data, dikelompokkan berdasarkan kolom _**kota**_. Hasil yang diharapkan sebagai berikut:

    ![Soal_1.2](https://4.bp.blogspot.com/-h3qI7a1HNfc/W0U6tWaKbiI/AAAAAAAAERY/dKGTXNQphp8FpSLe9vquAc4scWbzB3ohQCLcBGAs/s1600/Soal_2b.png)

3. Dari tabel **"Produk"** di database **"Toko"**, tuliskan query MySQL untuk menampilkan data produk dengan _**harga tertinggi di setiap kota**_, kemudian diurutkan berdasarkan kolom _**harga**_. Hasil yang diharapkan sebagai berikut:

    ![Soal_1.3](https://1.bp.blogspot.com/-BWCRTITLkEQ/W0U6tJUMWZI/AAAAAAAAERQ/ukGByJT5nsow29coBgdZkZPFlKst6oQXwCLcBGAs/s1600/Soal_2c.png)

4. Dari tabel **"Produk"** di database **"Toko"**, tuliskan query MySQL untuk menampilkan data produk dengan _**harga terendah**_. Hasil yang diharapkan sebagai berikut:

    ![Soal_1.4](https://2.bp.blogspot.com/-hIW5cFVDRRo/W0U6uMDG9ZI/AAAAAAAAERc/LsTu2LmW-okuHw4MAQ65rIVmtd9C2XjfACLcBGAs/s1600/Soal_2d.png)

    _**Catatan:**_ _Soal ini hanya meminta Anda untuk menuliskan langkah-langkah/urutan query MySQL sesuai spesifikasi di atas. Ketik jawaban dalam sebuah file __.txt__ & lampirkan via email!_

#

### **Soal 2 - Express & MongoDB**

Buatlah sebuah project back-end NodeJS (Express) sederhana yang mampu mengakses database MongoDB, dengan spesifikasi route sebagai berikut:

- __*POST /data*__ &rarr; akan memasukkan data ke collection **"data"** di database **"dataCPU"**. Data yang diinput adalah data seputar sistem operasi yang digunakan user, mencakup: **nama CPU, tipe OS, platform OS, versi rilis OS, RAM tersisa** dan **RAM total**. Data yang diinput tidak perlu dideklarasikan di _**body request**_.

- **_GET /data_** &rarr; akan memberikan response: menampilkan semua data dari collection **"data"** di database **"dataCPU"**. Data yang tersimpan diharapkan sebagai berikut:

    ```bash
    {   
        _id: 5b453fb83de88413bc523928,
        namacpu: 'Lintang_CPU',
        tipe: 'Windows_NT',
        platform: 'win32',
        rilis: '10.0.17134',
        ramSisa: 11338039296,
        ramTotal: 17063497728
    }
    ```

    _**Catatan:**_ _Upload source code project ke __Github__ Anda, kemudian ketik kode jawaban dalam sebuah file __.txt__. Lampirkan via email, sertakan pula __url link__ ke repo project Github Anda._

#

### **Soal 3 - Express & MySQL**

Buatlah sebuah project back-end NodeJS (Express) sederhana yang mampu mengakses database MySQL, dengan spesifikasi route sebagai berikut:

- __*POST /karyawan*__ &rarr; akan memasukkan data ke tabel **"karyawan"** di database **"toko"**. Data yang diinput via _**body request**_ hanyalah **nama** dan **tglLahir** (dalam _**JSON**_), sebagai contoh:

    ```json
    {
        "nama": "Lintang",
        "tglLahir": "26-11-1992"
    }
    ```
    
    Kemudian hasil yang tersimpan di tabel __"karyawan"__ tersusun atas kolom __no, nama, hari, bulan, tahun, zodiak__ dan __usia__. Hasil yang diharapkan sebagai berikut:

    ![Soal_4](https://3.bp.blogspot.com/-74OaRJ5oM90/W0VJq7Qm8aI/AAAAAAAAER0/HOEF0qreMWIrowzHDNqb4wkqOXver1TNQCLcBGAs/s1600/Soal4.png)

- **_GET /karyawan_** &rarr; akan memberikan response: menampilkan semua data dari tabel **"karyawan"** di database **"toko"**. Adapun klasifikasi kolom __zodiak__ disajikan pada gambar berikut:

    ![zodiak](https://1.bp.blogspot.com/-fZAEel3MI-s/W0VkJFrz-vI/AAAAAAAAESA/FSgalYKRydg0fBQAzYUFrHd2PhDWcswzACLcBGAs/s1600/zodiak_20151128_202626.jpg)

    _**Catatan:**_ _Upload source code project ke __Github__ Anda, kemudian ketik kode jawaban dalam sebuah file __.txt__. Lampirkan via email, sertakan pula __url link__ ke repo project Github Anda._

#

### *__#HappyCoding__*

#### Lintang Wisesa :love_letter: _lintangwisesa@ymail.com_

[Facebook](https://www.facebook.com/lintangbagus) | 
[Twitter](https://twitter.com/Lintang_Wisesa) |
[Google+](https://plus.google.com/u/0/+LintangWisesa1) |
[Youtube](https://www.youtube.com/user/lintangbagus) | 
:octocat: [GitHub](https://github.com/LintangWisesa) |
[Hackster](https://www.hackster.io/lintangwisesa)
