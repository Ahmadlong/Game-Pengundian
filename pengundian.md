## 1.1 Latar Belakang

Banyaknya orang berdebat tentang hal yg kecil

## 1.2. Deksripsi Teknologi Informasi

Game ini mmengguanakan bahasa java

Menggunakan javaFx ini di gunakan untuk pengembangan game juga dan untuk membuat tatap muka antar pengguna

Mengguanakan JDBC((Java Database Connectivity)ini untuk menyimpan dan mengambil data

Di dalam game ini saya juaga menggunakan class java util ini di gunakan untuk angka-angka di dalam game

Dalam pengembangan game yg 2 dimensi saya menggunakan LibGDX

Pembuatan menggunakan laptop

## 1.3. Branding
.Merk:Game Pengundian

.Tagline:aman,terpercaya,dan sangat membantu

.Campaign:permaslahn dapat di selaisaikan dengan bijak,aman,dan simpel

.Target usia:

siswa dan siswi

mahasiswa

masyarakat

pemerintahan

bahkan presiden

.user experience theme:

mudah

sederhana

asik

inspirasi desain

![image](https://github.com/Ahmadlong/Game-Pengundian/assets/148826264/4dab42a0-09bc-44e3-a242-451fcc7fdb68)

![image](https://github.com/Ahmadlong/Game-Pengundian/assets/148826264/33f3a2f0-2a48-46a6-af88-1501780ea6da)


## 2. User Story

Sebagai | Saya ingin bisa | Sehingga | Prioritas
---|---|---|---
Admin| menyediakan kupon sebanyaknya | pesertanya lebih banyak | ⭐⭐⭐⭐⭐
Admin|membuat aturan|gamenya lancar|⭐⭐⭐⭐⭐
admin|menyedikan hadiah yg menarik|pemenang bisa senang|⭐⭐⭐⭐
admin|memberikan tata tertib dahulu|peserta tidak kebingungan|⭐⭐⭐⭐⭐
peserta|membeli kupon|sehingga saya bisa main game ini|⭐⭐⭐⭐⭐
peserta|mengajak orang main juga|admin memberikan plus ke peserta|⭐⭐⭐
Peserta|memasukkan uang ke admin|bisa bermain tanpa ada iklan|⭐⭐⭐⭐
Admin|mengajak peserta melihat pemenang|pemenangnya terhibur|⭐⭐⭐
Admin|membuat kolom saran|peserta dapat menulis kritikan|⭐⭐⭐⭐
peserta|mengajukan permasalahan|admin dan peserta lain dapat menyelesaikannya|⭐⭐⭐⭐⭐
Admin|membuat daftar riwayat|peserta dapat melihat daftar pengundian yg telah iya ikuti|⭐⭐⭐⭐
Peserta|mengakses daftar pemenang undian sebelumnya|Saya dapat melihat sejarah pemenang dan hadiah yang telah diberikan|⭐⭐⭐⭐⭐
Peasrta|Memberikan ulasan dan umpan balik tentang undian| Pengembang game dapat meningkatkan pengalaman pengundian untuk masa depan|⭐⭐⭐
Peserta|Dapat berbagi hasil undian di media sosial|Saya dapat memperlihatkan kepada teman-teman saya bahwa saya telah memenangkan hadiah|⭐⭐⭐⭐⭐

## 3. Struktur Data

Cara membuat aneka macam bentuk grafik menggunakan mermaid.js bisa lihat di [https://mermaid.js.org/syntax/entityRelationshipDiagram.html](https://mermaid.js.org/syntax/entityRelationshipDiagram.html) 


```mermaid
erDiagram
    Undian ||--o{ Pengundian : Peserta
    Pengundian ||--|{ Hadiah : Pemenang
```


## 4. Arsitektur Sistem

```mermaid
flowchart TD
  subgraph cloud

  a(Database: MySQL)-->b(Backend: java)-->c(Webserver: Javascript.ExpressJ)
  end

  subgraph client
  id1(Android and IOS app: Dart.Flutter)
  end

  cloud-->client

```

## 5. Teknologi, Library, dan Framework
Teknologi

menggunakan bahasa java

Menggunakan javaFx 

menggunakan java util

menggunakan laptop


Library(Kumpulan kode yang telah di tulis sebelumnya dan yang dapat di gunakan oleh oranng lain)

java swing

java awt

java.awt.event.ActionEvent

java.awt.event.ActionListener

java.util.Random

Framework (struktur kerja yang menyediakan landasan konseptual dan teknologis untuk memudahkan pengembangan perangkat lunak)

libGDX

Slick2D

javaFX

## 6. Desain User Experience dan User Interface

![WhatsApp Image 2023-11-06 at 05 41 41_82df1902](https://github.com/Ahmadlong/Game-Pengundian/assets/148826264/031204d7-6cac-4703-89cf-4b2dfb93905a)

## 7. Demonstrasi Video

Link youtube nya

## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasimu ?

https://youtube.com/@AhmadRidwan-vw8oc?si=6C9_UXs-9RiOYS6b

## 9. Bagaimana algoritma, struktur data, dan bahasa pemrograman berperan dalam produk teknologi informasimu ?

https://youtu.be/bfHJwbBXCqk?si=1sx1BizqVfsvoqCK

## 10. Bagaimana metode pengembangan perangkat lunak / Software Development Life Cycle berperan dalam produk teknologi informasimu ?

Link youtube nya di detik jawaban ini

## 11. Bagaimana database / sistem basis data berperan dalam produk teknologi informasimu ?

https://youtu.be/xYUAbUrNDc4?si=RcgAIMNJl8asXl-t

