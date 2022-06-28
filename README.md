# integratif-IT0201-1202190039

## Tahapan 1 instalasi laravel

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

## Tahapan 2 
* Aktifkan XAMPP
![image](https://user-images.githubusercontent.com/93419670/176113162-dbf71676-3e82-4826-9d21-3d6e7bc31390.png)

* Ubah DB_DATABASE di .env sesuai dengan nama database yang dibuat di phpmyadmin
![image](https://user-images.githubusercontent.com/93419670/176113828-55fc29f7-1f82-403f-9a82-cf3c9a3b0e3f.png)

* Buat 2 table rss dan news dengan fitur migrations menggunakan perintah
![image](https://user-images.githubusercontent.com/93419670/176115278-c4e504c0-66ef-46a1-a86a-f7c14d701ed6.png)

* Tambahkan kolom name dan url pada tabel rss, seperti pada gambar dibawah
![image](https://user-images.githubusercontent.com/93419670/176115404-b339a77c-79bf-489e-ada3-ced7645afd10.png)

* Tambahkan kolom title, img_url, description, source_url, dan rss_id pada tabel news, seperti pada gambar dibawah
![image](https://user-images.githubusercontent.com/93419670/176144023-0ef5634a-72d3-4aa9-a8ab-36e0e478782e.png)

*
![image](https://user-images.githubusercontent.com/93419670/176116851-5299343b-003c-48f4-9bf6-db8df5ebc4c1.png)
![image](https://user-images.githubusercontent.com/93419670/176118107-e7d210ed-b7be-4b45-a0e8-40d3bb9be163.png)
![image](https://user-images.githubusercontent.com/93419670/176118740-867a4ca5-1069-4c82-872a-7ae49c98365f.png)
![image](https://user-images.githubusercontent.com/93419670/176119130-b2b93174-6048-41c9-b5bc-3f021a263c22.png)
![image](https://user-images.githubusercontent.com/93419670/176119473-ac02499e-c2cb-471d-99c6-2536c715bb09.png)
![image](https://user-images.githubusercontent.com/93419670/176123248-5175cdcc-e85f-417d-9a4f-0788bf19ce11.png)
![image](https://user-images.githubusercontent.com/93419670/176123439-e9d6d5a9-6b02-4d05-a549-2a152571298a.png)
![image](https://user-images.githubusercontent.com/93419670/176123777-7639be9d-f4a0-4ec1-9162-83184664dd87.png)

![image](https://user-images.githubusercontent.com/93419670/176123986-45ee2cf6-3251-458b-9084-513b41c5bd65.png)
![image](https://user-images.githubusercontent.com/93419670/176124853-d94b99d6-580a-434e-a966-f5465729f0ca.png)
![image](https://user-images.githubusercontent.com/93419670/176125188-6ea77d42-298d-4f98-8b08-2dd4f43947fa.png)

![image](https://user-images.githubusercontent.com/93419670/176138355-a237d543-eb7d-4372-837c-83063214f972.png)
![image](https://user-images.githubusercontent.com/93419670/176138446-02a11129-c24b-4724-a695-fac517db7ddb.png)
![image](https://user-images.githubusercontent.com/93419670/176139139-9299bf8e-aad9-437c-b1f3-0605ec6b04de.png)
![image](https://user-images.githubusercontent.com/93419670/176139215-559f85cd-2447-4817-b447-67660c826971.png)

* Cek localhost di http://127.0.0.1:8000/aggregrate/1 dan di database phpmyadmin
![image](https://user-images.githubusercontent.com/93419670/176139704-60a39be1-2167-4fa4-8d92-eb074bfc7e26.png)

![image](https://user-images.githubusercontent.com/93419670/176139792-599ba8e7-7973-4268-a6bf-2897411099df.png)

* Cek localhost di http://127.0.0.1:8000/aggregrate/2 dan di database phpmyadmin
![image](https://user-images.githubusercontent.com/93419670/176140784-68c2bcfb-8e86-446c-aa76-cb35732e2962.png)

![image](https://user-images.githubusercontent.com/93419670/176140901-306fce3f-9cec-4756-9bd2-3c805a1f289f.png)

* Cek localhost di http://127.0.0.1:8000/aggregrate/4 dan di database phpmyadmin
![image](https://user-images.githubusercontent.com/93419670/176141934-afaffd29-9eac-4b7b-af8f-539cb03a0fa5.png)

![image](https://user-images.githubusercontent.com/93419670/176142012-4923dff9-ce63-494e-b53c-a84bf0fc3ba8.png)
