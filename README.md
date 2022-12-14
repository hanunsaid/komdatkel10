# Aplikasi Web "Kavita"
![android-chrome-256x256](https://user-images.githubusercontent.com/95085861/196993908-ec7d603c-a279-4d6a-ad71-5eaf52861e0e.png)

# Anggota Kelompok 10
| Nama                      | NIM           |
| :--------------------     | :------------ |
| Dhea Miranda Widana Putri | G6401201019   |
| Hanun Attaya Said         | G6401201049   |
| Nadira Arbanisa S.        | G6401201032   |

---

## Sekilas Tentang

Kavita adalah server membaca lintas platform yang cepat, kaya fitur. Dibangun dengan fokus untuk manga, e-book, dan komik dengan tujuan menjadi solusi lengkap untuk semua kebutuhan membaca Anda.

## Instalasi

**Kebutuhan Sistem:**
- Unix, Linux atau Windows.
- RAM minimal 95 Mb+

**Proses Instalasi**
1. Unduh **Kavita** ke dalam direktori
```
wget https://github.com/Kareadita/Kavita/releases/download/v0.5.6/kavita-linux-x64.tar.gz
```
2. Ekstak file yang sudah diunduh
```
sudo gzip -d kavita-linux-x64.tar.gz
```
3. Gunakan chmod agar Kavita bisa mengakses direktori yang sudah disimpan
```
chmod +x ./Kavita
```
4. Jalankan program Kavita
```
./Kavita
```


## Cara Pemakaian

1. Sebelum menggunakan Kavita, kita perlu membuat akun terlebih dahulu.
![image](https://user-images.githubusercontent.com/95017091/196713457-6941eecc-2c13-4e67-9ce9-f343e100c280.png)

2. Login kedalam akun yang sudah dibuat
![image](https://user-images.githubusercontent.com/95017091/196713937-96de4bec-adf2-4c52-88f7-29a0ed449cee.png)

3. Setelah login, kita akan diarahkan ke halaman Dashboard. Disini kita dapat melihat log website, users yang terdaftar, library, media, task, dan system yang digunakan saat ini.
![image](https://user-images.githubusercontent.com/95017091/196714356-56188016-1dcf-4eb4-8165-8c5c86b03644.png)

4. Penambahan buku atau manga dilakukan pada menu libraries. Kita diminta untuk memberikan nama library yang ingin dibuat, memilih kategori library, dan memilih direktori folder yang berisi buku/manga yang ingin ditambahkan
![image](https://user-images.githubusercontent.com/95017091/196715404-cce117d6-9f2e-4591-99d6-5ebbeefb1335.png)
![image](https://user-images.githubusercontent.com/95017091/196715492-10a0b9c4-f8ed-4525-a13b-166091f15d17.png)

5. Pada bagian samping kiri, terdapat beberapa menu. Menu **Home** merupakan tempat untuk mengetahui buku/manga apa saja yang baru saja diupdate dan ditambahkan
![image](https://user-images.githubusercontent.com/95017091/196716634-503a4c25-d666-442b-aa2e-87a02cbb7c3a.png)

6. Menu **Want to Read** merupakan tempat untuk menyimpan bacaan apa saja yang ingin kita baca
![image](https://user-images.githubusercontent.com/95017091/196717148-ae3dcc45-dc81-4466-b9ad-ad221e2951f4.png)

7. Menu **Collections** merupakan tempat untuk menyimpan koleksi apa saja yang kita baca
![image](https://user-images.githubusercontent.com/95017091/196717442-e941a4e3-a069-4dc5-b15d-389f888c5359.png)

8. Menu **Reading List** merupakan tempat untuk menyimpan buku apa saja yang sedang kita baca
![image](https://user-images.githubusercontent.com/95017091/196717885-f50c4fbf-1ac3-468e-b265-e32df35cdd1f.png)
![image](https://user-images.githubusercontent.com/95017091/196718134-8f82ab63-59cf-4ece-9792-0159e05d0b34.png)

9. Menu **Bookmark** merupakan tempat untuk menyimpan bookmark pada buku/manga yang dibaca
![image](https://user-images.githubusercontent.com/95017091/196719286-57a9a66a-b618-43f1-b0e5-3e12eda57e19.png)

10. Menu **All Series** merupakan tempat semua series buku dan manga yang tersimpan pada aplikasi ditampilkan
![image](https://user-images.githubusercontent.com/95017091/196719997-83fd8ee0-3f82-456b-979c-4cb8ffb503c8.png)

11. menu **Book** dan **Manga** merupakan tempat semua buku dan manga ditampilkan sesuai kategori masing-masing
![image](https://user-images.githubusercontent.com/95017091/196720353-8327c98e-a3fd-45cc-960a-5522e709528e.png)
![image](https://user-images.githubusercontent.com/95017091/196720433-cd47f7d9-e649-4d23-9b5c-560a87501b62.png)



## Pembahasan

- Pendapat anda tentang aplikasi web ini
    - Kelebihan
        - Bisa mengupload segala jenis file sesuai dengan yang dimasuki (Misal e-book bisa EPUB2, EPUB3, PDF dsb.)
        - Berfokus pada pengalaman membaca dan menjelajahi koleksi pembaca. Pembaca epub dan pdf memungkinkan teks dan kaya fitur.
        - Lintas Platform tanpa dependensi
        - Mixed media Libraries
        - Menggunakan metadata dan penguraian nama file untuk mengelompokkan ke dalam seri, volume, dll.
    - Kekurangan
        - Perlunya ada download tambahan khusus untuk metadata
        - Tidak akan berjalan pada prosesor (CPU) yang tidak mendukung set instruksi SSE4.2
        - Menggunakan nama file untuk penguraian dan tidak didesain untuk menggunakan struktur folder.
- Bandingkan dengan aplikasi web lain yang sejenis
    - Komga, lebih fokus pada Komik dan pengelolaan komik (termasuk membaca), tidak mendukung pembacaan dokumen berbasis teks apa pun sebagai teks (alias epub 
    dibaca sebagai gambar). Perangkat lunak hebat, UX alternatif, pengembangan aktif.
    -Calibre-Web, frontend yang lebih bagus untuk Calibre. Harus memiliki Calibre yang mengelola file. UX-nya jauh lebih bagus daripada aplikasi Calibre yang 
    sebenarnya. Sangat fokus pada ebooks.
    - Ubooquity, dikenal oleh semua orang. Memetakan folder-folder ke dalam kartu-kartu dan menyediakan pembaca dasar untuk cbz/cbr dan pdf (sebagai gambar). 
    Tidak lagi dikembangkan.


## Referensi

Cantumkan tiap sumber informasi yang anda pakai.
- https://github.com/Kareadita/Kavita
- https://wiki.kavitareader.com/en
