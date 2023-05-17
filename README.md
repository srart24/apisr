# apisr
<br>
  
![apisr](img/apisr.png)

---------


<br>

apisr adalah sebuah modul yang menyediakan antarmuka untuk mengakses API dari :

[Api srart24](https://api-srart24.my.id)

Modul ini memudahkan pengguna untuk berinteraksi dengan berbagai fitur yang disediakan oleh Api [Api srart24](https://api-srart24.my.id)

--------

## Daftar Isi
- [Instalasi](#instalasi)
- [Penggunaan](#penggunaan)
- [Kontribusi](#kontribusi)
- [Lisensi](#lisensi)

--------

<br>

## Mendapatkan API Key

Untuk mendapatkan API Key,
[Di Sini](https://api-srart24.my.id) 
dan daftar untuk membuat akun. Setelah berhasil mendaftar, Anda akan diberikan API Key yang dapat digunakan untuk menggunakan modul ini.

--------

<br>

## instalasi

``` bash
$ npm install apisr
```


``` bash
$ yarn add apisr
```

#### memanggil
``` js
const apisr = require('apisr');
const test = new apisr('your-api-key');
```

``` javascript
import apisr from 'apisr'
const test = new apisr('your-api-key');
```

--------

<br>

## Penggunaan


``` js
test.gfx.logo1('My Logo')
  .then(buffer => {
    // Lakukan sesuatu dengan buffer logo
  })
  .catch(error => {
    // Tangani kesalahan yang terjadi
    console.error('Terjadi kesalahan:', error);
  });
 

  test.textpro.glitch(nama)
   .then(buffer => {
    // Lakukan sesuatu dengan buffer logo
  })
  .catch(error => {
    // Tangani kesalahan yang terjadi
    console.error('Terjadi kesalahan:', error);
  });


  test.sertifikat.tolol(nama)
   .then(buffer => {
    // Lakukan sesuatu dengan buffer logo
  })
  .catch(error => {
    // Tangani kesalahan yang terjadi
    console.error('Terjadi kesalahan:', error);
  });

```

<br>

## Kontribusi
Kontribusi selalu diterima! Jika Anda ingin berkontribusi ke proyek ini, silakan buat *pull request* dan kami akan mempelajarinya.

--------

<br>

## Lisensi
- lihat [LICENSE](LICENSE) untuk detail lebih lanjut.

--------

<br>

## Ketergantungan
[Api srart24](https://api-srart24.my.id)

------


<br><br>
### Author
---------
| [![Saya](https://github.com/srart24.png?size=50)](https://github.com/srart24) |
|------|
| srart24 |
---------
