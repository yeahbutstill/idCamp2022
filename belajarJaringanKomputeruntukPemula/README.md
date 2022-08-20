# Rangkuman Dasar-Dasar Jaringan Komputer


## Pengenalan Jaringan Komputer
Pada dasarnya, jaringan komputer–atau bisa disebut jaringan saja–adalah kumpulan (umumnya terdiri dari dua atau lebih) komputer atau perangkat keras lain yang saling terhubung, baik melalui kabel maupun nirkabel, sehingga memungkinkan mereka untuk bertukar informasi.

Jaringan komputer mirip seperti lingkungan sosial, di mana terdiri dari kumpulan orang yang saling mengenal, secara reguler bertukar informasi, dan mengoordinasikan kegiatan bersama. Mudah ‘kan memahaminya?

Sejatinya, Anda bisa kok membuat jaringan komputer sendiri secara sederhana menggunakan perangkat yang disebut switch untuk menghubungkan semua PC (Personal Computer) alias komputer pribadi yang Anda miliki satu sama lain. Voilà! Anda pun memiliki sebuah jaringan.

![alt text](pic/img.png)

Masih terlalu rumit? Mari kita ambil contoh yang lebih mudah dan akrab dengan kehidupan sehari-hari. Hubungkanlah perangkat jemala nirkabel (headset wireless) dengan ponsel cerdas (smartphone) Anda. Ta-da! Anda pun berhasil membuat sebuah jaringan. Sederhana, ‘kan?

![alt text](pic/img_1.png)

Pada contoh pertama, itu adalah bentuk dari LAN (Local Area Network), sedangkan yang kedua ialah PAN (Personal Area Network). Anda akan mempelajarinya lebih dalam di submodul selanjutnya.

Berikut adalah beberapa keuntungan atau manfaat terkait hadirnya jaringan komputer:

- Konektivitas dan komunikasi
- Berbagi data
- Akses internet
- Pengelolaan dan keamanan data

Tentunya masih amat banyak manfaat jaringan komputer yang lain. Namun, di submodul ini cukup itu saja yang perlu Anda ketahui. Bila masih penasaran apa saja manfaat-manfaat yang lain, Anda bisa mencarinya lebih lanjut di internet.


## Tipe-Tipe Jaringan Komputer
Sesungguhnya ada banyak tipe-tipe jaringan komputer di dunia ini, tetapi kita hanya akan mempelajari beberapa di antaranya saja yang memang umum dan kerap dijadikan acuan di pembelajaran jaringan. Kita akan mulai dari Personal Area Network, Local Area Network, Metropolitan Area Network, dan akhirnya Wide Area Network.

## Personal Area Network (PAN)
Personal Area Network alias PAN adalah tipe jaringan dengan cakupan terkecil dan sangat pribadi bagi penggunanya. PAN menghubungkan perangkat elektronik yang berada dalam jangkauan pengguna. Ukuran konektivitas PAN berkisar dari sekian sentimeter hingga beberapa meter (umumnya hingga 10 meter).

## Local Area Network (LAN)
Local Area Network, atau disingkat LAN, adalah jaringan komputer yang memiliki cakupan area geografis yang relatif kecil. Pada tipe jaringan ini, jarak komputer satu sama lain cukup berdekatan, seperti halnya di dalam satu kantor atau gedung yang sama.

Jumlah komputer yang terhubung dalam LAN dapat bervariasi, mulai dari hitungan jari, belasan, atau bahkan ratusan unit–selama komputer-komputer tersebut masih berada di satu wilayah yang bisa dijangkau oleh peralatan jaringan Anda.

## Metropolitan Area Network (MAN)
Metropolitan Area Network (MAN) adalah jaringan komputer yang menghubungkan komputer dalam area metropolitan, bisa berupa satu kota besar, beberapa kota besar dan kecil, atau area luas tertentu dengan banyak bangunan.

Cakupan MAN lebih besar dari LAN, tetapi lebih kecil dari WAN–akan kita bahas nanti. Meski namanya Metropolitan Area Network, tipe jaringan ini tidaklah mesti berada di perkotaan. Istilah “metropolitan” menyiratkan ukuran jaringan, bukan demografi wilayah yang dilayaninya.

