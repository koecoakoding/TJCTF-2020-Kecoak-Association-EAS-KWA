# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association

### Login
*input image here

1. Buka login page
2. Inspect Element dan lihat bagian script 
3. Akan terdapat ``` temp=md5(password)[_0x4a84('0x2')]();if(username==_0x4a84('0x6')&&temp==_0x4a84('0x4'))alert(_0x4a84('0x0')+password+'890898}');else alert(_0x4a84('0x5'));};```
4. Pada Bagian ini dapat dilihat bahwa username merupakan `_0x4a84('0x6')` dan temp adalah `_0x4a84('0x4')` Temp sendiri merupakan password yang dapat dilihat di bagian `temp=md5(password)[_0x4a84('0x2')]`
5. Username dan password yang telah di dapat, dimasukan ke dalam console dan akan keluar 

* insert image here

6. Masukan hasil password ke md5 decoder dan akan mendapatkan inevitable
7. Masukan username dan password lalu akan muncul flag

*insert image here