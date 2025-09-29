# Lab2Web

# Membuat dokumen HTML
Menggunakan < !DOCTYPE > untuk memberi tahu browser bahwa dokumen yang akan dibuat menggunakan HTML, kalo < html > adalah elemen utama yang membungkus seluruh halaman, < head > itu berisi informasi tentang halaman seperti judul, link CSS, dan metadata. title yaitu untuk menambahkan judul
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/8838f69a-7068-4944-a563-53b790f25282" />
<br>
<br>
# Mendeklarasikan CSS
- body: menentukan jenis huruf utama untuk seluruh halaman menggunakan font open sans
- header: memberi bagian atas halaman dengan tinggi minimal 80px dan garis bawah tipis berwarna biru muda
- h1: mengatur tampilan elemen judul utama Berukuran 24px (besar), Berwarna biru tua, Berada di tengah (center), Memiliki jarak ruang di sekelilingnya (padding).
- h1 i: Mengubah warna teks miring < i > di dalam judul < h1 > menjadi abu-abu gelap.
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/10de4ac4-7647-4a76-9e11-1bbdb5bdde2c" />
<br>
<br>

# Menambahkan Inline CSS
Menambahkan deklarasi inline CSS pada tag < p >
- text-align: center;: Membuat teks di dalam paragraf tersebut menjadi rata tengah (center).
- color: #ccd8e4;: Mengubah warna teks paragraf menjadi biru muda/abu-abu terang (#ccd8e4).
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/58ba01e2-4349-4ef1-9e10-379dec1db2a1" />
<br>
<br>

# Membuat CSS Eksternal
1. Pengaturan Navigasi (nav)
- background: #20A759;: Memberi latar belakang navigasi warna hijau tua.
- color: #fff;: Menetapkan warna teks utama di navigasi menjadi putih.
- padding: 10px;: Memberi jarak kosong 10px di sekeliling konten navigasi.

2. Pengaturan Tautan di Navigasi (nav a)
- color: #fff;: Membuat warna teks tautan tetap putih.
- text-decoration: none;: Menghilangkan garis bawah pada tautan.
- padding: 10px 20px;: Memberi jarak kosong 10px di atas/bawah dan 20px di kiri/kanan setiap tautan, membuatnya terlihat seperti tombol.

3. Efek Interaksi (nav .active, nav a:hover)
- nav .active, nav a:hover { ... }: Mengatur tampilan ketika tautan aktif (menggunakan kelas .active) atau ketika kursor diarahkan ke tautan (:hover).
- background: #0B6B3A;: Mengubah latar belakang tautan menjadi warna hijau yang lebih gelap saat kursor diarahkan atau saat tautan sedang aktif.

4. Menggunakan (Tag <link>)
Untuk menerapkan tag link, file HTML harus "memanggil" file CSS tersebut menggunakan tag < link > di dalam bagian < head >:

< link rel="stylesheet" href="style_eksternal.css" ... >: Ini memberitahu browser untuk mengambil dan menggunakan semua aturan gaya dari file style_eksternal.css pada halaman HTML tersebut.
<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/6f8acfdf-d84c-401d-811c-32fae2f0d3dc" />
<br>
<br>

# Menambahkan CSS Selector
1. ID Selector ( #intro )
- Mengatur area konten utama (ID: intro).
- Memberi latar belakang biru, garis tepi hijau, dan tinggi minimum 100px.
- Mengatur judul < h1 > di dalamnya agar rata kiri dan berwarna putih.

2. Class Selector ( .button )
- Membuat gaya dasar untuk tombol.
- Memberi padding (ruang dalam), latar belakang abu-abu, teks putih, dan menghilangkan garis bawah tautan.

3. Modifikasi Class ( .btn-primary )
- Kelas tambahan untuk membuat tombol "utama".
- Hanya mengganti warna latar belakang tombol menjadi merah (menimpa warna abu-abu standar).
- <img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/b77d71fe-0ecf-438e-93c9-23f7a57d9f10" />
