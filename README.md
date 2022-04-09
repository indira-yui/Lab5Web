# Lab5Web

|   INDIRA ALINE        |       312010042           |
| --------------------- | --------------------------|
| TI.20.A.1             |      PEMROGRAMAN WEB      |
| PERTEMUAN KE-6        |       PRAKTIKUM 5         |

Dipertemuan kali ini akan mempelajari **javascript** pada html, seperti penempatan **javascript** pada html di internal atau pun eksternal **JavaScript**

## 1). PERSIAPAN MEMBUAT DOKUMEN HTML DENGAN NAMA FILE **lab5_javascript.html** seperti berikut.

## CODE & OUTPUT
![javascript_dasar](img/create_docu_html.png)

**PENJELASAN**

Ini adalah hasil dari output dengan menggunakan element javascript **documen.write** dan **console.log** namun untuk **console.log** tidak ditampilkan dibrowser, ada fitur khusus untuk menampilkan nya seperti gambar dibawah.

![console.log](img/fitur.png)
ini adalah output console.log seperti terlihat kanan bawah, terdapat fitur console dan didalam nya ada script hello world

**code html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mengenal Javascript</title>
</head>
<body>
    <h1>Pengenalan Javascript</h1>
    <h3>Contoh documen.write dan console.log</h3>
    <script>
        document.write("Hello World");
        console.log("Hello World");
    </script>
</body>
</html>
```

# JAVASCRIPT DASAR

## 2).PEMAKAIAN ALERT SEBAGAI PROPERTY WINDOW

## CODE DAN OUTPUT
![alert](img/alertwindow.png)

**PENJELASAN**

Pemakaian **alert** sebagai property window dan akan muncul di atas halaman dengan contoh gambar seperti di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>alert box</title>
</head>
<body>
    <script lang="javascript">
        window.alert("ini merupakan pesan untuk anda");
    </script>
</body>
</html>
```

## 3). PEMAKAIAN METHOD DALAM OBJEK

## CODE DAN OUTPUT
![method_objek](img/method_objek.png)

**PENJELASAN**

Menggunakan ***Method*** dalam **objek** dengan javascript, seperti contoh gambar di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>skrip javascript</title>
</head>
<body>
    percobaan memakai javascript:<br>
    <script lang="javascript">
        document.write("Selamat mencoba javascript<br>");
        document.write("Semoga sukses!");
    </script>
</body>
</html>
```

## 4). PEMAKAIAN PROMPT

## CODE DAN OUTPUT
![prompt](img/prompt.png)

**PENJELASAN**

Menggunakan **Prompt** pada script seperti gambar di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pemasukan data</title>
</head>
<body>
    <script lang="javascript">
        var nama = prompt("siapa nama anda?","masukkan nama anda");
        document.write("hai, "+ nama);
    </script>
</body>
</html>
```

## 5).PEMBUATAN FUNGSI DAN CARA PEMANGGILANNYA

## CODE DAN OUTPUT
![function](img/onload.png)

**PENJELASAN**

Menggunakan Function dengan body onload di javascript seperti gambar di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program javascript</title>
    <script lang="javascript">
        function pesan(){
            alert ("Memanggil javascript lewat body onload")
        }
    </script>
</head>
<body onload=pesan()>
    
</body>
</html>
```

# DASAR PEMROGRAMAN DI JAVASCRIPT

## 6). OPERASI DASAR ARITMATIKA

## CODE DAN OUTPUT
![aritmatika](img/aritmatika.png)

**PENJELASAN**

Operasi Dasar Artimatika dalam ***javascript*** seperti contoh gambar di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function test (val1,val2)
        {
            document.write("<br>"+"perkalian : val1*val2 "+"<br>")
            document.write(val1*val2)
            document.write("<br>"+"pembagian : val1/val2 "+"<br>")
            document.write(val1/val2)
            document.write("<br>"+"penjumlahan : val1+val2 "+"<br>")
            document.write(val1+val2)
            document.write("<br>"+"pengurangan : val1-val2 "+"<br>")
            document.write(val1-val2)
            document.write("<br>"+"modulus : val1%val2 "+"<br>")
            document.write(val1%val2)
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="arithmetic" onclick=test(9,4)>
</body>
</html>
```

## 7). SELEKSI KONDISI (IF/ELSE)

