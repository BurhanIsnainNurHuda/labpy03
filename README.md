# Tugas Praktikum 3

    Nama: Burhan Isnain Nur Huda
    NIM: 312410266
    Kelas: TI.24.A.2
    Mata Kuliah: Bahasa Pemograman

# Latihan 1: latihan1.py

# Alur Algoritma

![IMG_20241104_150140](https://github.com/user-attachments/assets/de1f6e5a-cc33-4070-ba69-3dfcd630e565)

    Penjelasan:
    •Import Modul `random`: Kode ini mengimpor modul `random` dari Python, yang menyediakan fungsi untuk menghasilkan bilangan acak.
    •Input Nilai `n`: Kode ini meminta pengguna untuk memasukkan nilai `n`, yang menentukan berapa banyak bilangan acak yang ingin dihasilkan.
    •Loop `for`: Kode ini menggunakan loop `for` untuk mengulang `n` kali.
    •Generate Bilangan Acak: Dalam setiap iterasi loop, kode ini memanggil fungsi `random()` dari modul `random` untuk menghasilkan bilangan acak antara 0 dan 1. Kemudian, kode ini mengalikan bilangan acak dengan 0.5 untuk memastikan bilangan acak berada di antara 0 dan 0.5.
    •Cetak Hasil: Kode ini mencetak hasil bilangan acak yang dihasilkan ke layar, disertai dengan nomor urutnya.
    •Cetak Pesan "Selesai": Setelah loop `for` selesai, kode ini mencetak pesan "Selesai" untuk mengindikasikan bahwa program telah selesai mengeksekusi.

Cara Menjalankan atau Nge Run Program:

    •Simpan kode di file Python (misalnya, `latihan1.py`).
    •Buka terminal atau command prompt.
    •Jalankan program dengan perintah `python latihan1.py`.
    •Program akan meminta Anda untuk memasukkan nilai `n`.
    •Masukkan nilai `n` dan tekan enter.
    •Program akan menampilkan `n` bilangan acak yang lebih kecil dari 0.5, disertai dengan pesan "Selesai".    

# Input
![IMG_20241104_143058](https://github.com/user-attachments/assets/5fcda2e7-f710-43ac-8b91-3fa766a0d6aa)

•Penjelasan

    N: program meminta input berupa bilangan bulat untuk menentukan
       berapa banyak bilangan random yang akan dihasilkan.

# Output 
![IMG_20241104_143719](https://github.com/user-attachments/assets/c3a3db59-024d-4707-8890-d00c873b454f)

•Penjelasan

    data ke: i => nilai: Program kemudian mengeluarkan output berupa daftar bilangan random dengan jumlah N yang ditentukan. Setiap output bilangan random ditampilkan dengan keterangan "data ke: i", dimana i adalah urutan bilangan random yang dihasilkan. Nilai yang dihasilkan adalah bilangan decimal.

• Penjelasan Keseluruhan dari Input dan Output

    •Program meminta input dari user untuk menentukan berapa banyak bilangan random yang akan dihasilkan.
    •Program kemudian menggunakan fungsi `random()` untuk menghasilkan bilangan random.
    •Program kemudian mencetak bilangan random yang dihasilkan ke layar dengan keterangan "data ke: i",
     dimana i adalah urutan bilangan random yang dihasilkan.
    •Program mencetak "Selesai" setelah selesai memproses semua bilangan random.

Fungsi random()

    •Fungsi `random()` di Python digunakan untuk menghasilkan bilangan random antara 0 dan 1.
    •Fungsi `random()` termasuk di modul `random` dan perlu diimport sebelum digunakan.

Contoh:     
![IMG_20241104_144321](https://github.com/user-attachments/assets/7f5a70ec-9c3a-470f-afa5-b2985af2a084)

Program di atas akan mencetak bilangan random antara 0 dan 1.


# Latihan 2: latihan2.py

# Alur Algoritma 
![IMG_20241104_162720](https://github.com/user-attachments/assets/79064f29-b575-49d5-8f01-4e03737993a4)

    Penjelasan:
    1.Inisialisasi Variabel:

    •Program menginisialisasi variabel `laba` dengan nilai `0` untuk melacak total keuntungan.
    •Program menginisialisasi variabel `keuntungan` dengan nilai `0` untuk melacak keuntungan per bulan.
    •Program menginisialisasi variabel `modal` dengan nilai `100000000` (100 juta) untuk melacak modal awal.

    2.Perulangan (Loop) untuk 8 Bulan:

    •Program menggunakan perulangan `for` untuk mengulangi proses perhitungan selama 8 bulan.
    •Dalam setiap iterasi perulangan, program menjalankan langkah-langkah berikut:

    3.Perhitungan Keuntungan per Bulan:

    •Bulan ke-1 dan ke-2: Keuntungan tetap `0` karena belum mendapatkan laba.
    •Bulan ke-3: Keuntungan dihitung dengan `modal * 0.01` (1% dari modal)
    •Bulan ke-4: Keuntungan sama dengan keuntungan bulan ke-3.
    •Bulan ke-5: Keuntungan dihitung dengan `keuntungan * 1.05` (meningkat 5% dari keuntungan bulan ke-4).
    •Bulan ke-6, ke-7: Keuntungan sama dengan keuntungan bulan ke-5.
    •Bulan ke-8: Keuntungan dihitung dengan `keuntungan * 0.98` (menurun 2% dari keuntungan bulan ke-7).

    4.Penambahan Total Keuntungan:
    •Setiap akhir bulan, program menambahkan `keuntungan` ke variabel `laba` untuk menghitung total kePenjelasan:

    5.Cetak Total Keuntungan:
    •Setelah 8 bulan, program mencetak total keuntungan yang tersimpan dalam variabel `laba`.
# Hasil Input & Output 

![IMG_20241104_164807](https://github.com/user-attachments/assets/9028ab4e-c0b6-4276-9b7c-30ba3f4af454)

•Penjelasan

    1. Bulan 1 dan 2: Pengusaha belum mendapatkan laba, jadi laba pada bulan 1 dan 2 adalah 0.
    2. Bulan 3: Pengusaha mulai mendapatkan laba sebesar 1% dari modal awal 100 juta, yang berarti laba bulan 3 adalah 100.000.000 x 0.01 = 1.000.000.
    3. Bulan 4: Laba bulan 4 sama dengan laba bulan 3, yaitu 1.000.000.
    4. Bulan 5: Pendapatan meningkat 5% dari laba bulan 4, sehingga laba bulan 5 adalah 1.000.000 x 1.05 = 5.000.000.
    5. Bulan 6, 7: Karena tidak ada perubahan pada bulan 6 dan 7, laba bulan 6 dan 7 sama dengan laba bulan 5, yaitu 5.000.000.
    6. Bulan 8: Keuntungan mengalami penurunan sebesar 2% dari laba bulan 7, sehingga laba bulan 8 adalah 5.000.000 x 0.98 = 4.900.000.
    7.Total laba: Untuk menghitung total laba selama 8 bulan, kita menjumlahkan semua laba bulan: 0 + 0 + 1.000.000 + 1.000.000 + 5.000.000 + 5.000.000 + 5.000.000 + 4.900.000 = 19.000.000
    Jadi, total keuntungan selama 8 bulan berjalan usahanya adalah 19.000.000.
