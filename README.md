# PhishGuard

## Deskripsi

PhishGuard merupakan sistem yang dirancang untuk membantu mendeteksi pesan yang terindikasi sebagai phishing dengan memanfaatkan teknologi Machine Learning dan klasifikasi teks.

Sistem ini dikembangkan sebagai bagian dari proyek mata kuliah Rekayasa Perangkat Lunak (RPL).

## Tujuan Sistem

PhishGuard bertujuan untuk membantu pengguna dalam mengidentifikasi pesan yang memiliki indikasi phishing berdasarkan karakteristik dan pola tertentu pada pesan.

## Dokumentasi

Dokumentasi perancangan sistem yang tersedia dalam repository ini meliputi:

- Software Requirements Specification (SRS)
- Use Case Diagram
- Use Case Description
- Activity Diagram
- Sequence Diagram
- State Machine Diagram

## Software Requirements Specification
Dokumen yang berisi kebutuhan fungsional dan nonfungsional sistem PhishGuard. Dokumen SRS dapat dilihat melalui tautan berikut:

[📄 SRS - PhishGuard](SRS%20-%20Phishguard.pdf)


## Use Case Diagram
Diagram yang menggambarkan interaksi antara aktor User dan Admin dengan sistem PhishGuard.

![Use Case Diagram](Use%20Case%20Diagram%20Phishguard.jpg)

## Use Case Description
Use Case Description menjelaskan secara terperinci setiap use case pada sistem PhishGuard. Termasuk aktor yang terlibat, tujuan, prasyarat, alur utama, dan alur alternatif.

#### Use Case Description Registrasi
![Use Case Description](./Use%20Case%20Description%20Registrasi.jpg)

#### Use Case Description Login
![Use Case Description](./Use%20Case%20Description%20Login.jpg)

#### Use Case Description Input Pesan
![Use Case Description](./Use%20Case%20Description%20Input%20Pesan.jpg)

#### Use Case Description Melakukan Deteksi Pesan Phising
![Use Case Description](./Use%20Case%20Description%20Melakukan%20Deteksi%20Pesan%20Phising.jpg)

#### Use Case Description Melihat Hasil Deteksi
![Use Case Description](./Use%20Case%20Description%20Melihat%20Hasil%20Deteksi.jpg)

#### Use Case Description Melihat Riwayat Pemeriksaan
![Use Case Description](./Use%20Case%20Description%20Melihat%20Riwayat%20Pemeriksaan.jpg)

#### Use Case Description Mengelola Pengguna
![Use Case Description](./Use%20Case%20Description%20Mengelola%20Pengguna.jpg)

#### Use Case Description Mengelola Dataset
![Use Case Description](./Use%20Case%20Description%20Mengelola%20Dataset.jpg)

#### Use Case Description Melihat Data Deteksi
![Use Case Description](./Use%20Case%20Description%20Melihat%20Data%20Deteksi.jpg)

#### Use Case Description Melihat Statistik Deteksi
![Use Case Description](./Use%20Case%20Description%20Melihat%20Statistik%20Deteksi.jpg)

#### Use Case Description Logout
![Use Case Description](./Use%20Case%20Description%20Logout.jpg)

### Activity Diagram
Diagram yang menggambarkan alur aktivitas atau proses dalam sistem PhishGuard. Berikut dari Activity Diagramnya : 

#### Activity Diagram Registrasi

![Activity Diagram Login](Activity%20Diagram%20Regiter.jpg)

#### Activity Diagram Login

![Activity Diagram Login](Activity%20Diagram%20Login.jpg)

#### Activity Diagram Logout

![Activity Diagram Logout](Activity%20Diagram%20Logout.jpg)

#### Activity Diagram Input Pesan dan Melakukan Deteksi

![Activity Diagram Input Pesan dan Melakukan Deteksi](Activity%20Diagram%20Input%20Pesan%20dan%20Melakukan%20Deteksi.jpg)

#### Activity Diagram Melihat Riwayat dan Hapus Riwayat

