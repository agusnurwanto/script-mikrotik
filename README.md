# script-mikrotik
Script best practice untuk keperluan setting mikrotik

## Catatan
- untuk menjalankan auto backup dengan menjalankan script php di index.php
- script index.php menjalankan file bash yang akan auto login ke mikrotik via FTP dan mendonwload file backup.
- selanjutnya script bash akan menjalankan phpmiler/mail.php untuk mengirim email dengan attachment file backup yang sebelumnya sudah didownload via FTP
- file sceduller sceduller_mikrotik.txt disetting di menu system > sceduller dan dijalankan setiap hari jam 2 pagi agar tidak mengganggu kustomer

Semangat dan semoga berkah
