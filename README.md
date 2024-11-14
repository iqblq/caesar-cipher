## README

# Caesar Cipher Calculator

Caesar Cipher Calculator adalah aplikasi GUI berbasis Python yang menggunakan `tkinter` untuk mengenkripsi dan mendekripsi teks menggunakan metode Caesar Cipher. Aplikasi ini memungkinkan pengguna untuk mengubah teks sesuai dengan nilai pergeseran yang diinginkan, antara 1 hingga 25.

## Fitur

- **Enkripsi dan Dekripsi**: Memungkinkan pengguna untuk mengenkripsi teks dengan Caesar Cipher berdasarkan nilai pergeseran, dan mengembalikan teks yang terenkripsi menjadi teks asli.
- **Antarmuka Sederhana**: Menggunakan `tkinter` untuk tampilan sederhana dengan fitur full-screen.
- **Validasi Input**: Memastikan nilai pergeseran adalah antara 1 dan 25, serta input numerik untuk pergeseran.

## Persyaratan

- Python 3.x
- Tkinter (biasanya sudah terinstal pada Python)

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/iqblq/caesar-cipher.git
   cd caesar-cipher
   ```
   
2. Jalankan program:
   ```bash
   python kalkulator_caesar.py
   ```

## Penggunaan

1. Masukkan teks yang ingin dienkripsi atau didekripsi pada kotak "Masukkan Teks".
2. Masukkan nilai pergeseran antara 1 hingga 25 di kotak "Pergeseran".
3. Klik tombol **Enkripsi** untuk mengenkripsi teks, atau tombol **Dekripsi** untuk mendekripsi teks.
4. Hasil akan muncul di kotak "Hasil".
5. Untuk keluar dari aplikasi, klik tombol **Keluar**.

## Struktur Proyek

- **kalkulator_caesar.py**: Kode utama untuk menjalankan aplikasi Caesar Cipher Calculator.

## Penjelasan Fungsi Utama

- **enkripsi(plain_text, shift)**: Fungsi untuk mengenkripsi teks berdasarkan pergeseran yang diberikan.
- **dekripsi(cipher_text, shift)**: Fungsi untuk mendekripsi teks yang telah terenkripsi.
- **proses_enkripsi()** dan **proses_dekripsi()**: Fungsi untuk menangani input pengguna, melakukan enkripsi atau dekripsi, dan menampilkan hasilnya.
- **keluar_aplikasi()**: Fungsi untuk menutup aplikasi.

## Tampilan Aplikasi

Antarmuka menampilkan tata letak grid yang rapi, dengan warna latar belakang dan teks yang kontras serta font yang konsisten.
![image](https://github.com/user-attachments/assets/5e85f99b-a121-4fb4-84f0-0ec473888e4a)
[GitHub Repository](https://github.com/iqblq/caesar-cipher.git)
