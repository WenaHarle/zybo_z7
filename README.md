# Panduan Pemula Zybo Z7

## 1. Pendahuluan
Zybo Z7 adalah papan pengembangan yang menggabungkan prosesor ARM Cortex-A9 dengan logika FPGA, memungkinkan pengembangan perangkat keras dan lunak pada satu platform. Panduan ini dirancang untuk pemula dan akan membantu Anda memulai dengan Zybo Z7, mencakup konsep dasar, alat, dan proyek.

### Mengapa menggunakan Zybo Z7?
- Menggabungkan prosesor ARM dan FPGA untuk pengembangan fleksibel.  
- Mendukung pemrograman dengan Vivado (FPGA) dan Vitis (ARM).  
- Cocok untuk sistem tertanam, pemrosesan sinyal, dan desain perangkat keras-lunak.

## 2. Memulai
### Apa saja yang ada dalam kotak?
- Papan Zybo Z7  
- Kabel USB  
- Adaptor daya (jika termasuk)  
- Panduan memulai cepat

### Memahami tata letak papan
- Prosesor ARM Cortex-A9  
- Logika FPGA  
- Konektor PMOD  
- Port HDMI (Masuk/Keluar)  
- LED, tombol, dan sakelar pengguna  

### Menyiapkan lingkungan pengembangan
1. Instal **Vivado Design Suite** untuk pengembangan FPGA.  
2. Instal **Vitis IDE** untuk pemrograman prosesor ARM.  
3. Hubungkan Zybo Z7 ke komputer Anda melalui USB dan nyalakan.

## 3. Dasar-dasar Pemrograman
### Pengantar Vivado
- Digunakan untuk merancang dan memprogram logika FPGA.  
- Menawarkan antarmuka desain grafis.

### Pengantar Vitis
- Digunakan untuk menulis, mengompilasi, dan men-debug program untuk prosesor ARM.  

### Program Pertama: Menyalakan LED
- Tulis desain FPGA sederhana di Vivado untuk menyalakan LED pada papan.  
- Buat dan unggah bitstream ke Zybo Z7.

## 4. Menggunakan Prosesor ARM
### Menjalankan Program Dasar
- Buka Vitis dan tulis program “Hello World” untuk ARM Cortex-A9.  
- Kompilasi dan unggah program ke Zybo Z7.

### Antarmuka PMOD
- Hubungkan sensor atau tombol ke konektor PMOD.  
- Tulis program untuk membaca data dari PMOD.

## 5. Bekerja dengan FPGA
### Apa itu FPGA?
- Perangkat keras yang dapat diprogram ulang untuk memungkinkan desain logika kustom.

### Contoh Sederhana: Pengontrol LED
- Rancang sirkuit perangkat keras untuk mengontrol LED menggunakan sakelar.  
- Simulasikan, buat, dan unggah bitstream di Vivado.

### Menguji Bitstream FPGA
- Pastikan koneksi yang benar dan amati perilaku yang diharapkan.  

## 6. Menggunakan Periferal
### Output HDMI
- Sambungkan monitor HDMI ke Zybo Z7.  
- Tampilkan pola warna sederhana menggunakan logika FPGA.  

### Periferal Lainnya
- Hubungkan audio, Ethernet, atau periferal PMOD dan programkan.  

## 7. Pemecahan Masalah
- **Masalah Daya**: Pastikan pasokan daya yang benar.  
- **Kesalahan Pemrograman**: Periksa langkah desain dan koneksi.  
- **Masalah Logika FPGA**: Simulasikan desain sebelum membuat bitstream.  

## 8. Proyek Contoh untuk Pemula
1. **Menyalakan Beberapa LED**: Buat urutan LED berkedip menggunakan logika FPGA.  
2. **Input Tombol dengan PMOD**: Baca dan tampilkan status tombol pada LED.  
3. **Kalkulator Sederhana**: Gunakan prosesor ARM untuk menjalankan operasi aritmatika dasar.

## 9. Langkah Selanjutnya
- Pelajari topik lanjutan seperti Linux tertanam, pemrosesan sinyal, dan akselerasi perangkat keras.  
- Bergabung dengan komunitas Zybo Z7 dan temukan tutorial tambahan.  
- Bereksperimen dengan proyek yang lebih kompleks menggunakan FPGA dan prosesor ARM.

---
Selamat mencoba Zybo Z7!
