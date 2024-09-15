# Tugas Pertemuan 2
Penjelasan source code

1. File form_data.dart
    Pada file form_data.dart ini berisi sebuah form input untuk memasukkan data pengguna, yaitu Nama, NIM, dan Tahun Lahir. File ini bersifat dinamis atau memiliki status dinami karena di dalamnya terdapat interaksi pengguna, yaitu dalam hal input data.
    File ini memiliki 3 controller, yaitu _namaController, _nimController, dan _tahunController. 3 controller tersebut digunakan untuk menangani input dari pengguna. Selain itu file ini juga memiliki beberapa TextField untuk memasukkan nama, NIM, dan tahun lahir, yaitu pada _textboxNama(), _textboxNIM(), dan _textboxTahun().
    File form_data.dart ini juga memiliki tombol “Simpan”, tombol tersebut berfungsi untuk mengambil data dari form, lalu mengubahnya menjadi variabel, setelah itu memindahkan ke halaman lain untuk menampilkan datanya menggunakan navigator.

2. File tampil_data.dart
     File tampil_data.dart ini merupakan file yang bertugas atau bertanggung jawab untuk menampilkan data yang diambil dari form.Variabel TampilData merupakan StatelessWidget yang menerima tiga parameter dari halaman form_data.dart, yaitu ada nama, NIM, dan tahun lahir.
Di dalam fungsi build, yaitu lebih tepatnya untuk menghitung umur adalah dengan mengurangi tahun lahir dari tahun saat ini (DateTime.now().year - tahun;). Lalu di bagian body container, file ini menampilkan teks yang menyatakan nama, NIM, dan umur pengguna

3. File main.dart
     File main.dart ini merupakan file yang menjadi bagian utama/entry point dari program flutter ini. Fungsi main() berfungsi untuk menjalankan aplikasi dengan memanggil “runApp”.
MyApp merupakan class utama dalam file ini yang merupakan “StatelessWidget”. Di class ini, program diinisialisasi dengan widget “FormData” sebagai halaman yang muncul atau ditampilkan pertama kali.
 
ALUR PROGRAM
1)	Pengguna membuka atau menjalankan program dan disajikan form untuk menginput Nama, NIM, dan Tahun Lahir
2)	Setelah menginput data, lalu pengguna menekan tombol “Simpan” dan program akan memproses data tersebut
3)	Lalu pengguna diarahkan ke halaman lain dimana halaman tersebut menampilkan data yang telah dimasukkan bersama dengan informasi umur.

Nama  : Luthfi Emillulfata
NIM  : H1D022017
Shift Baru  : C

## Screenshot
![image](https://github.com/user-attachments/assets/8b2ce578-98f9-4b2f-a101-237c6f301f36)
![image](https://github.com/user-attachments/assets/91087e7c-e226-46b6-95bb-abc5160f2528)
![image](https://github.com/user-attachments/assets/d5c05cdd-734a-4e20-8be2-62fa170e5dbb)



