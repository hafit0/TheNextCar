# The Next Car Project
project untuk belajar implementasi MVC

## Features
- Users dapat mengklik button
- ketika pintu terbuka tidak bisa menyalakan


## Jawaban Tugas
### 1. Class Diagram 
![Class diagram](https://github.com/hafit0/TheNextCar/blob/master/ClassDiagram1.png)
### 2. Kegunaan `DoorController.cs`
Berisi method yang digunakan untuk menghandle pintu meliputi membuka pintu, menutup pintu, mengunci, membuka kunci dan memberikan keterangan ketika pintu itu dibuka,ditutup dan dikunci.
### 3. Kegunaan Model `Door.cs`
mengatur logic bolean dan mengembalikan nilai true/false sesuai dengan fungsi `isClose()` atau `isLocked()`.
### 4. Kegunaan Interface `OnDoorChanged()`
untuk menampung method `doorSecurityChanged` dan `doorStatusChanged` yang memiliki nilai string value dan message 