![Activity Diagram Melihat Riwayat dan Hapus Riwayat](Activity%20Diagram%20Melihat%20Riwayat%20dan%20Hapus%20Riwayat.jpg)

#### Activity Diagram Melihat Data Deteksi

![Activity Diagram Melihat Data Deteksi](Activity%20Diagram%20Melihat%20Data%20Deteksi.jpg)

### Sequence Diagram
Diagram yang menggambarkan urutan interaksi dan pertukaran pesan antara aktor, antarmuka, sistem, dan database dalam menjalankan suatu proses. Berikut dari Sequence Diagramnya :

#### Sequence Diagram Register
![Sequence Diagram](./Sequence%20Diagram%20Register.jpg)
#### Sequence Diagram Login
![Sequence Diagram](./Sequence%20Diagram%20Login.jpg)
#### Sequence Diagram Input Pesan dan Deteksi Pesan
![Sequence Diagram](./Sequence%20Diagram%20Input%20Pesan%20dan%20Deteksi%20Pesan.jpg)
#### Sequence Diagram Melihat Riwayat dan Hapus Riwayat
![Sequence Diagram](./Sequence%20Diagram%20Melihat%20Riwayat%20dan%20Hapus%20Riwayat.jpg)
#### Sequence Diagram Melihat Data Deteksi
![Sequence Diagram](./Sequence%20Diagram%20Melihat%20Data%20Deteksi.jpg)
#### Sequence Diagram Mengelola Dataset
![Sequence Diagram](./Sequence%20Diagram%20Mengelola%20Dataset.jpg)
#### Sequence Diagram Melihat Statistik Deteksi
![Sequence Diagram](./Sequence%20Diagram%20Melihat%20Statistik%20Deteksi.jpg)
#### Sequence Diagram Mengelola Pengguna
![Sequence Diagram](./Sequence%20Diagram%20Mengelola%20Pengguna.jpg)
#### Sequence Diagram Logout
![Sequence Diagram](./Sequence%20Diagram%20Logout.jpg)


### State Machine Diagram
Diagram yang menggambarkan perubahan status (state) suatu objek atau proses selama sistem PhishGuard berjalan. Berikut dari State Machine Diagramnya :

#### State Machine Diagram Objek Pesan
![State Machine Diagram](./State%20Machine%20Diagram%20Objek%20Pesan.jpg)
#### State Machine Diagram Objek Sesi
![State Machine Diagram](./State%20Machine%20Diagram%20Objek%20Sesi.jpg)
#### State Machine Diagram Objek Data Dataset
![State Machine Diagram](./State%20Machine%20Diagram%20Objek%20Data%20Dataset.jpg)
#### State Machine Diagram Objek Versi Model AI
![State Machine Diagram](./State%20Machine%20Diagram%20Objek%20Versi%20Model%20AI.jpg)
#### State Machine Diagram Objek Akun Pengguna
![State Machine Diagram](./State%20Machine%20Diagram%20Objek%20Akun%20Pengguna.jpg)

### Class Diagram
Class Diagram menggambarkan struktur kelas dalam sistem PhishGuard, termasuk atribut, metode, dan hubungan antarkelas.

![Class Diagram](./Class%20Diagram.jpg)

### Object Diagram
Object Diagram menggambarkan contoh objek nyata dari kelas-kelas dalam sistem PhishGuard beserta nilai atribut dan hubungan antar objek pada suatu kondisi tertentu.

![Object Diagram](./Object%20Diagram.jpg)

### Deployment Diagram
Deployment Diagram menggambarkan arsitektur fisik sistem PhishGuard, termasuk perangkat pengguna, server aplikasi, komponen AI, dan database serta hubungan komunikasi di antaranya.

![Deployment Diagram](./Deployment%20Diagram.jpg)

## Teknologi

- Machine Learning
- Natural Language Processing (NLP)
- Web Application

## Status Proyek

**Tahap:** Perancangan dan dokumentasi sistem
