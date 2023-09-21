# Jarkom-Modul-1-D05-2023


# Soal 1

### User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.

### a.Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? 
### b.Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? 
### 3.Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
### 4.Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

## Langkah-Langkah
### 1. Mencari koneksi dengan kata kunci zip dengan menggunakan ftp contains "zip"
![First](img/1.png)

### 2. Akan ada hasil seperti ini
![First](img/2.png)

### 3. Lihat dengan detail pada bagian ini 

#### Bagian pertama
![First](img/4.png)

#### Bagian pertama
![First](img/3.png)

### 4. Hasilnya adalah seperti ini 
### a. 258040667
### b. 1044861039
### c. 1044861039
### d. 258040696

<br>

# Soal 2

### Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!

## Langkah-Langkah
### 1. Mencari koneksi dengan kata kunci ip.dst == 10.21.78.111 untuk mencari tujuan koneksi ip dan klik pada port 1089
![First](img/5.png)

### 2. Lalu buka menu follow dan tcp stream
![First](img/6.png)

### 3. Akan ada hasil output seperti ini

#### Keseluruhan
![First](img/7.png)

#### Nama Server
![First](img/8.png)

### Hasilnya adalah gunicorn

<br>

# Soal 3

### Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:

### a.Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?
### b.Protokol layer transport apa yang digunakan?

<br>

## Langkah-Langkah
### 1. Mencari koneksi dengan kata kunci (ip.src == 239.255.255.250 or ip.dst == 239.255.255.250) && udp.port == 3702 untuk menfilter ip source dengan port 3702

![First](img/9.png)

### 2. Lalu akan ada hasil output seperti ini
![First](img/10.png)

### 3. Hitung total ip yang tertera disini

#### Jumlah Ip = 21
![First](img/11.png)

#### Protokol layer yang digunakan adalah UDP
![First](img/12.png)

# Soal 4

### Berapa nilai checksum yang didapat dari header pada paket nomor 130?

## Langkah-Langkah
### 1. Ini adalah tampilan muka soal no 4

![First](img/13.png)

### 2. Lalu cari nomor urutan ke 130
![First](img/14.png)

### 3. Cek User Data Protocol

![First](img/15.png)

### 4. Hasil nilai checksum yang didapat adalah 0x18e5
![First](img/16.png)


## Soal 5 

### Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.


### a.Berapa banyak packet yang berhasil di capture dari file pcap tersebut?
### b.Port berapakah pada server yang digunakan untuk service SMTP? 
### c.Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?

## Langkah-Langkah
### 1. Dikarenakan kita tidak memiliki nc (soal), maka kita harus mendownload folder dan memecahkan kata sandinya
![First](img/17.png)

### 2. Akan ada hasil seperti ini
![First](img/18.png)

### 3. Untuk itu, kita harus mencari kata sandi yang tersembunyi di dalam wireshark

#### Bagian pertama
![First](img/4.png)
<!-- 
#### Bagian pertama
![First](img/3.jpg) -->

<!-- ### 4. Hasilnya adalah seperti ini 
### a. 258040667
### b. 1044861039
### c. 1044861039
### d. 258040696 -->