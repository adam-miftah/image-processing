# Laporan Proyek Pengolahan Citra Digital ( Image Processing )
Proyek ini bertujuan untuk melakukan pengolahan citra dasar menggunakan Python dan OpenCV. Dalam proyek ini, kita akan membaca citra, melakukan binarisasi, inversi warna, dan erosi pada citra tersebut. Hasil dari setiap langkah akan divisualisasikan untuk menunjukkan perubahan yang terjadi pada citra asli.
 
 # Sumber Kode
Sumber kode ini diperoleh dari teman saya. Kode ini ditulis dalam Python dan menggunakan beberapa library penting untuk pengolahan citra.

# Dependensi
Sebelum menjalankan kode ini, pastikan Anda telah menginstal library berikut:
- OpenCV
- NumPy
- Matplotlib
Anda dapat menginstalnya menggunakan pip:
pip install opencv-python numpy matplotlib

# Penjelasan Kode
1. Import Library: Mengimpor library yang diperlukan untuk pengolahan citra.
2. Membaca Citra: Membaca citra dari file dan mengonversinya menjadi grayscale.
3. Binarisasi Citra: Mengubah citra grayscale menjadi citra biner menggunakan metode Otsu.
4. Inversi Citra: Membalikkan warna piksel dalam citra biner.
5. Erosi Citra: Mengurangi ukuran objek dalam citra dengan menggunakan operasi morfologi erosi.
6. Visualisasi Hasil: Menampilkan citra asli dan citra hasil erosi menggunakan Matplotlib.
