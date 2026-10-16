# QA Portfolio — Anis Madani

Lulusan Teknologi Informasi (Universitas Jember) yang berfokus pada Quality Engineering. 
Pengujian black-box untuk aplikasi Android, e-commerce, dan web kesehatan.

**Kontak:** anismadani29@gmail.com | www.linkedin.com/in/anis-madani | 085124168892

## Ringkasan proyek

 Proyek | Platform | Test case | Lulus / Gagal | Tools | Temuan utama |
 |---|---|---|---|---|---|
 | [Hutan Ku](./01-hutan-ku) | Android | 40 | 36 / 4 | TestComplete |
 | [Ikan Hias](./02-ikan-hias) | Web | 23 | 17 / 6 | Manual |
 | [Kontrol Ibu Hamil](./03-ibu-hamil) | Web | 6 | 6 / 0 | Manual |
 | [Total](./04-total) | Test case 69 | Lulus 59 / Gagal 10 | 

 ## Temuan Utama
 |Ikan Hias (6 defect) |
 1. Data Pekerja: tombol Detail tidak merespons saat diklik.
 2. Data Ikan: tombol Detail tidak merespons saat diklik.
 3. Data Pemesanan: tombol Beli tetap muncul saat pesanan belum dicentang, dan menimbulkan error saat diklik.

|Hutan Ku (4 skenario gagal) |
1. Input nama: tombol kembali saat popup input nama aktif.
2. Ubah ruang hutan: skenario tidak menekan next.
3. Ubah ruang hutan: skenario tidak memilih hutan.
4. Ubah ruang hutan: menekan tidak pada popup.
Penyebab keempatnya sedang dianalisis dari log TestComplete (bug aplikasi atau masalah skrip pengujian).

## Cara saya menguji
1. Membaca use case dan menurunkannya menjadi skenario (basic flow dan alternate flow).
2. Menyusun test case dengan data valid, tidak valid, dan kosong.
3. Mengeksekusi, mencatat hasil beserta log atau screenshot, lalu melaporkan temuan.

## Catatan
Semua proyek dikerjakan sebagai proyek akademik di Universitas Jember (2018 sampai 2019).
