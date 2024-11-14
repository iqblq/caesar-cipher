## README

# Caesar Cipher Calculator

Caesar Cipher Calculator adalah aplikasi GUI berbasis Python yang menggunakan `tkinter` untuk mengenkripsi dan mendekripsi teks menggunakan metode Caesar Cipher. Aplikasi ini memungkinkan pengguna untuk mengubah teks sesuai dengan nilai pergeseran yang diinginkan, antara 1 hingga 25.

## Fitur

- **Enkripsi**: Memungkinkan pengguna untuk mengenkripsi teks dengan Caesar Cipher berdasarkan nilai pergeseran.
- **Dekripsi**: Mengembalikan teks yang terenkripsi menjadi teks asli berdasarkan nilai pergeseran.
- **Antarmuka Sederhana**: Menggunakan `tkinter` untuk tampilan sederhana dengan fitur full-screen.
- **Peringatan Input**: Memastikan nilai pergeseran adalah antara 1 dan 25, serta memeriksa input numerik untuk pergeseran.

## Persyaratan

- Python 3.x
- Tkinter (biasanya sudah terinstal pada Python)

## Instalasi

1. Clone repositori ini:
   ```bash
   git clone https://github.com/username/Caesar-Cipher-Calculator.git
   cd Caesar-Cipher-Calculator
   ```
   
2. Jalankan program:
   ```bash
   python main.py
   ```

## Penggunaan

1. Masukkan teks yang ingin dienkripsi atau didekripsi pada kotak "Masukkan Teks".
2. Masukkan nilai pergeseran antara 1 hingga 25 di kotak "Pergeseran".
3. Klik tombol **Enkripsi** untuk mengenkripsi teks, atau tombol **Dekripsi** untuk mendekripsi teks.
4. Hasil akan muncul di kotak "Hasil".
5. Untuk keluar dari aplikasi, klik tombol **Keluar**.

## Struktur Proyek

- **main.py**: Kode utama untuk menjalankan aplikasi Caesar Cipher Calculator.

## Penjelasan Fungsi Utama

- **enkripsi(plain_text, shift)**: Fungsi untuk mengenkripsi teks berdasarkan pergeseran yang diberikan.
- **dekripsi(cipher_text, shift)**: Fungsi untuk mendekripsi teks yang telah terenkripsi berdasarkan pergeseran.
- **proses_enkripsi()** dan **proses_dekripsi()**: Fungsi untuk menangani input pengguna, melakukan enkripsi atau dekripsi, dan menampilkan hasilnya.
- **keluar_aplikasi()**: Fungsi untuk menutup aplikasi.

## Tampilan Aplikasi

Tampilan antarmuka disesuaikan agar mudah digunakan, dengan tata letak grid dan komponen yang memiliki warna latar belakang dan teks yang menarik serta menggunakan font yang konsisten.

## Lisensi

Proyek ini dilisensikan di bawah lisensi MIT.

---

Semoga aplikasi ini berguna! Silakan kontribusi dan beri bintang jika Anda menemukan proyek ini bermanfaat.
