## Nomor 1

Container pada docker adalah sebagai wadah yang bertujuan untuk mengemas juga menjalankan aplikasi. Wadah ini mencakup kode, runtime, system tools, dan pengaturan. Container juga hanya bisa mengakses resource yang telah ditentukan dalam Docker image.

## Nomor 2

Perbedaan antara konsep container dengan virtual machine yaitu, Container dapat berjalan langsung diatas Sistem Operasi sedangkan Virtual Machine tidak. Virtual Machine menggunakan kernel tersendiri untuk menjalankan aplikasi didalamnya. Sedangkan container tidak diizinkan untuk mengakses kernel.

## Nomor 3

Docker file adalah blueprint untuk membuat image

## Nomor 4

Docker registry adalah tempat untuk download/upload image

## Nomor 5

Cara untuk menjalankan lebih dari 1 container secara bersamaan dan saling terhubung yaitu dengan menggunakan pod di Kubernetes kluster. Pod sendiri didesain untuk mendukung banyak proses (sebagai kontainer) yang membentuk sebuah layanan. Kontainer yang ada di dalam sebuah Pod akan otomatis ditempatkan bersama di dalam satu mesin fisik atau mesin virtual di dalam klaster. Kontainer tersebut dapat berbagi resource dan dependensi, berkomunikasi satu sama lain, dan berkoordinasi kapan dan bagaimana mereka diterminasi.
