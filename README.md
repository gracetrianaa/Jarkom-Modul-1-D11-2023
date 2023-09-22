# Jarkom-Modul-1-D11-2023

Anggota kelompok D11 adalah :

|        Nama           | NRP|
| ---                   |--- |
|Gracetriana Survinta Septinaputri | 5025211199 |
|Muhammad Rifqi Fadhilah           | 5025211228 |


# Laporan Resmi Praktikum Modul 1 Jarkom

## Soal Nomor 1
User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.

### Langkah-langkah:
- Filter untuk protokol FTP pada Wireshark

- Mencari packets yang melakukan aktivitas unggahan (STOR dan Opening Binary) dari file c75-GrabThePhisher.zip

a) Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? `258040667`

b) Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? `1044861039`

![Soal1_1](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/6a046a0c-6309-4bff-b53c-b720b949ce9c)

c) Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut? `1044861039`

d) Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut? `258040696`

![Soal1_2](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/ef09000c-ca55-4640-b1ad-6db6749c4516)

### Bukti Flag
![Soal1_Flag](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/b3df8ff5-208c-4f04-af95-bf4bbdaf72a5)

## Soal Nomor 2

## Soal Nomor 3
Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:

### Langkah-langkah
#### Cara 1
- Melihat melalui Statistics -> Endpoints
  
- Pada protocol UDP terlihat ada 21 packets yang tercapture dengan IP destination 239.255.255.250 dan port 3702
#### Cara 2
- Filter dengan kueri `udp.port == 3702 && ip.dst == 239.255.255.250` dan hitung secara manual ada berapa packets

a) Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702? `21`

b) Protokol layer transport apa yang digunakan? `UDP`

![Soal3](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/7eab3429-0105-464c-a7eb-9e7401993a66)

### Bukti Flag
![Soal3_Flag](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/8ceb7c22-410e-45b0-823b-41c0443038ff)


## Soal Nomor 4

## Soal Nomor 5

## Soal Nomor 6

## Soal Nomor 7

## Soal Nomor 8

## Soal Nomor 9

## Soal Nomor 10