Pada praktiknya, jaringan MAN sering kali digunakan untuk menghubungkan dua atau lebih jaringan LAN dalam satu kota yang sama yang jaraknya cukup jauh dan tidak dapat dihubungkan melalui kabel sederhana atau koneksi nirkabel.

Berikut adalah beberapa perusahaan dan organisasi yang sekiranya memerlukan jaringan MAN, antara lain:

- Institusi pemerintahan yang membutuhkan koneksi tepercaya untuk support kebutuhan data dan sistem.
- Institusi pendidikan yang membutuhkan koneksi untuk mendukung program sekolah online.
- ISP (Internet Service Provider) atau Penyedia Layanan Internet yang memerlukan koneksi dari atau ke IIX (Indonesia Internet Exchange).
- Perusahaan yang memerlukan koneksi berkapasitas besar dari atau ke DC (Data Center) dan DRC (Disaster Recovery Center).
- Perusahaan yang memerlukan koneksi dari atau ke Kantor Pusat dengan Kantor Cabang.
- Perusahaan yang memerlukan koneksi untuk sistem data cadangan atau untuk keperluan integrasi sistem IT antar departemen.

## Wide Area Network (WAN)
Laksana namanya, Wide Area Network (WAN) mencakup wilayah geografis yang sungguh luas hingga mampu menjangkau lintas provinsi, lintas negara, bahkan lintas benua; dan umumnya digunakan untuk menghubungkan dua atau lebih LAN yang jaraknya relatif berjauhan.

![alt text](pic/img_2.png)

Salah satu contoh praktik penggunaannya adalah WAN kerap dimanfaatkan oleh perusahaan besar untuk menghubungkan semua jaringan kantor mereka, di mana setiap kantor biasanya memiliki jaringan LAN sendiri, dan LAN tersebut terhubung melalui WAN. Misal, perusahaan dapat memanfaatkan jaringan WAN untuk menghubungkan kantor cabang mereka yang berada di Jakarta dengan kantor pusat yang ada di Sydney.



## Sejarah Internet
Internet bermula dari jaringan kecil yang disebut ARPANET (Advanced Research Project Agency Network), dibangun oleh Departemen Pertahanan (Department of Defense) Amerika Serikat pada tahun 1969 untuk menghubungkan instalasi pertahanan.

Pada tahun 1973, protokol jaringan yang dipakai dari awal, yakni NCP (Network Control Protocol), digadang-gadang akan digantikan oleh TCP/IP (Transmission Control Protocol/Internet Protocol). NCP hendak diganti karena ia hanya mendukung komunikasi host-to-host (perangkat ke perangkat) dalam jaringan yang sama. Tentu saja itu tidak memenuhi kebutuhan yang pada saat itu menginginkan jaringan yang dinamis, terbuka, dan andal.

Pada tahun 1974, makin banyak jaringan yang terhubung dengan ARPANET. Beginilah rupa dari jaringan ARPANET pada tahun 1974.

![alt text](pic/img_3.png)

Kemudian, TCP/IP distandardisasi dari tahun 1978 sampai 1981. Hingga akhirnya, pada tanggal 1 Januari 1983 (dikenal sebagai “flag day”), NCP secara resmi dianggap usang dan ARPANET mengubah protokol jaringan intinya dari NCP ke TCP/IP protocol suite yang lebih fleksibel dan kuat.

Selanjutnya, pada pertengahan 1980-an, ARPANET banyak digunakan oleh para researcher (peneliti) dan developer (pengembang). Namun, tak ayal, banyak komunitas dan organisasi dengan berbagai macam latar belakang pun ikut berperan, berpartisipasi, dan bergabung ke ARPANET.

Tak selang berapa lama, ARPANET mulai mencapai batas kemampuannya. Lantas, masuklah National Science Foundation (NSF) mendirikan jaringan nasional yang dirancang untuk menyediakan akses ke superkomputer besar (digunakan untuk menemukan bilangan prima baru dan menghitung orbit galaksi nan jauh di sana).

