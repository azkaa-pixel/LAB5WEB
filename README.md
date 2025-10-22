# LAB - 5 - WEB

Nama : Ghefira Azka Fardani 

NIM : 312410521

Kelas : TI.24.A5

### 1. Membuat Dokumen HTML dan Menulis Kode JavaScript
buat file dengan nama ```lab5_javascript.html```

```html
<!DOCTYPE html>
<html>
<head>
  <title>Pengenalan JavaScript</title>
</head>
<body>
  <h1>Pengenalan JavaScript</h1>

  <script>
    document.write("Hello World");
  </script>
</body>
</html>
```

#### ```- penjelasan``` : 

```<script>``` → tempat nulis kode JavaScript di dalam HTML.

```document.write("Hello World");``` → perintah untuk menampilkan tulisan Hello World di halaman web.

#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/1.png)

### 2. Menampilkan Output dengan Alert, Prompt, dan Console
menambahkan kode ini 

```html
<!DOCTYPE html>
<html>
<head>
  <title>Pengenalan JavaScript</title>
</head>
<body>
  <h1>Pengenalan JavaScript</h1>

  <script>
    alert("Selamat datang di halaman JavaScript!");
    let nama = prompt("Masukkan nama Anda:");
    document.write("Halo, " + nama + "<br>");
    console.log("Nama Anda adalah: " + nama);
  </script>

</body>
</html>
```

#### ```- penjelasan``` : 

```alert()``` → bikin jendela pop-up berisi teks.

```prompt()``` → minta pengguna ngetik sesuatu.

```document.write()``` → nulis hasilnya ke halaman web.

```console.log()``` → tampilkan hasil ke console (cek di Inspect → Console).


#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/2(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/2(2).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/2(3).png)

### 3. Membuat dan Memanggil Fungsi di JavaScript
tambahkan kode ini 

```html
<script>
  function pesan() {
    alert("Memanggil fungsi di JavaScript!");
  }
</script>

<button onclick="pesan()">Klik Saya</button>

```
#### ```- penjelasan``` : 

```function pesan()``` → membuat fungsi bernama pesan.

```alert("Memanggil fungsi di JavaScript!")``` → pesan yang muncul saat fungsi dijalankan.

```onclick="pesan()"``` → tombol ini akan memanggil fungsi ```pesan()``` waktu diklik.


#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/3(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/3(2).png)

### 4. Membuat Fungsi dengan Parameter
tambahkan kode ini 

```html
<script>
  function tampilkanNama(nama) {
    alert("Halo, " + nama);
  }
</script>

<button onclick="tampilkanNama('Gpiipie')">Klik Nama</button>
```

#### ```- penjelasan``` :

```function tampilkanNama(nama)``` → bikin fungsi yang butuh parameter nama.

```alert("Halo, " + nama)``` → munculkan pesan sesuai isi parameter.

```onclick="tampilkanNama('Gpiipie')"``` → saat tombol diklik, fungsi dijalankan dan parameter diisi ```'Gpiipie'```.

#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/4(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/4(2).png)

### 5. Input dan Output pada JavaScript
tambahkan kode ini

```html
  <hr>
  <h3>Input dan Output</h3>
  <input type="text" id="namaInput" placeholder="Masukkan nama">
  <button onclick="tampil()">Tampilkan</button>
  <p id="hasil"></p>

  <script>
    function tampil() {
      let nama = document.getElementById("namaInput").value;
      document.getElementById("hasil").innerHTML = "Halo, " + nama;
    }
  </script>
```

#### ```- penjelasan``` :

```<input type="text" id="namaInput">``` → untuk mengetik nama kamu.

```<button onclick="tampil()">``` → saat diklik, akan menjalankan fungsi ```tampil()```.

```document.getElementById("namaInput").value``` → mengambil teks dari input.

```innerHTML``` → menampilkan hasilnya ke elemen ```<p>``` di bawahnya.

#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/5(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/5(2).png)

### 6. Struktur Percabangan IF...ELSE

```html
  <hr>
  <h3>Percabangan IF...ELSE</h3>

  <script>
    let nilai = prompt("Masukkan nilai Anda:");
    if (nilai >= 60) {
      document.write("Selamat, Anda Lulus!<br>");
    } else {
      document.write("Maaf, Anda Tidak Lulus.<br>");
    }
  </script>
```

#### ```- penjelasan``` :

```prompt()``` digunakan untuk meminta pengguna memasukkan nilai.

```if (nilai >= 60)``` → kondisi ini dicek, kalau benar maka tampil “Lulus”.

```else``` → dijalankan kalau kondisi salah, jadi tampil “Tidak Lulus”.

```document.write()``` digunakan untuk menulis hasil langsung ke halaman web.

#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/6(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/6(2).png)

### 7. Struktur SWITCH  

```html
  <hr>
  <h3>Percabangan SWITCH</h3>

  <script language="javascript">
    function test() {
      val1 = window.prompt("Input nilai (1-5):");
      switch (val1) {
        case "1":
          document.write("bilangan satu");
          break;
        case "2":
          document.write("bilangan dua");
          break;
        case "3":
          document.write("bilangan tiga");
          break;
        case "4":
          document.write("bilangan empat");
          break;
        case "5":
          document.write("bilangan lima");
          break;
        default:
          document.write("bilangan lainnya");
      }
    }
  </script>

  <button onclick="test()">Switch Case</button>
```

