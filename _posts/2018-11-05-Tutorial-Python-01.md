---
layout: post
title:  "Tutorial Python (Bagian 1)"
categories: [Indonesian, tutorial, Python]
---

# Instalasi Python

Pada banyak distribusi Linux, Python biasanya sudah terpasang secara default.
Untuk mengujinya, silakan ketik perintah berikut pada terminal.

```bash
python --version
```

atau (jika ada pesan error pada perintah sebelumnya)

```bash
python3 --version
```

**Rekomendasi** Saya sangat merekomendasikan distribusi Python dari
Continum Analytics yang diberi nama Anaconda.
Distribusi ini dapat dipasang pada komputer dengan sistem operasi
Windows, Mac OSX, dan Linux. Pada tutorial ini, kita akan membahas
Python versi 3, karena itu silakan pilih versi Python 3.x pada distribusi
Anaconda.

# Interaksi dengan konsol Python

Sebagian besar pemula akan memulai belajar bahasa pemrograman Python dengan
cara menggunakan baris perintah atau konsol interaktif Python. Konsol ini
juga sering disebut sebagai interpreter Python. Kita akan mulai dengan
cara yang relatif mudah: menggunakan konsol IPython.

Pada Anaconda Navigator, Anda dapat memilih icon IPython untuk memulai konsol
IPython (qtconsole).

![IPython QtConsole]({{site.url}}/assets/IPython_QtConsole.png)

# Aritmatika dan fungsi matematika sederhana

Kita akan mulai dari bagaimana cara melakukan perhitungan matematika
sederhana pada Python.

# Variabel dan tipe data

```python
a = 99
type(a)
```

# Menampilkan teks ke layar

```python
my_name = "Fadjar"
print("Hello my name is " % my_name)
```

# Tipe data khusus

- List
- Tupel
- Dict
- Set

# Percabangan

if

# Perulangan

```python
for i in range(1:10):
    print("i = ", i)
```
    