ARPANET secara resmi dinonaktifkan pada tahun 1990. Sementara itu, pada tahun 1995, NSFNET ditutup dan internet secara efektif diprivatisasi. Kala itu, jaringan telah menjadi “Internet”, yakni galaksi komunikasi baru yang siap untuk dieksplorasi dan dihuni sepenuhnya.

Internet kian berkembang, tetapi sayangnya jumlah komputer di internet tak bertambah di awal 1990-an.

![alt text](pic/4.png)

Akan tetapi, sekitar Agustus 1995, ada sekitar 10 juta host di internet. Lima tahun berselang, tahun 2000-an, terjadi ledakan pada jumlah komputer yang begitu fenomenal di internet, yakni lebih dari 100 juta host.



## Cara Kerja Internet
### Internet di Balik Layar
Seperti yang sudah Anda ketahui, internet adalah kumpulan jaringan yang luas dan terhubung satu sama lain. Istilah "Internet" bisa dikatakan berasal dari konsep interconnected network (jaringan yang saling berhubungan).

Di internet, satu komputer terhubung dengan komputer yang lain dalam suatu jaringan, begitu pula satu jaringan terhubung dengan jaringan yang lain. Dengan demikian, sebuah komputer dapat berkomunikasi dengan komputer lain di jaringan yang jauh jaraknya berkat internet. Ini memungkinkan pertukaran informasi antarkomputer di seluruh dunia berlangsung dengan cepat.

![alt text](pic/5.png)

Komputer bisa saling terhubung satu sama lain melalui kabel, gelombang radio, dan jenis infrastruktur jaringan lainnya. Semua data yang dikirim melalui internet–baik berupa gambar, pesan teks, atau email–diterjemahkan ke dalam kelip cahaya atau listrik (disebut juga "bit") yang kemudian ditafsirkan oleh komputer penerima. Kabel dan gelombang radio tersebut menghantarkan bit-bit ini dengan kecepatan cahaya. Makin banyak bit yang dapat melewati kabel dan gelombang radio dalam satu waktu, artinya makin cepat pula internet bekerja.

Data yang dikirim via internet dari komputer pengirim ke komputer tujuan akan bergerak melalui satu router ke router lainnya. Data dalam dunia komputer berbentuk bit. Bit merujuk pada sebuah digit dalam sistem angka biner yang ditunjukkan dengan nilai angka 1 dan 0, hanya itu. Tak penting apakah datanya berupa gambar, video, ataupun lagu, apa pun di internet direpresentasikan dan dikirim sebagai bit.

## Konsep Distributed Networking
Internet itu terbentuk dari jaringan independen dengan jumlah yang luar biasa banyak. Hal yang menarik tentang sistem ini adalah internet sepenuhnya terdistribusi. Sistem seperti ini disebut juga sebagai Distributed Networking alias Jaringan yang Terdistribusi.

![alt text](pic/img_6.png)

Secara definisi, distributed networking adalah sistem jaringan yang saling berhubungan, tetapi independen, dan umumnya tersebar di beberapa lokasi geografis. Seperti itulah internet. Dengan kata lain, internet tidak bergantung pada mesin individu mana pun. Semua komputer atau perangkat yang dapat mengirim dan menerima data dengan cara yang benar (misal menggunakan protokol jaringan yang benar) bisa menjadi bagian dari internet.

Proses Pengiriman Data
Anggaplah Anda ingin memutar lagu di music streaming platform seperti Spotify melalui komputer. Mungkin di pandangan kita, komputer akan terhubung langsung ke server Spotify dan lantas mengirimkan lagu melalui jalur langsung dan khusus (direct and dedicated line).

![alt text](pic/img_7.png)

Akan tetapi, nyatanya bukan seperti itu cara kerja internet. Andai kata internet punya koneksi semacam itu, tak mungkin rasanya untuk tetap menjaga semua sistem tetap berfungsi dengan normal selagi jutaan pengguna dalam waktu yang bersamaan menggunakan internet. Terlebih lagi, tidak ada jaminan bahwa setiap kabel dan komputer bekerja sepanjang waktu. Sebaliknya, data berjalan di internet secara tidak langsung (less direct). Apa maksudnya?

Proses pengiriman data di internet cukuplah menarik. Pasalnya, jalur yang ditempuh tak mesti tetap. Jalur data dapat berubah di tengah proses komunikasi antarkomputer berlangsung.

