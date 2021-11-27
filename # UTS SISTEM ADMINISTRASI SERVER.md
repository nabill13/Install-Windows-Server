# **# UTS SISTEM ADMINISTRASI SERVER**

#### ***Menginstall Windows Server***

Sebelum menginstall windows server, kita perlu mendownload filenya terlebih dahulu.

file bisa di akses melalui link berikut : 



#### ***Langkah-langkah Menginstall Windows Server***

1. Membuka VirtualBox, dan klik ikon *New* , Kemudian Beri nama pada kolom nama dengan *Windows Server*, lalu pada bagian versi pilih lalu *other Windows 64 bit* , lalu bisa klik *next* 

   ![1.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/1.PNG?raw=true)

   

2. Atur RAM yang akan disediakan untuk Windows Server ini, disini saya atur menjadi 2048 lalu bisa klik *next* 

   ![2.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/2.PNG?raw=true) 

   

3. Langkah selanjutnya yaitu memilih Hard disk, disini pilih yang *Create a virtual hard disk now* kemudian klik next

   ![3.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/3.PNG?raw=true) 

   

4. kemudian untuk Hard disk tipe nya pilih *VDI (VirtualBox Disk Image)* 

   ![4.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/4.PNG?raw=true)

   

5. lalu penyimpanan pada physical hard disk, pilih *Dynamically allocated* 

   ![5.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/5.PNG?raw=true)

   

6. langkah selanjutnya yaitu atur lokasi dan ukuran maksimal file, disini saya mengatur dengan *20,00 GB*

   ![6.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/6.PNG?raw=true)

   

7. Selanjutnya jalankan Windows Server, maka akan muncul gambar seperti di bawah ini, klik *icon folder* lalu -> *add*, kemudian pilih file Windows Server, lalu klik choose 

   ![8.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/8.PNG?raw=true)

9.  Maka akan muncul seperti gambar dibawah ini, bisa di next atau jika mau mengatur  time dan currency format nya juga boleh 

   ![10.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/10.PNG?raw=true)

10. klik *Install now*

    ![11.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/11.PNG?raw=true)

11. lalu akan muncul seperti gambar dibawah ini, pilih *Windows Server 2020 Standard Evaluation (Desktop Experience), lalu bisa klik next

    ![12.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/12.PNG?raw=true)

12. lalu centang terlebih dahulu, kemudian klik **next**

    ![13.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/13.PNG?raw=true)

12. kemudian bisa klik **Custom**

    ![14.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/14.PNG?raw=true)

13. klik next

    ![15.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/15.PNG?raw=true)

14. lalu tunggu hingga selesai menginstall semua

    ![16.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/16.PNG?raw=true)

15. lalu biarkan sistem merestart VirtualBox 

    ![17 (restart vb).PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/17%20(restart%20vb).PNG?raw=true)

16. Maka akan muncul logo dari Windows

    ![18(memulai windows server).PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/18(memulai%20windows%20server).PNG?raw=true)

17. lalu kita diharuskan membuat akun, username secara default, dan kita diharuskan membuat password. password terdiri dari huruf, angka dan karakter.![19 (masukin password baru ).PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/19%20(masukin%20password%20baru%20).PNG?raw=true)

    

18. maka akan muncul tampilan seperti gambar di bawah ini.

    ![20 (setelah membuat password).PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/20%20(setelah%20membuat%20password).PNG?raw=true)

19. klik *input* -> *keyboard* -> Insert Ctrl + Alt + Del, lalu masukan password yang sudah di buat pada langkah sebelumnya dan tunggu untuk proses konfigurasi

    ![22 (masukan password yang telah dibuat).PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/22%20(masukan%20password%20yang%20telah%20dibuat).PNG?raw=true)

20. buka *file explorer* -> CD Drive (D)VirtualBox Guest Additions-> Install aplikasi 

    "VBoxWindowsAdditions"

    ![24.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/24.PNG?raw=true)

21. Pilih *file location* -> next

    ![25.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/25.PNG?raw=true)

    lalu klik **install**

    ![26.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/26.PNG?raw=true)

    ![28.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/28.PNG?raw=true)

22. Centang checkbox dan pilih install

    ![26.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/26.PNG?raw=true)

    proses install

    ![27.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/27.PNG?raw=true)

23. Jika PC tidak akan digunakan maka klik **reboot now** -> finish

    ![29.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/29.PNG?raw=true)

24. lalu akan kembali ke halaman home, klik *input->keyboard->insert Ctrl+Alt+Del* , masukan password anda

    ![31.png](https://github.com/nabill13/Install-Windows-Server/blob/main/31.png?raw=true)

25. tampilan berhasil install windows server 2022

    ![32.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/32.PNG?raw=true)

#### ***INSTALASI ACTIVE DIRECTORY DOMAIN SERVICE*** 

1. Buka Command Prompt lalu cek -> ipconfig

   ![33.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/33.PNG?raw=true)

2. Buka Server Manager pada windows

   ![34.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/34.PNG?raw=true)

3. Klik Menu *manage* -> *Add Roles and Features*

   ![35.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/35.PNG?raw=true)

4. akan muncul gambar seperti di bawah ini lalu klik next 

   ![36.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/36.PNG?raw=true)

5. kemudian karena kita akan menggunakan aturan default dari sistem *Role-based or feature based installation* , lalu klik **Next**

   ![37.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/37.PNG?raw=true)

6. Klik *select a server from the server  pool* , kemudian akan ada tampilan default penyimpanan yang akan digunakan, lalu **Next**

   ![38.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/38.PNG?raw=true)

7. Pada Server Roles, pilih checkbox *Active Directory Domain Services*

   ![39.png](https://github.com/nabill13/Install-Windows-Server/blob/main/39.png?raw=true)

8. kemudian muncul tampilan seperti gambar dibawah ini, centang *Include  Management Tools* lalu -> *Add  Feature* lalu **Next**

   ![40.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/40.PNG?raw=true)

9. kemudian muncul tampilan seperti gambar dibawah ini, klik **Next**

   ![41.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/41.PNG?raw=true)

10. akan muncul gambar Active Directory klik **Next**

    ![43.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/43.PNG?raw=true)

11. **INSTALL**

    ![44.PNG](https://github.com/nabill13/Install-Windows-Server/blob/main/44.PNG?raw=true)

12. Selesai Instalasi, kita bisa mengabaikan pesan pada tampilan 

    ## SELESAI 