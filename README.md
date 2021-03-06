# Cara Install XAMPP di Linux Ubuntu 20.10
1. Langkah pertama download dulu xampp [Di Sini](https://www.apachefriends.org/download.html) pilih XAMPP For Linux dan pilih versinya
2. Langkah kedua buka terimal dengan perintah ```Ctrl+Alt+T```
3. Langkah ketiga Masuk ke directory Downloads dengan peritah ```cd Downloads/```
4. Langkah keempat cek xampp hasil downloads dengan perintah ```ls```
5. Langkah kelima ketikan perintah ```chmod +x xampp-linux-x64-<ubahdenganversiygdidownloads>-0-installer.run```
6. Langkah keenam ketikan perintah ```sudo  ./xampp-linux-x64-<ubahdenganversiygdidownloads>-0-installer.run```
7. Langkah ketujun akan muncul tampilan windows installer xampp tinggal tekan tombol next dst..
8. Selesai..
# Cara untuk menjalankan XAMPP di Linux
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ``` sudo /opt/lampp/lampp start ```
3. Local Server sudah bisa digunakan
# Cara untuk menghentikan XAMPP di Linux
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ``` sudo /opt/lampp/lampp stop ```
3. Finish
# Cara memberikan hak akses di htdocs untuk membuat project/folder baru
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ```cd /opt/lampp``` 
3. Langkah ketiga ketikan perintah ```sudo su``` 
4. Jika dimintai password masukkan password laptop anda
5. Langkah terakhir ketikan perintah ```chmod 777 -R htdocs/``` 

Lihat [Video](https://www.youtube.com/watch?v=Y-Km-IT8GkM)

# Jika http://localhost/phpmyadmin not found pada Linux
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ```sudo ln -s /usr/share/phpmyadmin /var/www/html/phpmyadmin``` 
3. Langkah ketiga ketikan perintah ```sudo /etc/init.d/apache2 reload``` atau ```sudo /opt/lampp/lampp start```
4. Jika dimintai password masukkan password laptop anda
5. Langkah terakhir buka lagi http://localhost/phpmyadmin pada web browser

Lihat Sumber [Video](https://www.youtube.com/watch?v=AkkL2QRJjHw)

# Menginstal Visual Studio Code dengan Paket Snap 
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ```sudo snap install --classic code``` 
3. Finish

Lihat [Sumber Install VSC](https://linuxize.com/post/how-to-install-visual-studio-code-on-ubuntu-20-04/)

# Mengatasi masalah npm not found
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ```sudo apt-get install npm``` 
3. Finish

Lihat [Sumber npm Not Found](https://stackoverflow.com/questions/31472755/sudo-npm-command-not-found)

# Menginstal Postman dengan Paket Snap 
1. Langkah pertama buka terminal dengan perintah ```Ctrl+Alt+T``` 
2. Langkah kedua ketikan perintah ```sudo snap install postman``` 
3. Finish

Lihat [Sumber Install Postman](https://www.linuxid.net/25018/install-dan-konfigurasi-postman-di-ubuntu-18-04/)