Data di internet berpindah dari satu komputer ke komputer lain dalam bentuk packet dan ia bergerak layaknya kita mengendarai mobil. Tergantung pada kemacetan lalu lintas atau kondisi jalan, kita mungkin akan memilih–atau terpaksa–mengambil rute yang berbeda setiap kali bepergian ke tempat yang sama.

Selain itu, sama halnya seperti kita bisa mengangkut segala macam barang di dalam mobil, banyak jenis data digital juga yang dapat dikirim menggunakan packet. Namun, tentunya ada beberapa batasan.



Bandwidth, Throughput, dan Latency
Bandwidth, throughput, dan latency adalah istilah yang saling berkaitan, tetapi masing-masing merujuk pada hal yang berbeda. Ketiganya kerap menimbulkan kebingungan bagi banyak orang, malah sering kali tertukar. Maka dari itu, simak dengan saksama ya!

Bandwidth
Bandwidth adalah kapasitas transmisi maksimum dari sebuah perangkat. Bandwidth diukur dengan bit rate, yakni jumlah bit yang dapat kita kirim selama periode waktu tertentu, biasanya diukur dalam detik, seperti Kbps (Kilobit per second), Mbps (Megabit per second), atau Gbps (Gigabit per second).

Throughput
Throughput adalah jumlah aktual data yang berhasil dikirim atau diterima melalui jaringan. Throughput disajikan dalam satuan Kbps, Mbps, atau Gbps. Jumlah data pada throughput dapat berbeda dari bandwidth karena berbagai masalah teknis, termasuk packet loss, jitter, latency, dan lainnya.

Latency
Latency atau latensi adalah jumlah waktu yang dibutuhkan data untuk berpindah dari titik asal ke titik tujuan dan kembali lagi ke titik asal (dikenal juga sebagai round trip atau perjalanan bolak-balik). Latensi sering kali dipakai untuk mengukur delay (penundaan) pada komunikasi client dan server.

---

# Rangkuman Model Jaringan


## Pengenalan Model Jaringan
Kita hanya akan membahas 2 model jaringan, yakni OSI dan TCP/IP.

### Model OSI
Model OSI (Open Systems Interconnection) adalah model jaringan teoretis yang diusulkan untuk menstandardisasi komunikasi antara perangkat melalui jaringan. Yang dimaksud teoritis adalah model ini tidak ada implementasi praktis. Ia hanyalah model konseptual yang menjelaskan bagaimana aplikasi dapat bekerja melalui jaringan.

Model OSI memiliki 7 layer yang menggambarkan bagaimana perangkat berkomunikasi satu sama lain.

- Application Layer (Layer 7)
  
    Application layer adalah layer ketujuh dari Model OSI. Layer ini merupakan satu-satunya layer yang berinteraksi langsung dengan data dari pengguna. Sebagai contoh, saat Anda membuka www.dicoding.com, application layer-lah bertanggung jawab untuk menyiapkan HTTP request yang akan dikirim melalui jaringan, misal menambahkan header dan cookie yang diperlukan.

- Presentation Layer (Layer 6)

    Presentation layer bertanggung jawab untuk mengonversi data agar sistem yang menggunakan format data yang berbeda dapat bertukar informasi.

- Session Layer (Layer 5)

    Session layer bertanggung jawab untuk membuka, menjaga, dan menutup sesi komunikasi alias session. Session adalah durasi koneksi antara pengirim dan penerima tetap terbuka.

- Transport Layer (Layer 4)

    Transport layer adalah tempat di mana data dipecah menjadi bagian-bagian yang lebih kecil, disebut juga sebagai segment. Transport layer memiliki tanggung jawab untuk memastikan keandalan pengiriman segment data di jaringan. Data yang dikirim mestilah terkirim tanpa corrupt (rusak). Jika tidak, data tersebut akan dikirim ulang.

- Network Layer (Layer 3)

    Network layer bertugas untuk memecah segment ke dalam paket (packet). Layer ini juga menetapkan alamat IP sumber (source IP address) dan alamat IP tujuan (destination IP address) untuk masing-masing packet.