#### ```- penjelasan``` :

```window.prompt()``` → menampilkan kotak input di browser untuk memasukkan nilai.

```switch(val1)``` → digunakan untuk membandingkan isi variabel ```val1``` dengan beberapa ```case```.

```case "1":``` hingga ```case "5"```: → setiap nilai punya hasil keluaran berbeda.

```break;``` → menghentikan proses supaya tidak lanjut ke ```case``` berikutnya.

```default:``` → dijalankan kalau nilai yang dimasukkan tidak cocok dengan salah satu ```case```.

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/7(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/7(2).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/7(3).png)

### 8. Tugas 1: Validasi Form 

```html
  <hr>
  <h3>Form Validasi</h3>

  <form name="formKu" onsubmit="return validasi()">
    Nama: <input type="text" name="nama"><br>
    Email: <input type="text" name="email"><br>
    <input type="submit" value="Kirim">
  </form>

  <script language="javascript">
    function validasi() {
      var nama = document.forms["formKu"]["nama"].value;
      var email = document.forms["formKu"]["email"].value;

      if (nama == "" || email == "") {
        alert("Nama dan Email tidak boleh kosong!");
        return false;
      } else {
        alert("Data berhasil dikirim!");
        return true;
      }
    }
  </script>
```
#### ```- penjelasan``` :

```onsubmit="validasi()"``` → setiap kali tombol Kirim ditekan, fungsi ```validasi()``` akan dijalankan.

```document.forms["formKu"]["nama"].value``` → mengambil isi dari kolom input nama.

Jika salah satu kosong, akan tampil ```alert``` dan proses form berhenti (```return false```).

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/8%20(1).png)
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/8(2).png)

### 9. Tugas 2: Perhitungan Otomatis (Checkbox)

```html
  <hr>
  <h3>Hitung Total Harga Otomatis</h3>

  <form name="formHitung">
    <input type="checkbox" id="item1" value="10000" onclick="hitung()"> Nasi Goreng (Rp10.000)<br>
    <input type="checkbox" id="item2" value="5000" onclick="hitung()"> Es Teh (Rp5.000)<br>
    <input type="checkbox" id="item3" value="8000" onclick="hitung()"> Ayam Goreng (Rp8.000)<br><br>
    Total: <input type="text" id="total" value="0" readonly>
  </form>

  <script language="javascript">
    function hitung() {
      var total = 0;
      if (document.getElementById("item1").checked) {
        total += parseInt(document.getElementById("item1").value);
      }
      if (document.getElementById("item2").checked) {
        total += parseInt(document.getElementById("item2").value);
      }
      if (document.getElementById("item3").checked) {
        total += parseInt(document.getElementById("item3").value);
      }
      document.getElementById("total").value = total;
    }
  </script>
```

#### ```- penjelasan``` :
```<input type="checkbox">``` → digunakan untuk memilih beberapa item sekaligus.

```onclick="hitung()"``` → setiap kali checkbox diklik, fungsi ```hitung()``` akan dijalankan.

```if (document.getElementById(...).checked)``` → memeriksa apakah checkbox dalam kondisi terpilih atau tidak.

```document.getElementById("total").value = total;``` → menampilkan total harga akhir ke dalam textbox hasil.

#### ```- hasil```
![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/9.png)

# TUGAS 

### 1. Buat script untuk melakukan validasi pada isian form.

### jawaban :

#### ```- kode program```

```html
<!DOCTYPE html>
<html>
<head>
  <title>Validasi Form</title>
</head>
<body>
  <h3>Form Validasi</h3>

  <form name="formKu" onsubmit="return validasi()">
    Nama: <input type="text" name="nama"><br>
    Email: <input type="text" name="email"><br>
    <input type="submit" value="Kirim">
  </form>

  <script language="javascript">
    function validasi() {
      var nama = document.forms["formKu"]["nama"].value;
      var email = document.forms["formKu"]["email"].value;

      if (nama == "" || email == "") {
        alert("Nama dan Email tidak boleh kosong!");
        return false;
      } else {
        alert("Data berhasil dikirim!");
        return true;
      }
    }
  </script>
</body>
</html>
```

#### ```- penjelasan``` :

Validasi form digunakan untuk memastikan bahwa pengguna ```mengisi semua kolom penting sebelum mengirim data```.
Dalam script ini digunakan fungsi ```validasi()``` yang dijalankan saat tombol Kirim ditekan.
Fungsi tersebut memeriksa:

- Apakah kolom ```Nama``` sudah diisi.

- Apakah kolom ```Email``` sudah diisi.

Jika ada kolom yang kosong, sistem akan menampilkan pesan peringatan (```alert```) dan form tidak akan dikirim (return false).
Jika semua kolom terisi, maka muncul pesan bahwa data berhasil dikirim (```return true```).

#### ```- hasil```

![foto](https://github.com/azkaa-pixel/LAB5WEB/blob/d363050fba4450de5ddda64923971c9abb6fa8ad/praktikum%205/jawaban.png)



