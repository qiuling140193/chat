# Chat
Login Server : 127.0.0.1
<p>Port : 9999
<p>
Ketika Login server akan mengecek client berada diport yang benar atau tidak, 
server akan melakukan synchronized untuk mengirim dan pesan dan menghapus client yg logout
<p>Synchronized adalah modifier yang digunakan dalam aplikasi Java berbasis thread. Modifier ini menspesifikasikan bahwa method merupakan thread safe. Artinya bahwa hanya ada satu jalur eksekusi pada method yang menggunakan modifier jenis ini dan memaksa thread thread lain menunggu giliran. 
<p>Server akan mengambil client kemudia dilist didalam table list.
<p>Server akan mengecek id (id mesti unique)
<p>Pertama clinet login akan masuk ke chat group, jika ingin private chat maka client click client yang ada di table list, makan akan tampil diaglog baru untuk private chat, penggunaka juga masih tetap bisa chat digroup, dan bisa menggunakan beberapa private chat dalam waktu bersamaan.
