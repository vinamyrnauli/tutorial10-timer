# Tutorial 10 (TIMER)
Nama: Vina Myrnauli Abigail Siallagan<br>
NPM: 2206825776<br>
Kelas: Pemrograman Lanjut - A<br>

---
## REFLEKSI 1

###### 1.2. Understanding how it works.
![](images/1.png)  
* Fungsi *async* beroperasi secara terpisah dari fungsi utama yang memanggilnya. Ini mengindikasikan bahwa eksekusi fungsi *async* tidak tergantung pada eksekusi fungsi utama yang memanggilnya. Dikarenakan sifatnya yang asinkron, urutan *output* dari *program* dapat berubah.
* Ada kemungkinan bahwa kode di luar fungsi async dieksekusi sebelum fungsi *async* selesai, mengubah urutan *output* yang diharapkan.
* Pada saat saya melakukan `cargo run`, "hey hey" bisa muncul sebelum "howdy!" dan "done!". Ini disebabkan oleh pernyataan `println!("hey hey");` terletak di luar fungsi *async*, yang berarti akan dijalankan secara independen dari eksekusi fungsi *async*.
