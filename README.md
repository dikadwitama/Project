# Project

Berikut merupakan weather app sederhana menggunakan API dari openweather, menggunakan bootstrap angular dan menggunakan IDE visual studio code.

## Program Initialization

- Clone Code ke local directory
- update / install angular ke versi yang terbaru ( npm install -g @angular/cli)
    * notes : file node_modules tidak ada jika langung clone dari github
- masuk ke direktori tempat menyimpan file (cd ../..)
- Run 'ng serve -o' untuk mengenerate program                        

## Running Program

- Harus membuat akun email terlebih dahulu, jika sudah masukkan email dan        password
- User dapat mencari cuaca hari ini (current) dan cuaca selama 5 hari            (forecast) dengan mengetikkan nama kota di kolom search dan klik add city
- Kota yang berhasil dicari dan di add, akan tersimpan pada dashbord user
- Jika ingin mengetahui detail cuaca, silahkan klik kota yang dipilih, akan      otomatis menampilkan current weather dan forecast weather

## Error Solution

- Jika user belum migrasi dari angular 2 maupun belum pernah update angular      yang terbaru dalam kurun waktu setahun, akan ada beberapa error seperti        salah satu contohnya adalah adanya peringatan error : (cannot find module      '@angular/http') yang diakibatkan cli angular terbaru memiliki syntax yang     berbeda. Sehingga harus dilakukan perubahannya dari  
    syntax: import {Http} from '@angular/http';
    Menjadi
    syntax: import {HttpClientModule} from '@angular/common/http'; 

## Further Information

- Menggunakan API dari OpenWeather ('https://openweathermap.org/api') karena     link yang diberikan tidak dapat dibuka dan akhirnya terpilihlah API ini        karena selain banyak fitur gratis yang didapatkan dan adanya fitur forecast    secara gratis.

  Best Regards,
    Andhika Dwitama Putra"# Project" 
