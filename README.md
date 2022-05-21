# Tugas Akhir Pemodelan Oseanografi Team-19
Repository ini dibuat untuk memenuhi persyaratan Tugas Akhir Praktikum Pemodelan Oseanografi 2022. Repository ini memuat file berupa panduan dan lampiran script python (py) yang nantinya dapat digunakan untuk menjalankan beberapa model pemodelan oseanografi seperti Adveksi-Difusi 2D, Hidrodinamika 1D dan Hidrodinamika 2D. Mandatory library yang digunakan pada praktikum kali ini adalah Numpy, Matplotlib, Siphon, Sys, dan Pprint. Seluruh Script yang dibuat merupakan hasil dari Team 19 Program Studi Oseanografi Universitas Diponegoro 2020. Semoga repository ini dapat bermanfaat!! 
# AUTHORS (Team 19)
- Fadhil Nur Rizqi 26050120140116 B
- Juan Javier 26050120140095 B
- Irene Indah Yuni Simanungkalit 2605012014011 B
- Athanasius Dhento Wilasma
- Deno Ferdian	
- Shumanty Nathio Simanjuntak
- Kalika Padmarani 26050120140043 B
# Cara Penggunaan Script Python
1. Pengguna dapat membuka folder yang berisi kumpulan script python yang dapat dijalankan pada Jupyter Notebook, Visual Studio Code dan Google Colaboratory dalam repository ini. 
2. Setelah dibuka, tampilan script akan muncul seperti di bawah ini.


3. Script python dapat di-copy dan nantinya di-running atau dijalankan pada Jupyter Notebook, Visual Studio Code dan Google Colaboratory.
# MATERI
# Modul Adveksi-Difusi 2 Dimensi
- Pengertian dan Persamaan Pembangun
* Adveksi secara 2 Dimensi merupakan sebuah proses atau mekanisme pergerakan penyebaran atau perluasan materi/property/kuantitas/sifat fisik yang disebabkan oleh aliran fluida akibat dipengaruhi gaya-gaya tertentu dalam arah horizontal.

![adveksi](https://user-images.githubusercontent.com/105922449/169641685-f0855bc6-9db5-4832-8705-ecd86aa21344.JPG)

* Difusi secara 2 Dimensi merupakan sebuah proses transport pasif.

![difusi](https://user-images.githubusercontent.com/105922449/169641827-92a4786a-e6a3-4b84-a8b1-0e163e0ee8e9.JPG)

- Persamaan Adveksi-Difusi terutama 2 Dimensi adalah persamaan matematis yang didesain untuk mempelajari fenomena transpor polutan. Persamaan ini menggambarkan model pemodelan oseanografi yang menggambarkan proses transportasi suatu zat yang dipengaruhi gaya dalam dua dimensi.
# Langkah pengerjaan Script Adveksi-Difusi 2D
1. Pilih satu aplikasi untuk menjalankan script ini seperti Jupyter Notebook, Visual Studio Code atau Google Colaboratory. Kemudian meng-import mandatory library berupa matplotlib.pyplot, numpy dan sys. Dilengkapi juga dengan pendefinisian model yang akan dijalankan.

import matplotlib.pyplot as plt
import numpy as np
import sys
#%%
def percentage(part, whole):
    percentage = 100 * float(part)/float(whole)
    return str(round(percentage,2)) + "X"
    
    
2. Selanjutnya dimasukkan parameter awal dan parameter lanjutan untuk perhitungan polutan yang akan digunakan.


3. Setelah itu dilakukan perhitungan dibuat dengan rumusan U dan V untuk mengetahui sebaran dari polutan.


4. Dilanjutkan dengan pembuatan grid agar dalam pembuatan model sebagai boundary atau batas alat bantu untuk menyusun dan mengatur hasil akhir sebaran polutan.


5. Dilakukan iterasi otomatis sampai memenuhi syarat batas kestabilan.


6. Langkah terkahir yaitu membuat script untuk labelling pada grafik output sebaran polutan.


7. Script siap dijalankan

# Modul Hidrodinamika 1 Dimensi
- Pengertian dan Persamaan Pembangun
* Hidrodinamika merupakan salah satu cabang ilmu pengetahuan yang mempelajari gerak liquid atau gerak fluida cair khususnya gerak air, kondisi hidrodinamika merupakan salah satu aspek yang sangat berpengaruh terhadap proses - proses yang terjadi di pantai terutama gelombang dan arus bergantung pada bentuk dan karakteristik pantai. Hidrodinamika merupakan sebuah konsep sistem model numerik secara umum untuk memodelkan suatu simulasi baik simulasi muka air, aliran di estuari, teluk dan pantai. 
* Sedangkan Hidrodinamika 1D merupakan
# Modul Hidrodinamika 2 Dimensi
- Pengertian dan Persamaan Pembangun
* Hidrodinamika 2D merupakan
