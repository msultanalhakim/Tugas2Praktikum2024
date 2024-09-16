# Tugas Pertemuan 2

Nama : Muhammad Sultan Alhakim
NIM : H1D022105
Shift Baru: A


Pada tugas pertemuan kali ini akan menjelaskan proses passing data dari form menuju tampilan dalam aplikasi Flutter. Berikut adalah langkah-langkahnya:

Form Input Data:
Pengguna akan memasukkan data seperti nama, NIM, dan tahun lahir di form yang ada di file ui/form_data.dart. Form ini menggunakan TextField untuk menerima input dari pengguna yang disimpan menjadi variabel tertentu.

Menekan Tombol Simpan:
Setelah pengguna mengisi data, pengguna akan menekan tombol "Simpan". Saat tombol ini diklik, input pada form akan tersimpan ke dalam variabel yang telah dibentuk (string nama, string nim, int tahun) lalu mengirimkan parameter ke halaman hasil menggunakan Navigator.of(context).push.

Pindah ke Halaman Hasil:
Aplikasi akan membuka halaman baru untuk menampilkan dengan parameter yang telah dikirimkan berdasarkan input sebelumnya (nama, NIM, dan tahun lahir) lalu dicetak pada halaman hasil tersebut.

Menampilkan Data:
Pada halaman hasil, data yang dikirimkan akan ditampilkan. Kemudian pada halaman ini juga menghitung umur berdasarkan tahun lahir yang dimasukkan dan menampilkan informasi kepada pengguna.

## Screenshot
![Lampiran Form](https://github.com/user-attachments/assets/ce0c1c4e-07d5-48eb-88b5-94f732c74430)
![Lampiran Hasil](https://github.com/user-attachments/assets/18fcfaf7-e796-4919-9ea6-de4a344fbfba)
