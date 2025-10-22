# LAB5WEB

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

![foto]()

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

![foto]()
![foto]()
![foto]()

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

![foto]()
![foto]()

### 4. Membuat Fungsi dengan Parameter

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

![foto]()
![foto]()

### 5. 
```html
```
#### ```- penjelasan``` :
#### ```- hasil```
![foto]()
### 6. 
```html
```
#### ```- penjelasan``` :
#### ```- hasil```
![foto]()
### 7. 
```html
```
#### ```- penjelasan``` :
#### ```- hasil```
![foto]()
### 8. 
```html
```
#### ```- penjelasan``` :
#### ```- hasil```
![foto]()