- Data Link Layer (Layer 2)

    Data link layer bertanggung jawab untuk memecah packet ke dalam frame. Selain itu, data link layer juga akan menetapkan source MAC address dan destination MAC address ke masing-masing frame.

- Physical Layer (Layer 1)

    Layer terakhir dari model OSI adalah physical layer yang melibatkan semua perangkat keras, seperti router, kabel, dan switch. Di layer ini, frame diubah menjadi aliran bit (1 dan 0) dan kemudian dikirim ke penerima.

### Model TCP/IP
Model TCP/IP memiliki 5 layer. Mari kita bahas satu per satu.

- Application layer (Layer 5)

    Application layer dalam model TCP/IP menggabungkan sebagian besar fungsi yang dilakukan oleh session layer dan presentation layer dari model OSI.

- Transport layer (Layer 4)

    Transport layer bertanggung jawab untuk memilah program client dan server mana yang seharusnya mendapatkan data. Protokol yang digunakan di layer ini adalah TCP (Transmission Control Protocol) dan UDP (User Datagram Protocol).

- Network layer (Layer 3)

    Network layer memungkinkan jaringan yang berbeda untuk berkomunikasi satu sama lain melalui perangkat yang dikenal sebagai router. Layer ini bertanggung jawab untuk mengirimkan data ke seluruh kumpulan jaringan.

- Data link layer (Layer 2)

    Layer kedua dalam model TCP/IP dikenal sebagai data link layer. Data link layer bertanggung jawab untuk mendefinisikan cara umum untuk menafsirkan sinyal sehingga perangkat jaringan dapat berkomunikasi satu sama lain.

- Physical layer (Layer 1)

    Serupa dengan namanya, layer ini mewakili perangkat fisik yang menghubungkan komputer di jaringan, termasuk spesifikasi untuk kabel jaringan dan konektor yang menghubungkan perangkat, serta spesifikasi yang menjelaskan bagaimana sinyal dikirim melalui koneksi tersebut.



### Mengenal Protokol Jaringan pada Model TCP/IP
Kumpulan standar atau aturan yang ditetapkan dan harus diikuti oleh komputer agar dapat berkomunikasi dengan benar disebut protokol.

Jaringan komputer memastikan bahwa setiap komputer dapat mendengar satu sama lain, saling berkomunikasi melalui protokol yang komputer lain juga mengerti, mengulangi pesan yang tidak terkirim secara utuh, dan berbagai hal lainnya. Persis layaknya manusia berkomunikasi.

Oke, kini Anda sudah mengerti soal konsep protokol. Selanjutnya, kita akan menilik lebih lanjut protokol-protokol di setiap layer pada model TCP/IP. Siap? Let’s go!

### Application Layer
Application layer merupakan layer paling atas dalam model TCP/IP. Layer ini memungkinkan pengguna untuk berinteraksi dengan aplikasi.

Berikut ini adalah protokol utama yang digunakan pada application layer, antara lain HTTP, HTTPS, SMTP, DNS, FTP, dan Telnet.

### Transport Layer
Transport layer bertanggung jawab atas keandalan, kontrol aliran, dan koreksi data yang dikirim melalui jaringan. Dua protokol yang digunakan pada layer ini adalah TCP dan UDP. Mari kita tengok keduanya.

- TCP

    TCP (Transmission Control Protocol) adalah protokol yang connection-oriented alias berorientasi koneksi. Artinya, TCP akan memastikan bahwa setiap packet dikirimkan–jika memungkinkan–dengan membuat koneksi ke perangkat penerima. Jika sebuah paket tidak tiba di tujuan, TCP akan mengirim ulang paket tersebut. Koneksi akan ditutup hanya setelah paket berhasil dikirim dengan sukses atau terjadi kondisi kesalahan yang tidak dapat dipulihkan. Dengan demikian, TCP termasuk protokol yang andal.

- UDP

    UDP (User Datagram Protocol) adalah protokol yang bersifat connectionless (tanpa koneksi). Maksudnya, UDP tidak memverifikasi koneksi antara komputer pengirim dan komputer penerima. Setelah UDP menerima dan memproses packet, ia kemudian akan melupakannya. UDP juga tidak menjamin bahwa packet tadi akan tiba di tujuannya.

