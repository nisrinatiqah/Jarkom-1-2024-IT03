# Laporan Resmi Praktikum Jarkom 2024 Modul-1

---

### Anggota Kelompok IT 03 :

- Nicholas Arya Krisnugroho Rerangin (5027231058)
- Nisrina Atiqah Dwiputri Ridzki (5027231075)

# Daftar Isi

- [Illegal Breakthrough](#illegal-breakthrough)
- [FTP Login](#ftp-login)
- [Suprise](#surprise)
- [Corporate Breach](#corporate-breach)
- [EZ](#ez)
- [Rizzset](#rizzset)



---
## Illegal Breakthrough
---
### Deskripsi
Seorang full-stack developer bernama kevin sedang membuat sebuah web yang memiliki login page. Tetapi karena ia hanya digaji rendah, ia lupa untuk mengamankan web yang ia buat. Bantulah kevin untuk tracing dari jejak yang ditinggalkan oleh attacker.

### Flag
JarkomIT{supp0rt_k0k_l3m4h_bg_v8CT00tWiKLnufX5HNXFOOMsvG6RTEzIuFa4BhPXImZ68pDXjnGvG6}

### Penjelasan 
1. Buka Analyze > Follow > TCP Stream = Langsung terlihat di stream pertama terdapat text "Hello, my name is Nakhimov and I'm here trying to get in to your system. I'm sorry, but your system is too weak for me. I'm in." Bisa terlihat bahwa nama attacker adalah Nakhimov.
2. Buka slide stream selanjutnya dan coba coba email yang muncul
3. Setelah di slide stream 207 terdapat tulisan "email=jarkomsupport%40gmail.com&password=j4rk0mg4c0rbg". Sehingga didapat emailnya jarkomsupport@gmail.com (hilangkan %40) dan passwordnya j4rk0mg4c0rbg. Flag langsung muncul!

### Dokumentasi Pengerjaan



---
## FTP Login
---
### Deskripsi
Seseorang menemukan sebuah celah dalam sebuah server. Ia mencoba untuk melakukan brute force login dan ia berhasil masuk. Lakukan pemeriksaan untuk melihat apa yang dilakukan oleh orang tersebut!

### Flag

Sebelum lanjut ke langkah pertama, download file yang dibutuhkan menggunakan
command `wget` seperti berikut :

### Penjelasan 


### Dokumentasi Pengerjaan

- ![ftploginn](https://github.com/user-attachments/assets/4b0a3ce0-78ac-4615-8b91-9a6a271a800e)



---
## Surprise
---
### Deskripsi
Setelah mengetahui apa yang diketahui pada challenge sebelumnya, sekarang lakukan analisis untuk mengetahui apa yang sebenarnya terjadi.
File sama seperti FTP Login.

### Flag
JarkomIT{supp0rt_k0k_l3m4h_bg_v8CT00tWiKLnufX5HNXFOOMsvG6RTEzIuFa4BhPXImZ68pDXjnGvG6}

### Penjelasan 
1. Buka Analyze > Follow > TCP Stream = Langsung terlihat di stream pertama terdapat text "Hello, my name is Nakhimov and I'm here trying to get in to your system. I'm sorry, but your system is too weak for me. I'm in." Bisa terlihat bahwa nama attacker adalah Nakhimov.
2. Buka slide stream selanjutnya dan coba coba email yang muncul
3. Setelah di slide stream 207 terdapat tulisan "email=jarkomsupport%40gmail.com&password=j4rk0mg4c0rbg". Sehingga didapat emailnya jarkomsupport@gmail.com (hilangkan %40) dan passwordnya j4rk0mg4c0rbg. Flag langsung muncul!

### Dokumentasi Pengerjaan

- ![surprise](https://github.com/user-attachments/assets/d26bafde-0411-4783-a917-91255a658e8b)




---
## Corporate Breach
---
### Deskripsi
Sebuah perusahaan IT support mendapatkan serangan oleh orang tidak dikenal. Bantulah perusahaan tersebut untuk melacak jejak yang ditinggalkan oleh attacker.

### Flag
JarkomIT{supp0rt_k0k_l3m4h_bg_v8CT00tWiKLnufX5HNXFOOMsvG6RTEzIuFa4BhPXImZ68pDXjnGvG6}

### Penjelasan 
1. Buka Analyze > Follow > TCP Stream = Langsung terlihat di stream pertama terdapat text "Hello, my name is Nakhimov and I'm here trying to get in to your system. I'm sorry, but your system is too weak for me. I'm in." Bisa terlihat bahwa nama attacker adalah Nakhimov.
2. Buka slide stream selanjutnya dan coba coba email yang muncul
3. Setelah di slide stream 207 terdapat tulisan "email=jarkomsupport%40gmail.com&password=j4rk0mg4c0rbg". Sehingga didapat emailnya jarkomsupport@gmail.com (hilangkan %40) dan passwordnya j4rk0mg4c0rbg. Flag langsung muncul!

### Dokumentasi Pengerjaan

- ![WhatsApp Image 2024-09-18 at 23 59 30_962951cc](https://github.com/user-attachments/assets/c184343f-b818-4d91-b326-903f7521a989)

- ![WhatsApp Image 2024-09-19 at 00 00 14_34beb25b](https://github.com/user-attachments/assets/ad651566-d340-4e1e-a234-37fab471d9e7)



---
## EZ
---
### Deskripsi
Aku sedang mencoba bikin chat service tapi kayanya pesannya bisa di sniffing deh? coba temukan pesannya.

### Flag
JarkomIT{supp0rt_k0k_l3m4h_bg_v8CT00tWiKLnufX5HNXFOOMsvG6RTEzIuFa4BhPXImZ68pDXjnGvG6}

### Penjelasan 
1. Untuk mencari jawaban dari log, buka Analyze > Follow > TCP Stream = Langsung terlihat di stream pertama terdapat 2 string yaitu "jawabannya jawaban"
2. Untuk mencari port yang digunakan, lihat di sebelah kiri bawah terdapat tulisan port : 1234. Flag langsung muncul!

### Dokumentasi Pengerjaan

-![WhatsApp Image 2024-09-19 at 00 25 05_9ee459b0](https://github.com/user-attachments/assets/ac7b2f2d-dd9b-4de4-aa43-56b99a80f54e)



---
## Rizzset
---
### Deskripsi
Aku sedang bereksperimen dengan suatu tools, kamu juga bisa menggunakannya untuk menjawab soal ini

### Flag
JarkomIT{supp0rt_k0k_l3m4h_bg_v8CT00tWiKLnufX5HNXFOOMsvG6RTEzIuFa4BhPXImZ68pDXjnGvG6}

### Penjelasan 
1. Buka Analyze > Follow > TCP Stream = Langsung terlihat di stream pertama terdapat text "Hello, my name is Nakhimov and I'm here trying to get in to your system. I'm sorry, but your system is too weak for me. I'm in." Bisa terlihat bahwa nama attacker adalah Nakhimov.
2. Buka slide stream selanjutnya dan coba coba email yang muncul
3. Setelah di slide stream 207 terdapat tulisan "email=jarkomsupport%40gmail.com&password=j4rk0mg4c0rbg". Sehingga didapat emailnya jarkomsupport@gmail.com (hilangkan %40) dan passwordnya j4rk0mg4c0rbg. Flag langsung muncul!

### Dokumentasi Pengerjaan

- ![WhatsApp Image 2024-09-18 at 23 59 30_962951cc](https://github.com/user-attachments/assets/c184343f-b818-4d91-b326-903f7521a989)

- ![WhatsApp Image 2024-09-19 at 00 00 14_34beb25b](https://github.com/user-attachments/assets/ad651566-d340-4e1e-a234-37fab471d9e7)