## CODE DAN OUTPUT
![if_else](img/ifelse.png)

**PENJELASAN**

Ini adalah program seleksi kondisi dari **if else** disitu **if** nya jika nilai lebih sama dengan 60 berarti lulus dan **else** nya jika 
dibawah 60 berati tidak lulus, sementara saya memberi nilai 80 yang berarti hasil nya adalah lulus

![hasil](img/ifelse_hasil.png)
ini adalah contoh output dari seleksi kondisi **if else** seperti contoh gambar diatas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh if-else</title>
</head>
<body>
    <script lang="javascript">
        var nilai = prompt("nilai (0-100): ", 0);
        var hasil = "";
        if (nilai >=60)
        hasil = "lulus";
        else
        hasil = "tidak lulus";
        document.write("hasil: " + hasil);
    </script>
</body>
</html>
```

## 8). PENGGUNAAN OPERATOR SWITCH UNTUK SELEKSI KONDISI

## CODE DAN OUTPUT
![switch_operator](img/switch.png)

**PENJELASAN**

Penggunaan operator switch untuk seleksi kondisi, disini saya menulis program **switch case** sebagai seleksi kondisi dengan memasukan 
angka 6 sebagai seleksi nya kemudian output nya akan keluar argument **bilangan lainnya**

![hasil_switch](img/hasil_switch.png)
gambar di atas adalah hasil output dari pemilihan **switch dengan case 6** hasil seperti contoh gambar di atas

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contoh Program Javascript</title>
    <script lang="javascript">
        function test ()
        {
            val1=window.prompt("input nilai (1-5):")
            switch (val1)
            {
                case "1" :
                    document.write("bilangan satu")
                    break
                case "2" :
                    document.write("bilangan dua")
                    break
                case "3" :
                    document.write("bilangan tiga")
                    break
                case "4" :
                    document.write("bilangan empat")
                    break
                case "5" :
                    document.write("bilangan lima")
                    break 
                default  :
                    document.write("bilangan lainnya")
            }
        }
    </script>
</head>
<body>
    <input type="button" name="button1" value="switch" onclick=test()>
</body>
</html>
```

# PEMBUATAN FORM

## 9). FORM INPUT
## CODE DAN OUPUT
![form_input](img/form.png)

**PENJELASAN**

Membuat **form input** dengan ***function javascript*** dan pengondisian **if/else** seperti gambar di atas saya memilih angka 6 maka akan menjadi **bilangan genap** .

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Form input</title>
    <script lang="javascript">
        function test () {
            var val1=document.kirim.T1.value
            if (val1%2==0)
                document.kirim.T2.value="bilangan genap"
            else
                document.kirim.T2.value="bilangan ganjil"
        }
    </script>
</head>
<body>
    <form action="" method="post" name="kirim">
        <p>BIL <input type="text" name="T1" id="T1" size="20"> MERUPAKAN BIL <input type="text" name="T2" id="T2" size="20"></p>
        <p><input type="button" value="TEBAK" name="B1" onclick=test()></p>
    </form>
</body>
</html>
```

## 10). FORM BUTTON
## CODE DAN OUTPUT
![form_button](img/formbutton.png)

**PENJELASAN**

Disini menggunakan **form button** dengan **function javascript** dan **html form button** hasil nya adalah seperti contoh gambar di atas, saya memilih warna hijau dan teks kuning.

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Objek Document</title>
</head>
<body>
    <script lang="javascript">
        function ubahWarnaLB(warna) {
            document.bgColor = warna;
        }
        function ubahWarnaLD(warna) {
            document.fgColor = warna;
        }
    </script>
    <h1>Tes</h1>
    <form action="">
        <input type="button" value="Latar Belakang Hijau" onclick="ubahWarnaLB('GREEN')">
        <input type="button" value="Latar Belakang Putih" onclick="ubahWarnaLB('WHITE')">
        <input type="button" value="Teks Kuning" onclick="ubahWarnaLD('YELLOW')">
        <input type="button" value="Teks Biru" onclick="ubahWarnaLD('BLUE')">
    </form>
    <script lang="javascript">
        document.write("Dimodifikasi terakhir pada " + document.lastModified);
    </script>
</body>
</html>
```

# HTML DOM

## 11). PILIHAN MENGGUNAKAN CHECKBOX DENGAN PERHITUNGAN OTOMATIS