### Network Layer
Tanggung jawab utama dari network layer adalah menerima dan mengirim packet melalui jaringan. Protokol di layer ini mencakup IP (Internet Protocol), ARP (Address Resolution Protocol), dan Internet Control Message Protocol (ICMP).

- IP

    IP (Internet Protocol) adalah protokol yang bertanggung jawab untuk mengirimkan packet ke perangkat jaringan. Protokol ini menggunakan IP address ketimbang alamat fisik (MAC) untuk merujuk ke perangkat individu. ARP-lah (nanti kita bahas) yang menangani tugas mengubah IP address ke MAC address.

- ARP

    ARP (Address Resolution Protocol) bertugas untuk membantu IP dalam mengarahkan packet ke komputer penerima yang sesuai dengan memetakan MAC address ke IP address.

- ICMP

    ICMP (Internet Control Message Protocol) bertanggung jawab untuk mendeteksi dan melaporkan kesalahan jaringan sekaligus menyediakan pembaruan status. Misalnya, jika router tidak dapat mengirimkan paket, ia akan mengirim pesan ICMP kembali ke sumber paket.

### Data Link Layer
Data link layer bertugas untuk mengidentifikasi jenis protokol jaringan pada packet. Layer ini juga menyediakan error control (kontrol kesalahan) dan framing (pembuatan frame).

Berikut beberapa contoh protokol, standar, dan implementasi pada data link layer:.

- Ethernet

    Ethernet merupakan keluarga teknologi jaringan komputer kabel yang biasa digunakan di Local Area Network (LAN), Metropolitan Area Network (MAN), dan Wide Area Network (WAN).

- Frame Relay

    Frame Relay adalah teknologi Wide Area Network (WAN) standar yang menentukan physical layer dan data link layer dari saluran telekomunikasi digital menggunakan metodologi packet switching. Awalnya dirancang untuk transportasi melintasi Integrated Service Digital Network (ISDN), kini dapat digunakan untuk banyak antarmuka jaringan lainnya.

- Token Ring

    Token Ring adalah teknologi jaringan komputer yang digunakan untuk membangun Local Area Network. Token Ring diperkenalkan oleh IBM pada tahun 1984 dan distandardisasi pada tahun 1989 sebagai IEEE 802.5.

- IEEE 802.11

    IEEE 802.11 adalah bagian dari standar IEEE 802 yang menetapkan kumpulan protokol dari MAC dan physical layer untuk mengimplementasikan komunikasi komputer Wireless Local Area Network (WLAN).

- PPP

    PPP (Point-to-Point Protocol) adalah protokol yang digunakan untuk menghubungkan satu sistem komputer ke sistem komputer lainnya. Komputer menggunakan PPP untuk berkomunikasi melalui jaringan telepon atau internet.

### Physical Layer
Physical layer memiliki tanggung jawab untuk menentukan karakteristik perangkat keras yang akan digunakan untuk jaringan. Layer ini menjelaskan standar perangkat keras seperti IEEE 802.3 (spesifikasi untuk media jaringan Ethernet) dan RS-232 (spesifikasi untuk konektor pin standar).

Berikut beberapa teknologi yang menyediakan layanan pada physical layer:

- Bluetooth physical layer

    Bluetooth adalah standar teknologi nirkabel jarak pendek yang digunakan untuk pertukaran data antarperangkat menggunakan gelombang radio UHF di ISM band dari 2,402 GHz hingga 2,48 GHz. Dengan bluetooth, artinya Anda sudah bisa membangun Personal Area Network (PAN)

- DSL physical layer

    DSL (Digital Subscriber Line) merupakan teknologi yang digunakan untuk mengirimkan data digital melalui saluran telepon. Dalam pemasaran telekomunikasi, istilah DSL secara luas dipahami sebagai Asymmetric Digital Subscriber Line (ADSL), yakni teknologi DSL yang paling umum dipasang untuk akses Internet.

- Ethernet physical layer

    Ethernet physical layer adalah fungsionalitas physical layer dari famili Ethernet yang diterbitkan oleh Institute of Electrical and Electronics Engineers (IEEE).

