---
layout: post
title: Memulai Proyek Pada Django.
categories: [aplikasi web]
tags: [python, django, pemasangan]
fullview: true.
---

Beberapa dari Anda mungkin sudah pernah mendengar kata Django terutama bagi Anda yang pernah menggunakan Python. Django adalah sebuah *web framework* berbasis python yang menggunakan sistem MTV (*Model*, *Template* dan *View*). *Web framework* itu sendiri adalah sebuah alat yang digunakan untuk mempermudah dalam membangun sebuah website yang isinya terdiri fungsi, *plugin* dan konsep sehingga membentuk suatu sistem tertentu. Sebelum memulai proyek lakulan proses pemasangan Django *framework*.

1. Untuk memasang Django diperlukan beberapa depedensi yang harus dipasang. 
   <p><code>$ sudo apt-get install python python-dev python-setuptools</code></p>

2. Pada kesempatan ini untuk proses pemasangan Django Saya menggunakan pip. Pip (*python indexing project*) merupakan package manager pada Python. Untuk memasang pip gunakan easy_install.
   <p><code>$ sudo easy_install pip</code></p>

3. Kemudian pasang Django menggunakan pip.
   <p><code>$ sudo pip install django</code></p>


Selesai untuk proses pemasangan Django, sekarang langkah-langkah untuk memulai proyek.
1. Buat proyek dan ketikan perintah berikut ke dalam *console*.
   <p><code>$ django-admin.py startproject namaproyek</code></p>

2. Buat apps Django
   <p><code>$ django-admin.py startapp namaapp</code></p>

3. Jalankan *server* 
   <p><code>$ python manage.py runserver</code></p>

4. Kemudian buka *web browser* dan buka alamat ini [http://localhost:8000](http://localhost:8000) Jika berhasil akan muncul tampilan seperti ini.<br> ![image](http://s27.postimg.org/88q7gofnn/image.png)

Jika berhasil lakukan eksplorasi lebih lanjut mengenai pembuatan proyek dan app pada Django.
