# Praktikum11

- PIP merupakan package manager untuk mengelola package dan modul pada python.

- Dengan menggunakan PIP, kita dapat menggunakan library yang tersedia bebas dari directory package library python.

- Untuk dapat menggunakan PIP, perlu diinstall terlebih dahulu, silahkan kunjungi tautan berikut untuk proses instalasinya: https://pypi.org/project/pip/

# Perintah Dasar Pada PIP

- `pip --version->` menampilkan versi PIP yang terinstall.

- `pip install nama_package->` menampilkan versi PIP yang terinstall.

- `pip uninstall nama_package ->` menghapus package.

- `pip list`  untuk menampilkan daftar package yang terinstall.

# Contoh Penggunaan PIP List

![img.1](gambar/pip%20list.png)

# Web Scraping Menggunakan Python

## Introducing

- Data Scraping adalah suatu teknik dalam mengumpulkan data dari berbagai sumber data.

- Salah satunya adalah dari website, sehingga lebih dikenal dengan Web Scraping.

- Secara Umum ada dua teknik dalam Web Scraping yaitu Manual (copy paste), dan Otomatis (dengan software/tools).

## Teknik Web Scraping

- Teknik Web Scraping

- Menggunakan regular expression

- Parsing data HTML

- Menggunakan DOM

- Menggunakan DOM

- Menggunakan Google Sheet

## Tools Yang Digunakan

* Python

1. Kunjungi tautan berikut untuk proses instalasinya: https://www.python.org/
![img.2](gambar/python.png)

2. Install Python 3.12.3

3. ketikan `Python` untuk melihat versi python yang telah terinstall.
![img.3](gambar/versi%20pip.png)

* Requests

- Requests merupakan library HTTP untuk proses mengirim dan mengambil data menggunakan protokol HTTP.

- Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah:
![img.4](gambar/requests.png)

* BeautifulSoup

- BeautifulSoup merupakan library yang digunakan untuk proses web scraping halaman HTML dan XML.

- Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah:
![img.5](gambar/BS.png)

* Pandas

- Pandas adalah library open source pada Python yang sering digunakan untuk memproses data yang meliputi pembersihan data, manipulasi data, hingga melakukan analisis data. Ketika melakukan suatu analisis, kita tidak bisa menggunakan data mentah.

- Penggunaan Pandas umumnya disingkat menjadi pd. Format penulisan saat akan memanggil library Pandas adalah `import pandas as pd`. Ingat untuk selalu import library yang akan digunakan terlebih dahulu.  

- Untuk menginstallnya menggunakan perintah pip, seperti pada gambar di bawah:
![img.6](gambar/pandas.jpg)

* Google Colab

1. Kunjungi tautan berikut untuk membuat project baru: https://colab.research.google.com/

2. Kemudian klik File

3. Kemudian Buat Notebook Baru
 
4. Beri nama proyeknya, untuk tampilannya seperti pada gambar di bawah:
![img.7](gambar/latihan%20PIP.png)

5. Kemudian Import Library yang telah kita install sebelumnya, untuk tampilannya seperti pada gambar di bawah:
![img.8](gambar/library.png)

6. Kemudian ketik program yang akan dijalankan Disini Saya menggunakan program Studi Kasus jadwal-sholat (URL : https://jadwalsholat.org/jadwal-sholat/monthly.php)
![img.9](gambar/program.png)

7. Jika sudah benar dan berhasil di RUN maka akan menghasilkan output seperti gambar di bawah:
![img.10](gambar/hasil.png)