## CODE DAN OUTPUT
![html_dom_checkbox](img/html_dom.png)

**PENJELASAN**

Disini menggunakan **HTML DOM** dengan **input type checkbox** sebagai contoh gambar di atas menghitung secara otomatis

**code html dan script**
```html
<!DOCTYPE html>
<!-- file daftar menu.html -->
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daftar Menu</title>
    <script lang="javascript">
        function hitung(ele) {
            var total = document.getElementById('total').value;
                total = (total ? parseInt(total) : 0);
            var harga = 0;
            if (ele.checked) {
                harga = ele.value;
                total += parseInt(harga);
            } else {
                harga = ele.value;
                if (total > 0)
                    total -= parseInt(harga);
            }
            document.getElementById('total').value = total;
        }
    </script>
</head>
<body>
    <h1>Daftar Menu Makanan</h1>
    <label><input type="checkbox" value="5000" name="menu1" id="menu1" onclick="hitung(this);">Ayam Goreng Rp. 5.000</label><br>
    <label><input type="checkbox" value="500" name="menu2" id="menu2" onclick="hitung(this);">Tempe Goreng Rp. 500</label><br>
    <label><input type="checkbox" value="2500" name="menu3" id="menu3" onclick="hitung(this);">Telur Dadar Rp. 2.500</label><hr>
    <strong>Total Bayar: Rp. <input type="text" name="total" id="total"></strong>
</body>
</html>
```

# PERTANYAAN DAN TUGAS

## 1). BUAT SCRIPT UNTUK MELAKUKAN VALIDASI PADA ISIAN FORM.
## CONTOH CODE DAN OUTPUT
![validasi_form](img/tugas1.png)

**PENJELASAN**

Ini adalah contoh membuat **form validasi** dengan menggunakan **script** atau ***javascript*** terdapat beberapa pengondisian, jika data tidak di isi dengan lengkap maka akan terdapat **prompt** ***isi alamat anda dengan lengkap*** karena harus mengisi dengan lengkap seperti contoh gambar di atas

![validasi_data](img/tugas2.png)
Sementara contoh gambar diatas adalah ketika data tidak di isi dengan lengkap, maka akan ada **prompt** isi alamat anda dengan lengkap, tidak akan bisa disubmit karena data belum lengkap

**code html dan script**
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Form Validasi</title>
    <link rel="stylesheet" type="text/css" href="style.css">
    <script type="text/javascript">
        function validasiForm() {
            var nama = document.getElementById("nama").value;
            var email = document.getElementById("email").value;
            var alamat = document.getElementById("alamat").value;
            if (nama != "" && email != "" && alamat != "") {
                return true;
            } else {
                alert('Isi Alamat Anda dengan lengkap !');
                return false;
            }
        }
    </script>
</head>
<body>
     <div class="login">
        <h2>VALIDASI DATA ANDA</h2>
        <form action="#" method="POST" onSubmit="return validasiForm()">
            <div>
                <label>Nama Lengkap:</label>
                <input type="text" name="nama" id="nama" />
            </div>
            <div>
                <label>Email:</label>
                <input type="email" name="email" id="email" />
            </div>
            <div>
                <label>Alamat:</label>
                <textarea cols="40" rows="5" name="alamat" id="alamat"></textarea>
            </div>
            <div>
                <input type="submit" value="Daftar" class="tombol">
            </div>
        </form>
    </div>
</body>
</html>
```
```css
body {
    background: #4cc9f0;
    font-family: sans-serif;
    padding: 100px;
  }
  
  h2{
      text-align: center;
      font-size: 35px;
      color: #555;
  }
  .login {
    padding: 1em;
    margin: 2em auto;
    width: 30em;
    background: #fff;
    border-radius: 3px;
  }
  
  label {
    font-size: 10pt;
    color: #555;
  } 
  
  input[type="text"],
  input[type="email"],
  textarea {
    padding: 8px;
    width: 95%;
    background: #efefef;
    border: 0;
    font-size: 10pt;
    margin: 6px 0px; 
  }
   
  .tombol {
    background: #3498db;
    color: #fff;
    border: 0;
    padding: 5px 8px;
  } 
   .tombol:hover{
      background-color: #555;
  }
```
## TERIMAKASIH
### @INDIRA_ALINE