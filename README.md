# integratif-IT0201-1202190039

## Tahapan instalasi laravel

* Download file composer
![image](https://user-images.githubusercontent.com/93419670/173064961-ab05677b-91ca-459d-a77c-a538cedf5961.png)

* Masuk Command Prompt
  - masuk command promt, ketik cmd dan klik OK
![image](https://user-images.githubusercontent.com/93419670/173065883-7806e5a5-a5a1-41b3-90fa-aae73c73407c.png)

* masuk folder XAMPP
  - arahkan command prompt menuju direktori file server, lokasi xampp/htdocs
```
cd \xampp\htdocs
```
* Mulai proses install laravel
  - buat request untuk menginstall file laravel 
```
composer create-project --prefer-dist laravel/laravel rachmad1202190039
```
![image](https://user-images.githubusercontent.com/93419670/173065268-0243a461-e799-4245-8c0e-5b7d4461006c.png)

* Cek instalasi laravel di web browser
  - setelah proses download laravel selesai, akan ada folder baru pada direktori file server dengan nama project yang telah dibuat tadi
![image](https://user-images.githubusercontent.com/93419670/173065449-f3d92187-6e9e-45c8-96e5-8776c8fab835.png)
  - untuk memastikan laravel sukses terinstall, arahkan command prompt menuju direktori project dan lakukan perintah berikut
```
cd rachmad1202190039
```
```
php artisan serve
```
![image](https://user-images.githubusercontent.com/93419670/173065668-4ad2e50a-468c-4387-923b-9997aaaa4ca3.png)

  - jika muncul tulisan diatas, maka selanjutnya membuka link yang telah disediakan laravel
![image](https://user-images.githubusercontent.com/93419670/173065041-4c04db53-3b72-42ae-90ea-4d6a2ef9704d.png)
