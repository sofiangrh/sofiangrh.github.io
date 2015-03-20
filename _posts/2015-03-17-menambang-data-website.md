---
layout: post
title: Menambang Data Website.
categories: [text mining]
tags: [web, database]
fullview: true.
---

Sebuah *website* dapat dianggap sebagai *database* tak terstruktur yang sangat besar jumlah dan ukurannya. Sumber data yang tersedia dapat diakses secara bebas di Internet dan sudah seharusnya direncanakan untuk menganalisis data-data *website* untuk membantu memenuhi kebutuhan terkait dengan isi, struktur serta pola aksesnya. Untuk itulah dalam ranah analisis data *website*, pada umumnya akan menggunakan tiga macam sumber data. Sumber data tersebut antara lain, *content* dari halaman *website*, struktur jejaring antar laman *website* yang terbentuk melalui tautan, serta sumber data *log* yang dihasilkan oleh *server* ataupun *client* (cookie). Terhadap masing-masing sumber data tersebut diperlukan adanya suatu tahapan *pre processing* yang akan berfungsi seperti halnya ETL (*Extract*, *Transform*, *Load*) dalam pemrosesan sebagai pembentukan data *warehouse*.

Berdasarkan sumber datanya, maka metode penambangan data *website* dapat dikelompokkan menjadi tiga bidang yaitu *web content mining*, *web structure mining* serta *web usage mining*. Dalam *web content mining*, tahapan dalam pre processing-nya akan menerapkan seperti yang dilakukan dalam *text mining* pada umumnya. Hanya saja perlu ditekankan di sini yaitu harus dapat membuang semua elemen yang dirasa tidak penting terhadap *content* (bold, italic, underline). 

*Web Structure Mining* akan lebih fokus pada analisis *graf* yang terbentuk dari struktur tautan dalam satu lingkungan atau batasan satu atau beberapa *website*. Setelah *graf* jejaring *website* terbentuk, maka *graf* dapat dianalisis. Penerapan pencocokan *graf* juga dapat diterapkan untuk melihat kemiripan struktur antar *website*. Bahkan *Social Network Analysis* dapat digunakan sebagai metode untuk menemukan *centrality* misalnya diantara kerumunan jejaring *website*. Dengan kata lain alogritma *graf* dapat digunakan untuk analisis jejaring *website* tersebut. Kemudian yang terakhir adalah *Web Usage Mining* yang akan fokus menganalisis transaksi yang diproses dari data *log* yang dihasilkan *web server*. Namun pemanfaatan dari *log server* tidak cukup dapat dihandalkan untuk digunakan dalam hak analisis transaksi. Salah satu penyebabnya adalah adanya *proxy server* dan *caching* pada *web browser* yang menyebabkan catatan *log server* menjadi tidak lengkap. 
