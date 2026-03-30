# Buat Laporan di Sini
1. Library (Header Files)
#include <iostream>: Pustaka inti yang memberikan izin kepada program untuk melakukan operasi Input (masuk) dan Output (keluar). Tanpa ini, perintah seperti cout tidak akan dikenali.
#include <string>: Modul tambahan yang memungkinkan program menggunakan tipe data string, yaitu kumpulan karakter atau teks (seperti nama, alamat, atau kalimat).

2. Perintah Input & Output
cout (Console Out): Bertugas mengirimkan data atau teks dari dalam kode ke layar monitor agar bisa dibaca oleh pengguna.
cin (Console In): Digunakan untuk mengambil input data sederhana dari keyboard. Namun, cin akan berhenti membaca jika menemukan spasi.
getline(cin, variabel): Metode input yang lebih mumpuni dibanding cin. Fungsi ini mampu membaca seluruh baris teks termasuk spasi hingga pengguna menekan tombol Enter.

3. Implementasi Kode
string nama;: Deklarasi sebuah "wadah" atau variabel bernama nama yang khusus disiapkan untuk menyimpan teks.
getline(cin, nama);: Perintah untuk menangkap apa pun yang diketik user (misal: "Budi Santoso") dan menyimpannya ke dalam variabel nama.
cout << "Hello " << nama;: Instruksi untuk menggabungkan teks statis "Hello " dengan isi dari variabel nama, lalu menampilkannya secara bersamaan di layar.
