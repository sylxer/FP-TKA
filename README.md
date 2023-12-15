# FP-TKA

## I. Introduction
Pada final project TKA ini, diminta untuk merancang arsitektur cloud untuk deploy aplikasi. Diberikan pilihan lingkungan cloud yakni menggunakan Digital Ocean, Microsoft Azure, dan Local Virtual Machine dan kami memutuskan untuk menggunakan Microsoft Azure. Setelah itu, diminta untuk mendeploy aplikasi dan mengetes load balancing menggunakan locust.

## II. Rancangan Arsitektur Komputasi Awan dan Spesifikasi
- Rancangan arsitektur
![alt text](img/rancangan_arsitektur.png)


- Tabel spesifikasi
![alt text](img/tabel_spesifikasi.png)

## III. Langkah-langkah Implementasi dan Konfigurasi
1. Membuat Database dan connection string
 
![alt text](img/img/1.jpg)
![alt text](img/img/2.jpg)
![alt text](img/img/3.jpg)
![alt text](img/img/4.jpg)

2. Create ‘New Connection’ dengan string database yang sudah ada sebelumnya, dan buat database sesuai dengan variabel yang sudah dibuat di dalam app.py

![alt text](img/img/5.jpg)
![alt text](img/img/6.jpg)

## IV. Hasil Pengujian Endpoint setiap API
- 1. Get All Orders
![IV.1](img/IV.1.png)

- 2. Get a Specific Order by ID
![IV.2](img/IV.2.png)

- 3. Create a New Order
![IV.3](img/IV.3.png)

- 4. Update an Order by ID
![IV.4](img/IV.4.png)

- 5. Delete an Order by ID
![IV.5](img/IV.5.png)


## V. Hasil Pengujian dan Analisis Loadtesting Menggunakan Locust
- 1. Jumlah Request per seconds (RPS)
![V.1](img/IV.1.png)

- 2. Jumlah peak concurrency maksimum yang dapat ditangani oleh server dengan spawn rate 25 dan durasi waktu load testing 60 detik
![V.2](img/IV.2.png)

- 3. Jumlah peak concurrency maksimum yang dapat ditangani oleh server dengan spawn rate 50 dan durasi waktu load testing 60 detik
![V.3](img/IV.3.png)

- 4. Jumlah peak concurrency maksimum yang dapat ditangani oleh server dengan spawn rate 100 dan durasi waktu load testing 60 detik
![V.4](img/IV.4.png)

## VI. Kesimpulan dan saran.
