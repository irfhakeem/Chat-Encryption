# Chat-Encryption

| Nama                  | NRP        | Task                                                                                                                                        |
| --------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------- |
| Muhammad Irfan Hakim  | 5025221291 | - Mengubah Algoritma DES tugas sebelumnya agar bisa menangani input lebih dari 8 char <br> - Implementasi enkripsi dan dekripsi pada client |
| Muhammad Nabil Fadhil | 5025221200 | - Implementasi server dan client                                                                                                            |

## Penjelasan DES

Untuk membuat DES bisa menangani input character lebih dari 8, kami menggunakan pendekatan dimana kami membuat input menjadi segmen-segmen berukuran 8 character yang mana kami nantinya tidak perlu mengganti algoritma enkripsi sebelumnya.

Jadi, kami hanya membuat beberapa fungsi pembantu untuk memisahkan text dan untuk melakukan loopin pada dekripsi atau enkripsi.

---

## Implementasi DES di Client

Jadi kami membuat enkripsi dan dekripsi pada file terpisah `des.py`. Nantinya di client1 dan client2 akan mengimport function dekripsi dan enkripsinya. Saat ingin mengirim pesan, maka pesan akan di enkripsi terlebih dahulu dan begitu juga saat mendapatkan persan maka pesan akan didekripsi terlebih dahulu.

---

## Socket Programming

Untuk implementasi socket programming, kami mengikuti tutorial dari link yang diberikan https://www.digitalocean.com/community/tutorials/python-socket-programming-server-client. Namun ada beberapa perubahan pada `server.py` karna kami menggunakan 2 client dan kami menjalankannya di localhost.
