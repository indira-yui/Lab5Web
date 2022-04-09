# Lab5Web

|   INDIRA ALINE        |       312010042           |
| --------------------- | --------------------------|
| TI.20.A.1             |      PEMROGRAMAN WEB      |
| PERTEMUAN KE-6        |       PRAKTIKUM 5         |

Dipertemuan kali ini akan mempelajari **javascript** pada html, seperti penempatan **javascript** pada html di internal atau pun eksternal 

**JavaScript**

## 1). PERSIAPAN MEMBUAT DOKUMEN HTML DENGAN NAMA FILE **lab5_javascript.html** seperti berikut.

## CODE & OUTPUT
![javascript_dasar](img/create_docu_html.png)

**PENJELASAN**
Ini adalah hasil dari output dengan menggunakan element javascript **documen.write** dan **console.log** namun untuk **console.log** tidak ditampilkan dibrowser,ada fitur khusus untuk menampilkan nya seperti gambar dibawah.

![console.log](img/fitur.png)
ini adalah output console.log seperti terlihat kanan bawah,terdapat fitur console dan didalam nya ada script hello world.

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
Pemakaian **alert** sebagai property window dan akan muncul di atas halaman dengan contoh gambar seperti di atas.

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
Menggunakan ***Method*** dalam **objek** dengan javascript, seperti contoh gambar di atas.

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
Operasi Dasar Artimatika dalam ***javascript*** seperti contoh gambar di atas.

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

