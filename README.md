CARA MEMBUAT REPOSITORY LOCAL DAN REPOSITORY PADA GITHUB SERTA CARA MEMBUAT FILE README.md

Yang kalian butuhkan :
1. Akun GitHub
2. Software atau Program Git

DAFTAR AKUN GitHub

  1. Buat akun GitHub dengan cara membuka laman https://github.com
  2. Masukan Username, Email dan Password yang akan kalian gunakan pada akun GitHub kalian.
  ![pic1](https://user-images.githubusercontent.com/56986904/67551402-fad1f500-f732-11e9-80b7-cc959cf4b0f9.png)
  3. Lalu buka email yang anda masukan tadi dan lakukan verifikasi.
  ![pic2](https://user-images.githubusercontent.com/56986904/67551659-a2e7be00-f733-11e9-8bed-f2625c4783d7.png)
  4. Setelah melakukan verifikasi, kalian akan di alihkan ke laman GitHub untuk selanjutnya membuat Repository baru, lalu masukan
     nama Repository kalian dan klik "create repository".
  ![make repo](https://user-images.githubusercontent.com/56971806/67517227-5321dc00-f6cc-11e9-9170-86c8344926d9.png)
  5. Seperti inilah tampilan Repository baru.
  ![make repo finish](https://user-images.githubusercontent.com/56971806/67517300-85cbd480-f6cc-11e9-8e5f-39ee7c1c6664.png)
  
DOWNLOAD SOFTWARE Git

  1. Untuk mendownload software Git kita harus masuk ke laman https://git-scm.com
  ![download git](https://user-images.githubusercontent.com/56971806/67517048-ee668180-f6cb-11e9-8f7e-999a25a197c2.png)
  2. Pilih download dan sesuaikan dengan operating system dan spesifikasi laptop atau komputer kalian.
  ![git download](https://user-images.githubusercontent.com/56971806/67517709-61242c80-f6cd-11e9-8023-c3e408500952.png)
  3. Lakukan instalasi Git pada laptop atau komputer kalian.
  ![install git](https://user-images.githubusercontent.com/56971806/67518320-c593bb80-f6ce-11e9-8bec-2d7f431b16ec.png)
  4. Pastikan software atau program Git sudah terinstall 100%.
  ![git install complete](https://user-images.githubusercontent.com/56971806/67518391-ebb95b80-f6ce-11e9-97ed-37038b021405.png)
  5. Pastikan program Git sudah dapat di gunakan di perangkat kalian dengan cara membuka Command Prompt lalu ketik "git
  --version"
     jika sudah muncul berarti Git sudah dapat di gunakan.
  ![git verio](https://user-images.githubusercontent.com/56971806/67518796-acd7d580-f6cf-11e9-9170-92d6fd646554.png)
  
 MEMBUAT REPOSITORY LOKAL DAN MEMBUAT FILE README.md
  
  1. Buatlah "folder" baru di directory kalian lalu "klik kanan" pada folder tersebut dan pilih "Git Bash Here"
  ![git bash](https://user-images.githubusercontent.com/56971806/67519128-620a8d80-f6d0-11e9-80e8-53ea3f21054c.png)
  2. Lalu konfigurasi dengan menggunakan perintah "git config --global user.name "nama_user" dan "git config --global user.email
  "email_user"
  ![1](https://user-images.githubusercontent.com/56971806/67521014-37223880-f6d4-11e9-95f7-d6d3eb2ed0b0.png)
  3. Buatlah direktori baru dengan menggunakan perintah "mkdir latihan01" dan pindah ke direktori tersebut dengan menggunakan
  perintah "cd latihan01"
  ![2](https://user-images.githubusercontent.com/56971806/67521103-646ee680-f6d4-11e9-941c-c82c1177b6e5.png)
  4. Buat file kosong berformat .git dengan cara menjalankan perintah "git init".
  ![3](https://user-images.githubusercontent.com/56971806/67521181-8e280d80-f6d4-11e9-9807-632e3635f48e.png)
  5. Buat file README.md dengan menggunakan perintah echo "#latihanphyton1" >> README.md"
  ![4](https://user-images.githubusercontent.com/56971806/67521300-d1827c00-f6d4-11e9-81fc-a8be66a7167c.png)
  6.Untuk melihat File, gunakan perintah ls -l
  ![5](https://user-images.githubusercontent.com/56971806/67521430-11496380-f6d5-11e9-9ad5-f9d082e5e338.png)
  7.Memasukan File README.md ke repository lokal dengan menggunakan perintah "git add README.md"
  ![6](https://user-images.githubusercontent.com/56971806/67521586-638a8480-f6d5-11e9-832d-cd32e5971ff5.png)
  8.Simpan perubahan kedalam database repository dengan menggunakan perintah "git commit -m"
  ![7](https://user-images.githubusercontent.com/56971806/67521755-af3d2e00-f6d5-11e9-9537-630631ec559a.png)
  9.Masuk ke laman GitHub dan buka URL yang sudah di buat di repository GitHub, gunakan perintah "git remote add origin [url]", contoh: git remote add origin https://github.com/alfinabdilah/latihanPhyton.git
  ![9](https://user-images.githubusercontent.com/56971806/67548382-e3dbd480-f72b-11e9-9f75-3e2a8ad0e356.png)
  10.Kirim perubahan local repository ke GitHub dengan menggunakan perintah "git push -u origin master"
  ![10](https://user-images.githubusercontent.com/56971806/67548383-e4746b00-f72b-11e9-9d30-51172eed0848.png)
  11.Cek kembali repository di laman GitHub.