- SONET dan SDH physical layer

    Synchronous optical networking (SONET) dan Synchronous Digital Hierarchy adalah protokol standar untuk mentransfer beberapa aliran bit digital secara sinkron melalui fiber optic (serat optik) menggunakan laser atau cahaya yang sangat koheren dari LED (light-emitting diode).

- Modem physical layer

    Modem (modulator-demodulator) adalah sebuah perangkat keras komputer untuk mengubah data dari format digital ke dalam bentuk yang sesuai untuk analog, seperti telepon atau radio.

- USB physical layer

    USB (Universal Serial Bus) adalah standar industri yang menetapkan spesifikasi kabel, konektor, dan protokol untuk koneksi, komunikasi, dan catu daya antara komputer, periferal, dan komputer lain. Ada banyak variasi rentetan perangkat keras USB, USB-C adalah yang paling terkini.



## Komunikasi Data pada Model TCP/IP
Sekarang kita akan melihat bagaimana komunikasi data yang terjadi pada model TCP/IP supaya Anda makin paham lagi tentang model ini. Siapkan ancang-ancang, mari kita langsung mulai.

Katakanlah kita ingin membuka website www.dicoding.com melalui web browser yang sudah terhubung ke jaringan (dalam hal ini adalah internet). Itu berarti, web browser berada di sisi client, sementara web server milik Dicoding ada di sisi server. Ini dinamakan komunikasi client-server. Oke, lantas apa yang akan terjadi selanjutnya?

- Application layer

    Layer pertama yang akan berinteraksi dengan browser adalah application layer. Layer ini mendefinisikan komunikasi antara aplikasi yang ada di komputer pengirim (client) dan aplikasi di komputer penerima (server).


- Transport Layer

    Transport layer memiliki tanggung jawab untuk memecah data (message) yang diterima menjadi potongan yang lebih kecil yang disebut segment (jika menggunakan TCP) atau datagram (jika menggunakan UDP).

    Katakanlah web server dicoding memiliki proses yang berjalan pada port 80. Ketika client menyiapkan HTTP request, ia akan menambahkan TCP header. TCP header berisi banyak hal, sekian di antaranya adalah source port (port sumber) dan destination port (port tujuan). Anggap saja source port dalam skenario kita adalah port 7268, sedangkan source destination-nya adalah port 80.


- Network Layer

    Di network layer, data (segment) akan dipecah menjadi potongan yang lebih kecil yang disebut packet. Packet yang dihasilkan bisa jadi satu atau mungkin banyak, tergantung pada berapa banyak data yang ada.

    Tugas dari layer ini adalah untuk memastikan bahwa data dari satu komputer (client) dapat menemukan jalan ke komputer tujuan (server). Untuk melakukan itu, sebuah IP header yang berisi source IP (IP sumber) dan destination IP (IP tujuan) ditambahkan ke setiap packet.

    Jalur dari client ke server mungkin saja melintasi banyak jaringan. Oleh karenanya, packet membutuhkan peran dari perangkat jaringan router untuk berpindah dari satu jaringan ke jaringan yang lain. Inilah yang dinamakan routing (perutean).


- Data Link Layer

    Data link layer bertanggung jawab untuk pengiriman lalu lintas pada satu segmen jaringan atau LAN, dalam istilah TCP/IP berarti pengiriman dalam satu subnet. Data (packet) dari layer sebelumnya akan dipecah menjadi bagian yang lebih kecil yang disebut frame.

    Kemudian, frame tersebut akan ditambahkan sebuah header yang berisi source MAC address (MAC address sumber) dan destination MAC address (MAC address tujuan). Bagi Anda yang belum familier, MAC address adalah alamat yang ditetapkan dan dimiliki oleh setiap perangkat fisik.


- Physical Layer

    Sesuai namanya, physical layer bertanggung jawab untuk mengirim dan menerima data secara fisik. Ada banyak caranya, bisa melalui gelombang radio (Wi-Fi), sinyal cahaya (Fiber optic), dan lain-lain. Data yang tadi dikirim dari data link layer kemudian di-encode (dikodekan) ke dalam bit (1 dan 0), lalu ditransmisikan melalui media fisik.

