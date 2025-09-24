---
profileName: Main
postId: 66
postType: post
categories:
  - 89
---
# Konsep Berpikir Komputasional
erpikir Komputasional** -> Menyelesaikan masalah dengan efisien dan optimal.
## AADP
A -> Abstraksi -> Fokus pada hal-hal esensial dan emengesampingkan hal-hal yang tidak relevan. Tujuannya adalah optimalisasi dan efisiensi.
A -> Algoritma -> Merancang langkah-langkah runut dari suatu penyelesaian masalah se-efisien dan optimal mungkin. Harus memiliki awal dan akhir.
D -> Dekomposisi -> Memecah masalah kompleks ke masalah kecil yang bisa dikelola dan dikerjakan bertahap. "Divide and Conquer".
P -> Pattern Recognition -> Melihat dan mengenali pola dari masalah serupa yang dapat digunakan untuk menyelesaikan masalah lainnya yang mirip.
# Struktur Data
**Data** -> Fakta yang belum diolah dan dapat diinterpretasikan sebagai informasi.
**Struktur Data** -> Cara mengorganisi data dengan rapi dan terurut sehingga mudah dipahami.

Dalam istilah [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **struktur data** adalah cara menyimpan dan mengatur data secara terstruktur pada sistem komputer atau [pangkalan data](https://id.wikipedia.org/wiki/Pangkalan_data "Pangkalan data") (_database_) sehingga lebih mudah diakses. Secara teknis, data dalam bentuk angka, huruf, simbol, dan lainnya ini diletakkan dalam kolom-kolom dan susunan tertentu. Contoh struktur data dapat dilihat pada berkas-berkas [lembar sebar](https://id.wikipedia.org/wiki/Lembar_sebar "Lembar sebar") (_spreadsheet_), pangkalan data, [pengolah kata](https://id.wikipedia.org/wiki/Pengolah_kata "Pengolah kata"), [citra yang dipampat](https://id.wikipedia.org/wiki/Pemampatan_citra "Pemampatan citra") (_compressed image_), dan pemampatan berkas dengan teknik tertentu yang memanfaatkan struktur data.

Dalam teknik [pemrograman](https://id.wikipedia.org/wiki/Pemrograman "Pemrograman"), struktur data berarti tata letak data yang berisi kolom-kolom data, baik itu kolom yang terlihat oleh pengguna ataupun kolom yang hanya digunakan untuk keperluan pemrograman yang tidak terlihat oleh pengguna. Setiap baris dari kumpulan kolom-kolom tersebut dinamakan catatan (_[record](https://id.wikipedia.org/wiki/Record "Record")_). Lebar kolom untuk data dapat berubah dan bervariasi. Ada kolom yang lebarnya berubah secara dinamis sesuai masukan dari pengguna, dan juga ada kolom yang lebarnya tetap. Dengan sifatnya ini, sebuah struktur data dapat diterapkan untuk pengolahan basis data (misalnya untuk keperluan data keuangan) atau untuk pengolah kata yang kolomnya berubah secara dinamis.

## Kegunaan
Struktur data adalah basis dari [tipe data abstrak](https://id.wikipedia.org/wiki/Tipe_data_abstrak "Tipe data abstrak"). Tipe data abstrak mendefinisikan bentuk logis dari sebuah tipe data, sementara struktur data mengimplementasikan bentuk fisik dari tipe data tersebut.

Masing-masing jenis struktur data yang berbeda cocok untuk penggunaan-penggunaan yang berbeda, dan beberapa jenis memang dispesialisakian untuk tugas tertentu. Contohnya, [basis data relasional](https://id.wikipedia.org/wiki/Basis_data_relasional "Basis data relasional") biasanya menggunakan indeks B-tree untuk data retrieval, sedangkan implementasi [kompilator](https://id.wikipedia.org/wiki/Kompilator "Kompilator") biasanya menggunakan tabel hash untuk menemukan pengidentifikasi.

Struktur data memberikan cara mengelola data yang banyak secara efisien untuk berbagai penggunaan, misalnya untuk [basis data](https://id.wikipedia.org/wiki/Basis_data "Basis data") yang besar dan layanan pengindeksan internet. Biasanya, struktur data yang efisien adalah kunci untuk mendesain [algoritme](https://id.wikipedia.org/wiki/Algoritme "Algoritme") yang efisien. Beberapa metode desain formal dan [bahasa pemrograman](https://id.wikipedia.org/wiki/Bahasa_pemrograman "Bahasa pemrograman") menekankan struktur data, bukan pada algoritma, sebagai faktor kunci dalam mengatur desain [perangkat lunak](https://id.wikipedia.org/wiki/Perangkat_lunak "Perangkat lunak"). Struktur data bisa digunakan untuk mengatur penyimpanan dan pengambilan informasi yang disimpan baik di dalam [memori utama](https://id.wikipedia.org/wiki/Penyimpanan_data_komputer#Penyimpanan_primer "Penyimpanan data komputer") maupun [memori sekunder](https://id.wikipedia.org/wiki/Penyimpanan_data_komputer#Penyimpanan_sekunder "Penyimpanan data komputer").
## Jenis-Jenis
## Array/Larik
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **larik** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _array_) adalah suatu [tipe data](https://id.wikipedia.org/wiki/Tipe_data "Tipe data") terstruktur yang dapat menyimpan banyak [data](https://id.wikipedia.org/wiki/Data "Data") dengan suatu nama (homogen) yang sama dan menempati tempat di [memori](https://id.wikipedia.org/wiki/Memori "Memori") yang berurutan ([kontigu](https://id.wikipedia.org/w/index.php?title=Kontigu&action=edit&redlink=1 "Kontigu (halaman belum tersedia)")) serta bertipe data sama pula.

Larik dapat diakses berdasarkan [indeksnya](https://id.wikipedia.org/wiki/Indeks "Indeks"). Indeks larik umumnya dimulai dari 0 dan ada pula yang dimulai dari angka bukan 0. Pengaksesan larik biasanya dibuat dengan menggunakan perulangan (_looping_).
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQMGHSeFjlTyWAKUgrvEseMzSfdjSdkH4X1RQ&s)

## Linked List
**Senarai berantai** atau **daftar bertaut** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _linked list_) dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer") merupakan sebuah [struktur data](https://id.wikipedia.org/wiki/Struktur_data "Struktur data") yang digunakan untuk menyimpan sejumlah objek data biasanya secara terurut sehingga memungkinkan penambahan, pengurangan, dan pencarian atas [unsur](https://id.wikipedia.org/wiki/Elemen "Elemen") data yang tersimpan dalam senarai dilakukan secara lebih efektif. Pada praktiknya sebuah struktur data memiliki unsur yang digunakan untuk saling menyimpan rujukan antara satu dengan lainnya sehingga membentuk sebuah senarai abstrak, tiap-tiap unsur yang terdapat pada senarai abstrak ini sering kali disebut sebagai _node_. karena mekanisme rujukan yang saling terkait inilah disebut sebagai senarai berantai.

[![](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Singly-linked-list.svg/408px-Singly-linked-list.svg.png)](https://id.wikipedia.org/wiki/Berkas:Singly-linked-list.svg)  
_Sebuah senarai berantai dengan tiap-tiap node yang terdiri atas dua unsur, data integer, dan unsur rujukan ke node berikutnya_

Senarai berantai merupakan bentuk struktur data paling umum dan sederhana yang banyak digunakan untuk mengimplementasikan model struktur data lainnya, termasuk antrian, _stack_, ataupun [larik](https://id.wikipedia.org/wiki/Array "Array") asosiatif.
## Stack
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **tumpukan** ([bahasa Inggris](https://id.wikipedia.org/wiki/Bahasa_Inggris "Bahasa Inggris"): _stack_) merupakan sebuah koleksi objek yang menggunakan prinsip _**LIFO**_ (_**Last In First Out**_), yaitu data yang terakhir kali dimasukkan akan pertama kali keluar dari tumpukan tersebut. Operasi untuk memasukkan data biasa disebut _push_ dan operasi untuk mengeluarkan biasanya disebut _pop_. Tumpukan dapat diimplementasikan sebagai [senarai berantai](https://id.wikipedia.org/wiki/Senarai_berantai "Senarai berantai") atau [larik](https://id.wikipedia.org/wiki/Larik "Larik"). Tumpukan tergolong [struktur data linear](https://id.wikipedia.org/w/index.php?title=Struktur_data_linear&action=edit&redlink=1 "Struktur data linear (halaman belum tersedia)") dan operasi _push_ dan _pop_ hanya bisa dilakukan di satu ujung struktur yang biasa disebut _top_ dari tumpukan. Untuk melihat data yang ada di top tanpa mengeluarkannya, biasanya dilakukan menggunakan operasi _peek_.
![](https://cdn.programiz.com/sites/tutorial2program/files/stack.png)

## Queue
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), **antrean** adalah koleksi dari data-data yang memiliki urutan dan hanya bisa diubah dengan menambahkan data di satu ujung dan mengeluarkan data di ujung lainnya. Biasanya, ujung di mana elemen bisa ditambahkan disebut _back_, _tail_, atau _rear_ dari antrean sementara ujung di mana elemen bisa dikeluarkan disebut _head_ atau _front_ dari antrean, mirip dengan kata-kata yang digunakan apabila orang-orang berbaris dalam antrean.

Operasi menambahkan elemen ke _rear_ dari antrean biasanya disebut _enqueue_ sementara operasi mengeluarkan elemen dari _fron_ biasanya disebut _dequeue_. Operasi-operasi lain yang biasa dilakukan di antaranya adalah operasi _peek_ atau _front_ yang digunakan untuk melihat elemen terdepan dari antrean tanpa mengeluarkannya.

Operasi-operasi yang mendefinisikan antrean membuatnya tergolong sebagai [struktur data _first-in-first-out_ (FIFO)](https://id.wikipedia.org/wiki/FIFO "FIFO"). Karena memenuhi struktur data FIFO, elemen pertama yang dimasukkan ke antrean akan menjadi yang pertama dikeluarkan. Antrean juga merupakan contoh [struktur data linear](https://id.wikipedia.org/w/index.php?title=Struktur_data_linear&action=edit&redlink=1 "Struktur data linear (halaman belum tersedia)"). Antrean biasa digunakan dalam program komputer, biasanya diimplementasikan menggunakan _[circular buffer](https://id.wikipedia.org/w/index.php?title=Circular_buffer&action=edit&redlink=1 "Circular buffer (halaman belum tersedia)")_ dan [senarai berantai](https://id.wikipedia.org/wiki/Senarai_berantai "Senarai berantai").

Antrean biasa digunakan dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), [transportasi](https://id.wikipedia.org/wiki/Transportasi "Transportasi"), dan [riset operasi](https://id.wikipedia.org/wiki/Riset_operasi "Riset operasi") di mana terdapat entitas-entitas seperti data, objek, orang, atau kejadian yang perlu disimpan untuk diproses kemudian. Dalam konteks tersebut, antrean melakukan pekerjaan dari [_buffer_](https://id.wikipedia.org/w/index.php?title=Buffer_\(ilmu_komputer\)&action=edit&redlink=1 "Buffer (ilmu komputer) (halaman belum tersedia)"). Penggunaan lain dari antrean adalah dalam implementasi _[breadth-first search](https://id.wikipedia.org/w/index.php?title=Breadth-first_search&action=edit&redlink=1 "Breadth-first search (halaman belum tersedia)")_.
![](https://www.visiontron.com/wp-content/uploads/lines-02-1.png)
## Binary Search Tree
Dalam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), sebuah **pohon pencarian biner** (PPB) atau **pohon biner terurut** adalah sebuah [pohon biner](https://id.wikipedia.org/wiki/Pohon_biner "Pohon biner") yang memiliki sifat-sifat berikut:

- Setiap [simpul](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Simpul_\(node\) "Pohon (struktur data)") (_node_) memiliki sebuah nilai.
- Sebuah [susunan total](https://id.wikipedia.org/w/index.php?title=Susunan_total&action=edit&redlink=1 "Susunan total (halaman belum tersedia)") ditentukan dalam nilai ini.
- [Sub pohon](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Sub_pohon_\(Subtrees\) "Pohon (struktur data)") (_subtree_) kiri dari sebuah simpul hanya memuat nilai lebih kecil dari nilai simpul.
- Sub pohon kanan dari sebuah simpul hanya memuat nilai lebih besar atau sama dengan nilai dari simpul.

Kelebihan utama dari pohon pencarian biner adalah keterkaitannya dengan [algoritme pengurutan](https://id.wikipedia.org/w/index.php?title=Algoritme_pengurutan&action=edit&redlink=1 "Algoritme pengurutan (halaman belum tersedia)") dan [algoritme pencarian](https://id.wikipedia.org/wiki/Algoritme_pencarian "Algoritme pencarian") yang dapat lebih efisien, seperti _[in-order traversal](https://id.wikipedia.org/w/index.php?title=In-order_traversal&action=edit&redlink=1 "In-order traversal (halaman belum tersedia)")_.

Pohon pencarian biner adalah sebuah struktur data dasar yang digunakan untuk membentuk struktur data yang lebih abstrak seperti [set](https://id.wikipedia.org/w/index.php?title=Struktur_data_set&action=edit&redlink=1 "Struktur data set (halaman belum tersedia)"), [multiset](https://id.wikipedia.org/w/index.php?title=Multiset&action=edit&redlink=1 "Multiset (halaman belum tersedia)"), dan [array asosiatif](https://id.wikipedia.org/w/index.php?title=Array_asosiatif&action=edit&redlink=1 "Array asosiatif (halaman belum tersedia)").

Jika PPB memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah multiset. Pohon jenis ini menggunakan ketaksamaan longgar (_non-strict inequalities_), sehingga semua yang berada di subpohon bagian kiri dari sebuah node adalah lebih kecil atau sama dengan nilai dari node, dan semua yang berada di subpohon bagian kanan dari node adalah lebih besar atau sama dengan nilai dari node.

Jika PPB tidak memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah set dengan nilai-nilai unik, sama seperti set pada matematika (himpunan). Pohon tanpa nilai-nilai duplikat menggunakan ketaksamaan kaku (_strict inequalities_), artinya subpohon kiri dari sebuah node hanya memuat node-node dengan nilai yang lebih kecil dari nilai node, dan subpohon kanan hanya memuat nilai-nilai yang lebih besar.

Beberapa definisi PPB menggunakan sebuah ketaksamaan longgar hanya pada satu sisi, sehingga nilai-nilai duplikat diperkenankan. Walaupun demikian, definisi-definisi PPB tersebut membatasi dengan baik bagaiman sebuah pohon dengan banyak nilai duplikat dapat diseimbangkan.
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR18UBQzzwUOJCf8-7wlSBoLs_54mtp_BK6MQ&s)
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTOONoimcO2S5jqRwDOQUox6FvdCj6X7_TICQ&s)

### Mekanisme
#### Pencarian

Pencarian sebuah nilai tertentu pada pohon biner adalah sebuah proses yang dapat dilakukan secara rekursif karena nilai-nilai yang disimpan adalah terurut. Pencarian dimulai dengan memeriksa akar (_root_). Jika nilai yang dicari sama dengan akar, maka nilai ditemukan. Jika nilai yang dicari kurang dari akar, maka pencarian dilakukan terhadap subpohon kiri, sehingga kita secara rekursif mencari subpohon kiri dengan cara yang sama. Jika nilai yang dicari lebih besar dari akar, maka pencarian dilakukan terhadap subpohon kanan sehingga kita secara rekursif mencari subpohon kanan dengan cara yang sama. Jika kita mencapai sebuah ujung (_leaf_) dan belum menemukan yang dicari, maka nilai tersebut tidak ada dalam pohon. Sebuah pembandingan dapat dibuat dengan [pencarian biner](https://id.wikipedia.org/wiki/Pencarian_biner "Pencarian biner"), yang beroperasi hampir mirip degan pengaksesan acak pada sebuah array.
#### Penyisipan

Penyisipan dimulai sebagaimana sebuah pencarian dilakukan. Jika akar tidak sama dengan nilai sisipan, kita mencari subpohon kiri atau kanan seperti di atas. Pada suatu saat kita akan mencapai sebuah node luar dan menambahkan nilai sisipan sebagai anak kiri atau anak kanan, bergantung pada nilai node. Dengan kata lain, kita memeriksa akar dan secara rekursif menyisipkan node yang baru ke subpohon kiri jika nilai yang baru lebih kecil atau sama dengan akar, atau menyisipkan ke subpohon kanan jika nilai yang baru lebih besar dari root.
#### Penghapusan

Ada kasus-kasus yang mesti diperhatikan:

- **Penghapusan sebuah ujung:** Penghapusan sebuah node tanpa anak adalah mudah, cukup menghilangkanya dari pohon.
- **Penghapusan sebuah node dengan satu anak:** Menghapusnya dan mengganti dengan anaknya.
- **Penghapusan sebuah node dengan dua anak:** Misalkan node yang akan dihapus adalah _N_. Kita ganti nilai dari N dengan suksesor _in-order_ (anak terkiri dari subpohon kanan) atau dengan predesesor _in-order_ (anak terkanan dari subpohon kiri).
### Graph
Graph adalah jenis [struktur data](https://www.trivusi.web.id/2022/06/mengenal-struktur-data.html) umum yang susunan datanya tidak berdekatan satu sama lain (non-linier). Graph terdiri dari kumpulan simpul berhingga untuk menyimpan data dan antara dua buah simpul terdapat hubungan saling keterkaitan.

Simpul pada graph disebut dengan **verteks (V)**, sedangkan sisi yang menghubungkan antar verteks disebut **edge (E)**. Pasangan (x,y) disebut sebagai edge, yang menyatakan bahwa simpul x terhubung ke simpul y.

![](https://cdn.programiz.com/sites/tutorial2program/files/graph-vertices-edges_0.png)


Graph di atas terdiri atas 4 buah verteks dan 4 pasang sisi atau edge. Dengan verteks disimbolkan sebagai V, edge dilambangkan E, dan graph disimbolkan G, ilustrasi di atas dapat ditulis dalam notasi berikut:

`**V = {0, 1, 2, 3}**`

	`**E = {(0,1), (0,2), (0,3), (1,2)}**`

`**G = {V, E}**`
# Konsep Algoritma
Algoritma adalah suatu kumpulan instruksi terstruktur dan terbatas yang dapat diimplementasikan dalam bentuk program komputer untuk menyelesaikan suatu permasalahan komputasi tertentu. Algoritma merupakan bentuk dari suatu strategi atau ‘resep’ yang kalian gunakan untuk menyelesaikan suatu masalah. Algoritma lahir dari suatu proses berpikir komputasional oleh seseorang untuk menemukan solusi dari suatu permasalahan yang diberikan. Dengan demikian, berpikir komputasional merupakan keahlian yang kalian perlukan untuk dapat membuat algoritma, program, atau suatu karya informatika yang dapat digunakan dengan efektif dan efisien. 

Setelah kalian menganalisis suatu problem menggunakan teknik abstraksi dan dekomposisi lalu menyusun algoritma dengan melakukan pengenalan pola dari problem sejenis, algoritma tersebut harus direpresentasikan dalam bentuk yang dapat dipahami oleh orang lain. Selain itu, karena pada akhirnya strategi tersebut akan diubah dalam bentuk kode program, algoritma harus ditulis dalam bentuk yang terdefinisi dengan baik (well-defined) dengan jumlah langkah yang terbatas. Algoritma adalah abstraksi dari sebuah program sehingga kemampuan menuliskan algoritma dengan baik akan membantu kalian dalam membuat program yang baik dan benar.

# Search
## Linear Search
Linear Search, atau pencarian linear, adalah algoritma pencarian yang paling sederhana. Ini bekerja dengan cara memeriksa setiap elemen dalam kumpulan data secara berurutan hingga elemen yang dicari ditemukan atau sampai seluruh kumpulan data telah diperiksa.

Contoh Program:

```
def linear_search(arr, target):
for i in range(len(arr)):
if arr[i] == target:
return i
return -1
```
![](https://media.geeksforgeeks.org/wp-content/uploads/20240506105158/Linear-Search-algorithm-banner-(1).webp)
## Binary Search
![](https://media.geeksforgeeks.org/wp-content/uploads/20240506155201/binnary-search-.webp)

alam [ilmu komputer](https://id.wikipedia.org/wiki/Ilmu_komputer "Ilmu komputer"), sebuah **pohon pencarian biner** (PPB) atau **pohon biner terurut** adalah sebuah [pohon biner](https://id.wikipedia.org/wiki/Pohon_biner "Pohon biner") yang memiliki sifat-sifat berikut:

- Setiap [simpul](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Simpul_\(node\) "Pohon (struktur data)") (_node_) memiliki sebuah nilai.
- Sebuah [susunan total](https://id.wikipedia.org/w/index.php?title=Susunan_total&action=edit&redlink=1 "Susunan total (halaman belum tersedia)") ditentukan dalam nilai ini.
- [Sub pohon](https://id.wikipedia.org/wiki/Pohon_\(struktur_data\)#Sub_pohon_\(Subtrees\) "Pohon (struktur data)") (_subtree_) kiri dari sebuah simpul hanya memuat nilai lebih kecil dari nilai simpul.
- Sub pohon kanan dari sebuah simpul hanya memuat nilai lebih besar atau sama dengan nilai dari simpul.

Kelebihan utama dari pohon pencarian biner adalah keterkaitannya dengan [algoritme pengurutan](https://id.wikipedia.org/w/index.php?title=Algoritme_pengurutan&action=edit&redlink=1 "Algoritme pengurutan (halaman belum tersedia)") dan [algoritme pencarian](https://id.wikipedia.org/wiki/Algoritme_pencarian "Algoritme pencarian") yang dapat lebih efisien, seperti _[in-order traversal](https://id.wikipedia.org/w/index.php?title=In-order_traversal&action=edit&redlink=1 "In-order traversal (halaman belum tersedia)")_.

Pohon pencarian biner adalah sebuah struktur data dasar yang digunakan untuk membentuk struktur data yang lebih abstrak seperti [set](https://id.wikipedia.org/w/index.php?title=Struktur_data_set&action=edit&redlink=1 "Struktur data set (halaman belum tersedia)"), [multiset](https://id.wikipedia.org/w/index.php?title=Multiset&action=edit&redlink=1 "Multiset (halaman belum tersedia)"), dan [array asosiatif](https://id.wikipedia.org/w/index.php?title=Array_asosiatif&action=edit&redlink=1 "Array asosiatif (halaman belum tersedia)").

Jika PPB memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah multiset. Pohon jenis ini menggunakan ketaksamaan longgar (_non-strict inequalities_), sehingga semua yang berada di subpohon bagian kiri dari sebuah node adalah lebih kecil atau sama dengan nilai dari node, dan semua yang berada di subpohon bagian kanan dari node adalah lebih besar atau sama dengan nilai dari node.

Jika PPB tidak memperkenankan nilai-nilai duplikat, maka PPB merupakan sebuah set dengan nilai-nilai unik, sama seperti set pada matematika (himpunan). Pohon tanpa nilai-nilai duplikat menggunakan ketaksamaan kaku (_strict inequalities_), artinya subpohon kiri dari sebuah node hanya memuat node-node dengan nilai yang lebih kecil dari nilai node, dan subpohon kanan hanya memuat nilai-nilai yang lebih besar.

Beberapa definisi PPB menggunakan sebuah ketaksamaan longgar hanya pada satu sisi, sehingga nilai-nilai duplikat diperkenankan. Walaupun demikian, definisi-definisi PPB tersebut membatasi dengan baik bagaiman sebuah pohon dengan banyak nilai duplikat dapat diseimbangkan.
### Mekanisme
#### Pencarian

Pencarian sebuah nilai tertentu pada pohon biner adalah sebuah proses yang dapat dilakukan secara rekursif karena nilai-nilai yang disimpan adalah terurut. Pencarian dimulai dengan memeriksa akar (_root_). Jika nilai yang dicari sama dengan akar, maka nilai ditemukan. Jika nilai yang dicari kurang dari akar, maka pencarian dilakukan terhadap subpohon kiri, sehingga kita secara rekursif mencari subpohon kiri dengan cara yang sama. Jika nilai yang dicari lebih besar dari akar, maka pencarian dilakukan terhadap subpohon kanan sehingga kita secara rekursif mencari subpohon kanan dengan cara yang sama. Jika kita mencapai sebuah ujung (_leaf_) dan belum menemukan yang dicari, maka nilai tersebut tidak ada dalam pohon. Sebuah pembandingan dapat dibuat dengan [pencarian biner](https://id.wikipedia.org/wiki/Pencarian_biner "Pencarian biner"), yang beroperasi hampir mirip degan pengaksesan acak pada sebuah array.
#### Penyisipan

Penyisipan dimulai sebagaimana sebuah pencarian dilakukan. Jika akar tidak sama dengan nilai sisipan, kita mencari subpohon kiri atau kanan seperti di atas. Pada suatu saat kita akan mencapai sebuah node luar dan menambahkan nilai sisipan sebagai anak kiri atau anak kanan, bergantung pada nilai node. Dengan kata lain, kita memeriksa akar dan secara rekursif menyisipkan node yang baru ke subpohon kiri jika nilai yang baru lebih kecil atau sama dengan akar, atau menyisipkan ke subpohon kanan jika nilai yang baru lebih besar dari root.
#### Penghapusan

Ada kasus-kasus yang mesti diperhatikan:

- **Penghapusan sebuah ujung:** Penghapusan sebuah node tanpa anak adalah mudah, cukup menghilangkanya dari pohon.
- **Penghapusan sebuah node dengan satu anak:** Menghapusnya dan mengganti dengan anaknya.
- **Penghapusan sebuah node dengan dua anak:** Misalkan node yang akan dihapus adalah _N_. Kita ganti nilai dari N dengan suksesor _in-order_ (anak terkiri dari subpohon kanan) atau dengan predesesor _in-order_ (anak terkanan dari subpohon kiri).
# Sort
## Bubble Sort
![](https://favtutor.com/resources/images/uploads/mceu_61632030011682402256084.png)
Bubble Sort adalah salah satu algoritma sorting yang paling sederhana. Algoritma ini bekerja dengan membandingkan elemen-elemen berpasangan dalam daftar dan menukar mereka jika diperlukan. Proses ini terus berlanjut hingga semua elemen berada dalam urutan yang benar.
## Insertion Sort
![46bfac9.png](https://he-s3.s3.amazonaws.com/media/uploads/46bfac9.png)
![](https://he-s3.s3.amazonaws.com/media/uploads/46bfac9.png)
Insertion Sort membandingkan setiap elemen dengan elemen-elemen sebelumnya dan memasukkannya ke dalam posisi yang benar dalam daftar yang terurut. Algoritma ini efisien untuk daftar kecil.
## Selection Sort
![](https://miro.medium.com/0*pK2-pSUoAnIR_Eg7.png)

Selection Sort bekerja dengan cara mencari elemen terkecil dalam daftar dan menukarnya dengan elemen pertama. Proses ini terus berlanjut untuk elemen-elemen berikutnya hingga seluruh daftar terurut.
# C++
https://cwh-full-next-space.fra1.cdn.digitaloceanspaces.com/cheatsheets/C++%20Cheatsheet.pdf
https://www.geeksforgeeks.org/cpp/cpp-cheatsheet/