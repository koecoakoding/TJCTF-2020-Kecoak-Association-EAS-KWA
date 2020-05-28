# Write Up TJCTF 
## Fachrizal Rahmat Hidayat (05311840000005)
## Kecoak Association


### Titanic
1. Lihat kunci pertama, dan kita akan mengetahui jika clue nya ada di dialog dalam titanic
2. Kata yang terdapat dalam dialog titanic merupakan kata yang terdapat character khusus karena jika merupakan kata biasa maka bia di md5 decoder
3. Lalu ada yang bertanya di discord kepada penyelenggaranya,  `apakah kata yang ada ' nya juga termasuk?`. Dari ini saya berpendapat bahwa kata yang dimaksud memiliki '
4. Dengan mencari di dalam script subtitle maka akan mendapat sebuah kata marlborough's yang jika dimasukan ke md5 hash akan sama dengan flag
5. jadi flag nya tjctf{marlborough's} 