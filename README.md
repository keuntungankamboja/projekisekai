
**Sistem Pakar Penyakit Jantung Berbasis Web (PHP)**

Sistem pakar adalah aplikasi berbasis kecerdasan buatan yang dirancang untuk menyelesaikan masalah spesifik menggunakan pengetahuan dan aturan yang diambil dari pakar di bidang tertentu. Dalam hal ini, sistem pakar penyakit jantung berbasis web adalah sistem yang membantu pengguna dalam mendiagnosis atau memberikan rekomendasi terkait penyakit jantung secara online.

### Komponen Utama Sistem Pakar:
1. **Basis Pengetahuan:**  
   Berisi fakta dan aturan yang digunakan untuk menganalisis kondisi kesehatan terkait penyakit jantung. Informasi ini didapat dari dokter atau pakar jantung.

2. **Mesin Inferensi:**  
   Bagian sistem yang memproses data dari pengguna dan mencocokkannya dengan aturan dalam basis pengetahuan untuk menghasilkan diagnosa atau rekomendasi.

3. **Antarmuka Pengguna:**  
   Dibangun menggunakan bahasa pemrograman PHP yang memungkinkan pengguna untuk berinteraksi dengan sistem melalui halaman web.

4. **Database:**  
   Digunakan untuk menyimpan data pengguna, gejala, aturan, serta hasil diagnosa. Database yang umum digunakan adalah MySQL atau MariaDB.

### Fitur Utama:
- Input gejala penyakit oleh pengguna.
- Analisis gejala berdasarkan aturan yang telah ditetapkan.
- Penyajian hasil diagnosa awal atau rekomendasi tindakan medis.
- Penyimpanan riwayat diagnosa pengguna.

### Teknologi yang Digunakan:
- **Frontend:** HTML, CSS, JavaScript untuk antarmuka pengguna.
- **Backend:** PHP sebagai server-side language.
- **Database:** MySQL atau MariaDB.

### Manfaat:
- Membantu masyarakat untuk mendapatkan informasi awal mengenai kondisi kesehatan jantung mereka.
- Mempercepat proses identifikasi gejala tanpa perlu langsung konsultasi ke dokter.
- Meningkatkan kesadaran akan pentingnya kesehatan jantung.

Sistem ini bukan pengganti konsultasi medis profesional, tetapi alat bantu untuk memberikan informasi awal sebelum pengguna berkonsultasi lebih lanjut dengan dokter ahli.

## INTALASI 
For windows

Download dan Instal aplikasi Xampp di Komputer
Copy folder spjantung, lalu paste ke folder htdocs
Aktifkan Apache dan MySQL pada Xampp
Buka browser, lalu buka alamat localhost/phpmyadmin
Buat database baru dengan nama spjantung
Import database aplikasi ke dalam database spjantung
Jalankan aplikasi dengan ketik localhost/spjantung
Login admin dengan username : admin, password : admin

For arch linux

Download dan instal xampp di AUR
jalankan xampp 
Buka browser, lalu buka alamat localhost/phpmyadmin
Buat database baru dengan nama spjantung
Import database aplikasi ke dalam database spjantung
Buka terminal dan ketikan 
~~~bash
sudo cp -r /home/yourname/Unduhan/spjantung /opt/lampp/htdocs/  #untuk memasukan ke htdoc arch linux
sudo chmod -R 755 /opt/lampp/htdocs/spjantung # folder dapat diakses oleh server
~~~
Jalankan aplikasi dengan ketik localhost/spjantung
Login admin dengan username : admin, password : admin




