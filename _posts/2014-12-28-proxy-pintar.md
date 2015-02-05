---
layout: post
title: Proxy Pintar.
categories: [unek-unek]
tags: [text mining, proxy]
fullview: true.
---

Sejak diberlakukannya Undang-Undang ITE di Indonesia banyak sekali komentar dan pendapat yang muncul di media. Salah satu yang sering diperbincangkan adalah pemblokiran situs-situs pornografi dan situs-situs yang mengandung SARA. Langkah pemerintah melalui Kementrian Kominfo menjanjikan sebuah alat bantu berupa perangkat lunak yang digunakan untuk memblokir akses ke situs-situs "terlarang" tersebut. Langkah seperti ini mungkin sedikit tidak tepat sasaran, alat bantu ini nantinya akan memiliki sebuah basis data yang berisi semua URL yang dinyatakan sebagai situs terlarang. Seperti pada sebuah *Antivirus*, basis data untuk alat bantu pemblokir ini akan selalu ter-*update* dan dapat diunduh secara bebas oleh masyarakat. 

Penerapan metode klasifikasi *text mining* bisa menjadi solusi sebuah pemblokir handal. Ketika pengguna mengakses sebuah URL dari sebuah jaringan yang digunakannya *gateway* yang dituju dipasang *program* ini yang berkoordinasi dengan *proxy server*. Setiap halaman yang akan diakses pengguna akan diuji terlebih oleh alat penyaring ini. Jika ternyata termasuk kategori "terlarang" maka akan ada sebuah peringatan bahwa halaman yang diakses ini termasuk kategori yang tidak boleh diakses. Ketika ditemukan sebuah halaman "terlarang" baru, secara otomatis tercatat pada basis data. Konsepnya seperti sebuah *spam filtering* yang diterapkan pada *google mail*. 
