# Jarkom-Modul-1-D11-2023

Anggota kelompok D11 adalah :

|        Nama           | NRP|
| ---                   |--- |
|Gracetriana Survinta Septinaputri | 5025211199 |
|Muhammad Rifqi Fadhilah           | 5025211228 |


# Laporan Resmi Praktikum Modul 1 Jarkom

## Soal Nomor 1
User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.

### Langkah-langkah
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
Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.

### Langkah-langkah
- Mencari password untuk membuka connect.txt dengan memilih salah satu packet SMTP dan klik Follow TCP Stream

- Ditemukan password pada TCP Stream yaitu NWltcGxlUGFzNXdvcmQ= yang harus didecode dengan Base64

- Setelah didecode, didapatkan passwordnya `5implePas5word`

![Soal5_1](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/c1c53780-dc0f-4852-ac87-318ae4fa3fd2)

a) Berapa banyak packet yang berhasil di capture dari file pcap tersebut? `60`

b) Port berapakah pada server yang digunakan untuk service SMTP? `25`

c) Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP? `74.53.140.153`

![Soal5_2](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/ae50dbb2-9941-45ec-84ed-842df57ae554)

### Bukti Flag
![Soal5_Flag](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/b40a3cce-f020-4094-b69b-db3a315975db)


## Soal Nomor 6

## Soal Nomor 7
Berapa jumlah packet yang menuju IP 184.87.193.88?

### Langkah-langkah
- Menggunakan query filter `ip.dst == 184.87.193.88` dan jumlahkan berdasarkan hasil filter totalnya ada 6
  
![Soal7](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/73384683-e24e-4b1d-bd6e-3b6e832b6358)

### Bukti Flag
![Soal7_Flag](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/c480aa01-0aa3-470c-929a-48abc6d6feec)


## Soal Nomor 8
Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)

### Langkah-langkah
- Filter dengan kueri `tcp.dstport == 80 || udp.dstport == 80`

  ![Soal8](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/0cb38534-26d1-48e6-859c-01f095dc334d)

### Bukti Flag
![Soal8_Flag](https://github.com/gracetrianaa/Jarkom-Modul-1-D11-2023/assets/90684914/b25af75e-091e-4c15-9720-1d2f5ccd4f71)

  
## Soal Nomor 9

## Soal Nomor 10

