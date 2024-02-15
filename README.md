# devuploads
**Devuploads Terminal**

Situs : [Devuploads](https://devuploads.com/)

<p>Registrasi dan Ambil API KEY :
• Registrasi di https://devuploads.com/
• Login dan Ambil API KEY
   Settings > API
• Klik Generate Jika Belum Muncul

Installasi dan Clone Repo :
Disin Saya Contohkan Menggunakan Termux di Android
(Disarankan menggunakan Termux dari Fdroid)
• Pertama Install Termux
• Lakukan update
  ```
  apt update
  apt upgrade
  pkg install nano git -y
  git clone https://github.com/donydaily/devuploads
  cd devuploads
  chmod +x upload.sh
  ```
  
• Settings API KEY
  Ambil API KEY yang telah dibuat tadi copy dan paste dibagian ini
  file_path=""
  api_key="PASTE DISINI"
  sess_id=""
  server_url=""
  Dengan Perintah Berikut
    nano upload.sh
  Simpan dengan klik CRTL+X Lalu y dan Enter
  
• Menggunakan Script
  sh upload.sh
  Lalu masukan path dimana file yang akan diupload
  Contoh : /sdcard/Donwload/MASUKAN_NAMA_FILE.txt
  Disarankan menggunakan _ atau - sebagai pengganti spasi pada nama file agar terbaca
  Tunggu sampai selesai dan akan muncul link download file yang sudah di upload tadi
