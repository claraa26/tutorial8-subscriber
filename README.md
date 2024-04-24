# Nama: Clara Sista Widhiastuti
# NPM: 2206825782
# Kelas: ADPRO-A


a. what is amqp? </br>
ampq adalah singkatan dari  Advanced Message Queuing Protocol , yaitu sebuah protokol jaringan standar dan terbuka yang digunakan untuk berkomunikasi antar aplikasi. 

b. what it means? ```guest:guest@localhost:5672``` , what is the first guest, and what is
the second guest, and what is localhost:5672 is for? </br>
```guest:guest@localhost:5672``` suatu _connection_ URI yang digunakan untuk _networing_ dan _messaging_ pada suatu sistem. </br>
First guest: username yang digunakan untuk mengautentikasi koneksi. </br>
Second guest: password digunakan untuk proses autentikasi. </br> 
localhost: IP _address_ dimana sistem tersebut dijalankan </br>
5672: nomor porst yang digunakan

## RabbitMQ
![](https://imgur.com/bKZM3Vu.png)
Producer akan terus mengirim request dan akan diletakan pad queue message. Dan consumer akan memprosesnya satu persatu secara lambat. total queue in my machine 15
![](https://imgur.com/Lqnv8OP.png)

Saya menjalankan di 3 console berbeda. Dapat dilihat bahwa data yang ditampilkan berbeda urutannya dengan sebelumnya karna subscribernya multithread, namun hal tersebut membantu meningkatkan kemampuan untuk menjalankan mutiple event
![](https://imgur.com/G3EBxdK.png) 
![](https://imgur.com/bupOodb.png)