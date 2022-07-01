# Rangkuman Kelas


# Pengenalan DevOps


### Masalah pada Proses Pengembangan Aplikasi
Kita semua tahu bahwa proses pengembangan aplikasi itu ruwet, bahkan di beberapa kasus bisa jadi melibatkan banyak sekali pihak. Tidak hanya dari segi model, ada juga beberapa masalah lain yang menghantui selama proses pengembangan aplikasi, seperti arsitektur yang monolitik, proses yang manual, dan struktur tim yang tertutup pun bisa menjadi bottleneck sehingga menyebabkan keterlambatan dan ketidakefisienan dalam proses penyajian aplikasi.

Oke, supaya lebih detail dalam memahami masalah-masalah ini, mending langsung saja kita bedah satu per satu yuk.

### Model Waterfall
Waterfall adalah salah satu dari sekian banyak model pada proses pengembangan aplikasi (alias SDLC atau Software Development Life Cycle). Model Waterfall ini merupakan metode kerja yang menekankan fase-fase yang berurutan dan sistematis. Disebut waterfall lantaran proses yang terjadi dalam mengembangkan sebuah perangkat lunak atau aplikasi mengalir satu arah “ke bawah” bak air terjun.

Pada model waterfall, setiap fase saling bergantung satu sama lain. Kita tak bisa lanjut ke fase berikutnya sebelum fase yang sedang dikerjakan saat ini benar-benar selesai digarap. Misalnya, kita tak bisa melakukan pengujian jika proses coding dari keseluruhan aplikasi belum beres. Begitu juga kita tak bisa men-deploy aplikasi jika keseluruhan komponen aplikasi belum lolos fase pengujian. Begitu seterusnya.

Ketahuilah bahwa proses perpindahan dari satu fase ke fase lainnya pun memakan waktu yang lama, salah satu penyebabnya adalah tim yang bertanggung jawab perlu menyesuaikan tools yang mereka gunakan terlebih dahulu.

Belum lagi jika di tengah-tengah proses pengembangan aplikasi tetiba ada perubahan kebutuhan, fitur, atau antarmuka; repotlah jadinya karena harus kembali ke fase awal, yakni penentuan persyaratan/kebutuhan (requirement).

### Arsitektur Monolitik
Apa sih yang dimaksud dengan monolitik itu? Maksudnya, dikatakan arsitektur monolitik apabila kita menempatkan berbagai komponen aplikasi di satu unit. Contoh sederhananya adalah ketika kita men-deploy authentication service (layanan autentikasi), order service (layanan pemesanan), account service (layanan akun), dll di satu Back-End server yang sama.

Sebenarnya, arsitektur monolitik bukan berarti buruk sama sekali. Ia menjadi langkah awal yang bagus bagi Anda yang baru memulai pengembangan aplikasi agar bisa memahami kompleksitas sistem dan cakupan setiap komponen lebih baik. Namun, seiring makin rumitnya sistem yang Anda bangun, makin sulit pula untuk dikelola bila tetap menerapkan pendekatan monolitik.

Pasalnya, itu berarti semua komponen (seperti authentication service, order service, account service, dll) saling terikat dan bergantung satu sama lain. Jika salah satu komponen gagal beroperasi, kemungkinan besar komponen yang lain akan terkendala.

Oleh karena itu, apabila Anda memiliki aplikasi yang menggunakan pendekatan monolitik dan dirasa sudah sangat kompleks sehingga sulit untuk dikelola, sebaiknya modifikasilah arsitekturnya agar menerapkan pendekatan microservice.

### Proses Manual
Proses yang manual membuat pengembangan aplikasi menjadi lambat, tidak konsisten, dan rawan kesalahan.

Sebagai contoh, pengaturan dan pengonfigurasian infrastruktur (seperti server) secara manual merupakan proses yang sangat memakan waktu. Bagaimana tidak, melakukan proses ini ke beberapa server yang ada terus-menerus secara manual bisa menguras tenaga dan menghabiskan waktu hingga berhari-hari. Ditambah lagi, rentan sekali adanya kemungkinan bahwa satu atau dua langkah terlewat sehingga pada akhirnya timbul kesalahan konfigurasi.

### Struktur Tim Tertutup
Proses pengembangan aplikasi melibatkan 2 tim penting, yakni Developer dan IT Operations. Mereka adalah dua tim yang krusial karena memiliki tujuan yang sama, yakni menyajikan aplikasi yang komprehensif dan stabil ke pengguna; tetapi sering kali mereka tertutup satu sama lain dan seakan-akan tercerai. Baik Developer maupun IT Operations, mereka memiliki prioritas, peralatan, dan pola kerjanya sendiri-sendiri sehingga acap kali menimbulkan pergolakan saat mereka tengah bekerja sama.

Di satu sisi, Developer dituntut oleh perusahaan untuk dapat membuat perangkat lunak, mengembangkan aplikasi, memperbaiki bug, dan mengerjakan banyak fitur secepat mungkin. Sering kali yang diukur hanyalah jumlah fitur yang dikerjakan sehingga justru inilah yang mengakibatkan mereka tidak memperhatikan kualitas kode.

Di sisi lain, IT Operations dituntut untuk membuat infrastruktur (seperti server, database, jaringan, dan sejenisnya) yang senantiasa stabil tanpa down. Nah, masalahnya, salah satu hal yang kerap membuat infrastruktur tidak stabil adalah perubahan yang terjadi pada aplikasi yang berjalan di dalamnya. Selain perubahan, intensitas deploy yang tinggi pun akan memperbesar potensi terjadinya masalah.

Di sinilah letak masalah antara tim Developer dan IT Operations berpusat, kedua tim tersebut memiliki peran yang berseberangan satu sama lain.

Lantas, bagaimana dong cara mengatasi masalah antara Developer dan IT Operations ini? Bagaimana agar keduanya bisa berkolaborasi dengan baik? Nah, prakarsa mengenai DevOps pun muncul untuk menjadi solusi dari problematika ini.



### Pengertian DevOps
DevOps adalah kombinasi dari filosofi kultur/budaya, sekumpulan praktik, dan rangkaian alat (tools) yang dapat meningkatkan kemampuan organisasi/perusahaan untuk menyajikan (deliver) aplikasi atau perangkat lunak secara cepat.

Itu artinya, perusahaan mampu mengembangkan dan memperbaiki produk mereka dengan lebih cepat ketimbang menggunakan model pengembangan aplikasi dan proses manajemen infrastruktur yang tradisional, seperti model Waterfall yang kita bahas sebelumnya. Dengan prosedur yang cepat, memungkinkan perusahaan untuk melayani pengguna dengan lebih baik dan mampu bersaing secara lebih efektif di pasar.

Dengan mengimplementasikan DevOps, tim yang sebelumnya saling tertutup dan terpisah (yakni Developer dan IT Operations) pada akhirnya mampu bersatu, berkolaborasi, dan berkomunikasi untuk mengoptimalkan produktivitas. Ucapkan selamat tinggal pada kekisruhan yang terjadi pada internal perusahaan dan mari ciptakan suasana yang lebih damai.



### Manfaat Penerapan DevOps
Apa pun ukuran dari perusahaan Anda, entah itu startup, medioker,  hingga korporasi sekalipun akan memperoleh manfaat bila mengadopsi DevOps. Berikut ini adalah beberapa manfaat utama DevOps.

- #### Ketangkasan
Menerapkan DevOps dapat membuat perusahaan Anda unggul secara kompetitif karena sanggup mengantisipasi kebutuhan pasar, menciptakan inovasi dengan cepat, serta merengkuh pertumbuhan bisnis yang lebih efisien.

- #### Proses rilis cepat
DevOps mampu meningkatkan frekuensi rilis aplikasi, fitur, atau perangkat lunak sehingga Anda dapat berinovasi dan meningkatkan kualitas produk dengan lebih cepat.

- #### Keandalan
Saat melakukan pembaruan pada aplikasi atau perubahan terhadap infrastruktur, pastikan kualitasnya tetap terjaga agar Anda dapat menyajikan aplikasi yang ciamik lebih cepat dan andal sehingga pengguna tetap mendapatkan pengalaman yang positif.

- #### Skalabilitas
Hadirnya DevOps memungkinkan Anda untuk mengelola dan mengoperasikan infrastruktur beserta proses pengembangan aplikasi dalam skala besar. Automasi dan konsistensi dapat mempermudah Anda dalam mengelola sistem yang kompleks secara efisien dengan risiko yang lebih rendah.

- #### Kolaborasi meningkat
Anda bisa membangun tim yang lebih efektif dengan menerapkan kultur DevOps, yang menekankan nilai-nilai seperti kepemilikan dan akuntabilitas. Developer dan IT Operations akan berkolaborasi dengan erat, berbagi banyak tanggung jawab, dan memadukan alur kerja mereka. Dengan ini pada akhirnya akan mengurangi inefisiensi sekaligus menghemat waktu.

- #### Keamanan
Jika menerapkan DevOps, bisnis Anda bisa bergerak lebih cepat sambil mempertahankan akses kontrol dan menjaga compliance. Anda bisa mengadopsi DevOps tanpa mengorbankan keamanan, yakni menggunakan compliance policies (kebijakan compliance) secara otomatis, kontrol akses yang mendetail, dan teknik manajemen konfigurasi.



## Prinsip-Prinsip DevOps


### Pengantar The Three Ways: Prinsip-Prinsip yang Mendasari DevOps
Ketahuilah, sebelum bisa mengimplementasikan DevOps dengan baik, ada prinsip-prinsip DevOps yang perlu diketahui supaya kelak Anda bisa membawa perusahaan ke level yang lebih tinggi dari saat ini.

Terdapat 3 prinsip utama yang akan kita pelajari:

- Prinsip terkait alur kerja, yang mampu mengakselerasi penyelesaian dan/atau penyerahan pekerjaan dari Developer, ke IT Operations, hingga ke pengguna aplikasi.

- Prinsip terkait umpan balik, yang memungkinkan perusahaan untuk menciptakan sistem kerja yang lebih aman dan lebih baik.

- Prinsip terkait proses belajar dan eksperimen yang berkelanjutan, yang mampu menciptakan kultur yang menumbuhkan dua hal:

  - pemahaman bahwa pengulangan dan latihan merupakan syarat untuk menguasai sesuatu; serta

  - kesadaran betapa pentingnya eksperimen yang terus-menerus guna meningkatkan keterampilan dalam pengambilan risiko dan sebagai proses belajar baik dari keberhasilan maupun kegagalan.

Poin-poin di atas disebut dengan **The Three Ways**, yakni prinsip-prinsip yang mendasari DevOps. Prinsip-prinsip ini menggambarkan nilai dan filosofi yang dapat memandu Anda dalam mengimplementasikan dan mempraktikkan DevOps di perusahaan Anda. Apabila prinsip-prinsip ini tidak diterapkan atau tidak ada dalam proses pengembangan aplikasi Anda, maka sebenarnya Anda belum sepenuhnya mengimplementasikan DevOps.



## The First Way: Prinsip Terkait Alur Kerja
Dalam bidang IT, terutama yang berkaitan dengan pengembangan aplikasi, suatu “pekerjaan” umumnya mengalir dari kiri ke kanan, yakni dari Development hingga Operations (yang mana merupakan area fungsional antara bisnis dan pelanggan).

Maka dari itu, prinsip DevOps pertama yang akan kita bahas adalah The First Way, yakni terkait alur kerja. Prinsip ini menjelaskan bahwa kita membutuhkan alur kerja yang cepat dan lancar dalam proses pengembangan aplikasi, mulai dari penulisan kode oleh Developer (Development), ke penyiapan infrastruktur dan proses deploy aplikasi oleh IT Operations (Operations), hingga akhirnya sampai di gadget pengguna/pelanggan (Customer) dan terasa manfaat atau nilai dari aplikasi/fitur/pembaruan perangkat lunak tersebut.

Dalam proses pengembangan aplikasi, ada beberapa cara atau metode untuk mengoptimalkan alur kerja, yakni dengan membuat pekerjaan kita menjadi “tampak”, membatasi work in process (tugas yang masih tahap pengerjaan dan/atau belum terselesaikan), mengurangi skala batch yang dikerjakan, memangkas jumlah handoff, serta mengidentifikasi dan memperbaiki constraint.

Intinya, tujuan dari The First Way ini adalah untuk memperbaiki alur kerja sehingga proses pengembangan aplikasi bisa berlangsung cepat, tetapi tetap menjaga keandalan infrastruktur dan meningkatkan kualitas aplikasi. Dengan demikian, pada akhirnya pelanggan pun bisa merasakan fitur atau pembaruan aplikasi lebih cepat.



## The Second Way: Prinsip terkait Umpan Balik
Jika The First Way menjelaskan tentang prinsip yang memungkinkan alur kerja yang lancar dan cepat dari kiri ke kanan (Development ke Operations), The Second Way ini mendeskripsikan prinsip yang memungkinkan feedback (umpan balik) yang cepat nan konstan dari kanan ke kiri (Operations ke Development).

Pada prinsip ini, fokus utamanya adalah untuk meningkatkan jumlah feedback dan mempercepat proses penyampaian feedback (dari Operations ke Development) guna mencegah agar masalah tak terulang kembali, memungkinkan deteksi masalah lebih dini, serta pemulihan infrastruktur lebih cepat.

Prinsip ini sangat penting untuk kita pahami agar terciptanya sistem kerja yang lebih aman sebab masalah dapat ditemukan sedini mungkin dan diperbaiki lebih cepat sehingga kita terhindar dari kegagalan saat aplikasi sudah di-deploy ke production a.k.a dirilis ke publik.

Nah, salah satu cara terbaik untuk mencapainya adalah dengan memiliki praktik seperti continuous integration atau continuous deployment (akan kita pelajari nanti) yang dipadukan bersama dengan rangkaian automated test (pengujian otomatis) yang cepat. Dengan mempraktikkan hal-hal ini, feedback (umpan balik) bisa segera tersampaikan dengan cepat ke Developer dan segera diperbaiki.



## The Third Way: Prinsip terkait Proses Belajar dan Eksperimen yang Berkelanjutan
Pembahasan yang ketiga adalah The Third Way, yakni prinsip terkait proses belajar dan eksperimen yang berkelanjutan. Prinsip ini menjelaskan tentang cara memupuk kultur untuk mendorong proses belajar dan eksperimen yang berkelanjutan. Selain itu, prinsip ini juga membenamkan pemahaman bahwa cara untuk menguasai sesuatu adalah melalui pengulangan dan berlatih terus-menerus.

Tentu kita semua tahu bahwasanya eksperimen yang dilakukan terus-menerus bukanlah hal yang mudah untuk dilestarikan sebab membutuhkan keberanian dalam pengambilan risiko dan kelapangan hati dalam belajar (baik dari jika berhasil maupun gagal).

Proses pengambilan risiko biasanya adalah sesuatu yang sebisa mungkin dihindari oleh bisnis. Namun sebaliknya, justru eksperimen dan pengambilan risiko adalah hal yang bagus bagi IT karena memungkinkan kita untuk senantiasa meningkatkan sistem kerja.

Proses eksperimen ini sering kali mengharuskan tim untuk berani melakukan hal-hal di luar kebiasaan mereka selama ini. Ini merupakan hal yang bagus. Pasalnya, ketika terjadi kesalahan atau kegagalan, tim bisa memperbaikinya dan belajar dari kesalahan/kegagalan tersebut.

Dengan begitu, ke depannya tim bisa lebih cekatan dalam mengembangkan aplikasi dan terhindar dari kegagalan yang berulang. Pun, bila seandainya terjadi kesalahan yang tak diinginkan, tim akan mengerti apa yang harus dilakukan dan memitigasi agar kegagalan tersebut tidak terulang kembali.

Jika kita mampu menerapkan The First Way dan The Second Way, kelak kita akan lebih berani dalam mengambil risiko. Sebabnya, kita tahu bahwa risikonya takkan terlalu besar (mengingat kita memiliki skala batch pekerjaan yang kecil) dan akan mendapatkan feedback yang cepat mengenai pekerjaan yang kita lakukan.

Apabila kita sudah terbiasa melakukan eksperimen dan belajar dari kesalahan, maka akan tercipta kultur untuk selalu ingin berinovasi dan berani dalam mengambil risiko.



# CALMS Framework


## Pengantar CALMS Framework
Untuk bisa menerapkan DevOps dengan baik di perusahaan, ihwal terkrusial yang perlu Anda lakukan adalah memahami metodologi DevOps. Dengan menguasainya, niscaya kelak dapat meningkatkan kolaborasi antartim di perusahaan melalui aktivitas yang berlangsung pada siklus hidup aplikasi, mulai dari desain produk, proses pengembangan aplikasi, hingga operasional produksi (a.k.a rilis ke pasar dan dinikmati pengguna).

Seperti yang kita tahu, DevOps bertujuan untuk menyatukan orang-orang untuk bekerja sama dan menghilangkan hambatan sehingga mereka dapat mencapai tujuan secara efisien. Nah, modul ini akan menyelami lebih dalam mengenai metodologi yang dipakai untuk mengadopsi DevOps, yakni seputar kultur, praktik, dan tools.

Untuk memahami bagaimana cara menerapkan DevOps, kita akan menggunakan suatu framework alias kerangka kerja yang bernama CALMS sebagai acuan.

CALMS merupakan framework yang digunakan sebagai sarana untuk menilai apakah suatu perusahaan atau organisasi siap dalam mengadopsi DevOps, serta mengukur bagaimana kemajuan perusahaan dalam transformasi atau proses penerapan DevOps mereka.



## CALMS Framework: Culture
Beberapa hal yang perlu Anda pelajari dan terapkan di perusahaan adalah membangun lingkungan yang kolaboratif, fokus pada kebutuhan pengguna, dan menyertakan keamanan di setiap fase.

- **Membangun lingkungan yang kolaboratif**
Kolaborasi merupakan hal terpenting yang perlu diperhatikan saat mengimplementasikan DevOps di perusahaan. Baik Developer maupun IT Operations, keduanya memiliki perangkat lunak, kepentingan, dan tujuannya sendiri-sendiri. Ini bukanlah hal yang baik karena akan menciptakan gap atau kerenggangan di antara mereka.

  Oleh karenanya, DevOps perlu hadir agar mereka bisa bersatu dan saling bekerja sama. Kolaborasi ini pada akhirnya dapat mengoptimalkan produktivitas dari sisi Developer sekaligus menjaga keandalan dari sisi IT Operations.


- **Fokus pada kebutuhan pengguna**
Mindset yang mengutamakan pengguna adalah faktor utama dalam mendorong pengembangan aplikasi. Sebagai contoh, dengan feedback loop (umpan balik yang berkelanjutan), tim terkait (Developer dan IT Operations) bisa tetap terhubung dengan pengguna untuk mengembangkan aplikasi sesuai kebutuhan pasar.


- **Menyertakan keamanan di setiap fase**
Aspek keamanan harus diimplementasikan di setiap fase dalam siklus hidup aplikasi, baik saat masih dalam proses coding maupun selepas rilis ke pasaran.

  Musabab ini adalah hal yang krusial, Anda mesti sedini mungkin mengedukasi tim Developer dan IT Operations untuk menanamkan aspek keamanan dalam pola kerja mereka.



# CALMS Framework: Automation
Dengan menerapkan DevOps, tugas-tugas repetitif dan manual dapat diotomatiskan sehingga memungkinkan tim (baik Developer maupun IT Operations) untuk fokus menciptakan inovasi.

Automasi akan menjadikan proses pengembangan (development), pengujian (testing), dan penggelaran (deployment) menjadi cepat. Namun, untuk mewujudkan hal itu, Anda perlu mengidentifikasi sekiranya di bagian mana saja proses automasi bisa diterapkan.



# CALMS Framework: Lean
Dalam implementasi DevOps, tim Developer perlu menerapkan prinsip lean guna menghilangkan inefisiensi proses dan mengoptimalkan nilai kerja, seperti meminimalkan WIP, menjadikan pekerjaan kita transparan, mengeliminasi kerumitan saat proses penyerahan kode ke IT Operations, dan mengurangi waktu tunggu saat berpindah dari satu fase ke fase lainnya (misal dari penulisan kode ke pengujian).



# CALMS Framework: Measurement
Dalam menerapkan DevOps, perusahaan mesti mengabdikan diri mereka untuk benar-benar mengumpulkan data tentang apa pun, mulai dari alur kerja, proses deployment, pengguna, hingga infrastruktur. Ini diperlukan guna memahami kemampuan perusahaan saat ini dan mengidentifikasi di bagian mana perbaikan dapat diterapkan.

Meski bisa mengukur segala hal, tidak berarti kita harus mengukur semuanya. Berikut adalah beberapa contoh pertanyaan untuk mengukur kinerja atau proses Anda selama ini.

- Berapa lama waktu yang dibutuhkan dari tahap penulisan kode hingga deployment?
- Seberapa sering bug atau galat muncul?
- Berapa lama waktu yang dibutuhkan untuk pulih (recover) dari kegagalan sistem (system failure)?
- Berapa banyak orang yang menggunakan produk Anda saat ini?
- Berapa banyak pengguna yang Anda peroleh atau justru hilang di minggu ini?
- Semua data-data ini akan menarik karena kelak membantu perusahaan Anda untuk membuat keputusan. Salah satunya, Anda bisa menentukan kapan waktu yang tepat untuk merilis fitur baru atau melakukan rollback (kembali ke versi aplikasi sebelumnya).



# CALMS Framework: Sharing
Hal yang tak kalah penting lainnya saat menerapkan DevOps di perusahaan adalah dengan menciptakan budaya keterbukaan (transparansi informasi dan komunikasi) dan saling berbagi di dalam dan di antara tim. Dengan begitu, semua orang akan bisa bekerja sama menuju satu tujuan dan meminimalisir gesekan yang timbul ketika masalah muncul.



# Praktik DevOps


# Pengantar Praktik DevOps
Kita suah membedah secara tuntas mengenai metodologi DevOps melalui CALMS Framework. Kini kita akan menyambangi materi lain mengenai bagaimana sebenarnya DevOps dipraktikkan supaya Anda mendapat gambaran dengan lebih jelas.

Anda harus paham terlebih dahulu bahwa poin-poin yang tadi kita bahas pada modul CALMS Framework akan mengarah pada praktik DevOps yang merampingkan dan meningkatkan siklus pengembangan aplikasi agar bisa menyajikan update (pembaruan) lebih sering secara andal seraya menjaga stabilitas infrastruktur (seperti server).

Ini pada akhirnya berujung pada dua hal praktis nan penting, yakni DevOps pipeline dan DevOps tools. Kita akan bahas ini lebih mendalam di submodul berikutnya. Yuk, lanjut!



# DevOps Pipeline
DevOps Pipeline (atau biasa disebut juga sebagai CI/CD Pipeline) merupakan serangkaian proses dan tools terotomatisasi yang memungkinkan Developer dan IT Operations untuk bekerja secara kohesif untuk men-deploy kode ke lingkungan production.

Mari kita bedah setiap tahapan pada DevOps Pipeline satu per satu.

- **Code**
Pada tahap ini, tim Developer menulis dan mengembangkan kode aplikasi dalam bahasa pemrograman tertentu, entah itu Java, JavaScript, Python, C#, dsb. Selepas kode siap, Developer pun kemudian mengirimkan/mengunggah (push) kode yang telah ditulis ke sebuah lokasi terpusat, umumnya adalah Git repository.

- **Build**
Selepas kode di-push ke repository dan dipastikan aman untuk lanjut ke fase berikutnya, kode tadi lantas dieksekusi melalui proses build. Usai semua proses build sukses, barulah kita bisa masuk ke fase berikutnya.

- **Test**
Tahapan berikutnya adalah test alias pengujian. Di sini, artifact yang sedianya sudah dibuat akan diuji apakah memenuhi persyaratan fungsional, kinerja, desain, dan implementasi yang ditentukan atau tidak. Setelah semua pengujian berhasil lolos, tahapan selanjutnya pun dimulai.

- **Release**
Di fase ini, artifact yang telah lolos pengujian kemudian dikemas/dibungkus dengan nomor versi (version number) tertentu sebelum nanti akhirnya di-deploy.

- **Deploy**
Usai diberi nomor versi, artifact akan di-deploy ke target environment/lingkungan (kumpulan sumber daya–seperti server, dll–untuk meng-hosting aplikasi) yang sesuai, entah itu ke lingkungan test, staging, alpha, beta, atau production sekalipun.

- **Monitor**
Dalam tahap ini, umumnya aplikasi sudah di-deploy ke lingkungan production dengan sempurna sehingga bisa dinikmati oleh pengguna. Oleh karenanya, kita perlu memonitor aplikasi agar bisa mendeteksi error ataupun kejanggalan dengan cepat dan secara tanggap langsung memperbaikinya.

Jika terjadi kegagalan di salah satu tahapan, proses yang tengah dilakukan akan dihentikan sehingga tak bisa lanjut ke fase berikutnya.

Selain itu, saat kita belajar tentang DevOps pipeline atau CI/CD pipeline, maka akan erat kaitannya pula dengan istilah-istilah seperti Continuous Integration, Continuous Delivery, dan Continuous Deployment. Apa sih perbedaan mendasar di antara ketiganya?

Mari kita bedah ketiganya satu per satu.

- **Continuous Integration**
Continuous integration (CI) merupakan praktik pada proses pengembangan aplikasi di mana Developer dengan rutin dan teratur memasukkan (commit) atau menggabungkan (merge) setiap perubahan kode (code changes) mereka ke sebuah repositori terpusat (central repository), setelah itu proses build dan test secara otomatis pun dijalankan.


- **Continuous Delivery**
Continuous delivery (CD) adalah praktik pada proses pengembangan aplikasi di mana perubahan kode (code changes) secara otomatis dipersiapkan sebelum nantinya dikirim ke lingkungan production.

  Continuous delivery merupakan teknik lanjutan dari continuous integration. Jika di CI hanya sampai proses build dan unit test, di CD ini prosesnya hingga deploy semua perubahan kode ke lingkungan testing, staging (pre-production), dan/atau production. Namun, untuk bisa men-deploy ke production, perlu melalui persetujuan manual (manual approval) terlebih dahulu, entah itu oleh Developer yang lebih senior, manajer, atau siapa pun yang berhak.


- **Continuous Deployment**
Continuous delivery dan continuous deployment pada hakikatnya adalah proses yang “serupa tapi tak sama”. Perbedaannya, continuous delivery memiliki proses persetujuan manual (manual approval) sebelum aplikasi di-deploy ke production, sementara continuous deployment tidak ada.

  Jadi, dengan continuous deployment, proses deploy aplikasi ke lingkungan production berlangsung secara otomatis tanpa ada persetujuan eksplisit dan intervensi manusia.



# DevOps Tools
Dalam mendukung kesuksesan praktik DevOps di suatu perusahaan, ada beberapa kategori best practice yang perlu kita perhatikan berikut dengan tools yang sesuai untuk menerapkannya (akan dibagi antara tools yang bersifat umum dan AWS).

## Komunikasi dan Kolaborasi
Berikut adalah beberapa tools yang bisa membantu mengimplementasikan komunikasi dan kolaborasi antartim di perusahaan.

- ### Platform komunikasi dan kolaborasi terpadu
  Berikut adalah beberapa contoh platform komunikasi dan kolaborasi terpadu (dibagi berdasarkan tools umum dan tools AWS).

   - #### Umum	
     - Microsoft Teams  
     - Slack 
     - Workplace 
     - Cisco Webex Teams
   - #### AWS
     - Amazon Chime

- ### Cloud
  Alih-alih harus membeli dan memelihara perangkat-perangkat server secara fisik, Anda bisa dengan mudah membuat suatu environment (yang berisi server, jaringan, penyimpanan, dll) secara on-demand (sesuai permintaan) menggunakan cloud provider seperti AWS.

- ### IDE
  Berikut adalah beberapa contoh IDE yang mendukung collaboration tool(dibagi berdasarkan tools umum dan tools AWS).

  - #### Umum
    - Visual Studio dengan fitur Live Share
    - Intellij IDEA dengan fitur Code With Me
  - #### AWS
    - AWS Cloud9



- ### CI/CD
  Dalam poin CI/CD ini, tools yang digunakan dibagi menjadi beberapa kategori berdasarkan siklus DevOps pipeline.

  - #### Code
     Berikut beberapa contoh version control system yang bisa Anda pakai (dibagi berdasarkan tools umum dan tools AWS).

    - ##### Version Control System

      - Umum
        - GitHub
        - GitLab
        - BitBucket
      - AWS
        - AWS CodeCommit

  
- ### Build
  Berikut beberapa contoh tools yang digunakan pada proses build (dibagi berdasarkan tools umum dan tools AWS).

  - #### Build Tools
    - Umum
      - Travis CI
      - Jenkins
      - CircleCI
    - AWS
      - AWS CodeBuild


- ### Test
  Tahapan test ini sebenarnya tergantung. Apabila sekadar unit test, maka itu bisa dilakukan saat proses build berlangsung. Namun, jika ingin melakukan load testing, kita perlu men-deploy-nya terlebih dahulu ke lingkungan testing dengan bantuan AWS CodeDeploy. Opsi lain, jika Anda menginginkan suatu pengujian yang spesifik, bisa juga memanfaatkan third-party tools dan mengintegrasikannya dengan AWS.


- ### Release
  Kode aplikasi yang telah lolos pengujian kemudian disimpan ke repository, registry, atau storage dalam bentuk software packages, container image, dsb., dengan diberi nomor versi tertentu yang menandakan bahwa aplikasi sudah final dan siap di-deploy.

  Apabila artifact yang dimaksud berbentuk compressed file, kita bisa menaruhnya di object storage seperti Amazon S3. Akan tetapi, jika berbentuk container image, berikut adalah contoh tools yang bisa digunakan (dibagi berdasarkan tools umum dan tools AWS).

  - ##### Container Image Registry tools

    - Umum
      - Docker Hub 

    - AWS
      - Amazon ECR 





- ### Deploy
  Berikut adalah beberapa contoh tools yang bisa digunakan untuk deploy aplikasi (dibagi berdasarkan tools umum dan tools AWS).

  - #### Deployment Tools
    - Umum
      - Heroku 
      - Netlify
      - GitHub Pages

    - AWS
      - AWS CodeDeploy 
      - AWS Elastic Beanstalk








- ### Monitor
  Berikut adalah beberapa contoh tools yang bisa digunakan untuk memantau aplikasi (dibagi berdasarkan tools umum dan tools AWS).

  - #### Monitoring Tools
    - Umum 
      - Prometheus
      - Elastic Stack
      - Dynatrace
    - AWS
      - AWS X-Ray
      - Amazon CloudWatch


AWS CodePipeline adalah layanan continuous delivery yang memungkinkan kita untuk membuat model, memvisualisasikan, dan mengotomatiskan langkah-langkah yang diperlukan untuk merilis perangkat lunak. Dengan layanan ini, kita bisa mengonfigurasi tahapan-tahapan pada CI/CD pipeline sehingga memudahkan dalam proses pengembangan aplikasi.



### Infrastructure as Code
Dalam pembahasan Infrastructure as Code ini, umumnya terdapat 2 kategori yang perlu kita bedah, yakni infrastructure automation dan configuration management.

- #### Infrastructure automation
  Infrastructure automation dalam hal ini adalah pembuatan infrastruktur dan sumber daya sejenis secara otomatis hanya dengan menggunakan kode. Dengan cara ini, baik Developer maupun IT Operations dapat berinteraksi dengan infrastruktur secara terprogram dalam skala besar, tanpa perlu mengonfigurasinya secara manual.

  Berikut adalah contoh tools yang bisa digunakan untuk kategori infrastructure automation (dibagi berdasarkan tools umum dan tools AWS).

  - #### Infrastructure automation tools

    - Umum
      - Terraform

    - AWS
      - AWS CloudFormation





- #### Configuration management
  Berikut adalah beberapa contoh tools yang bisa digunakan pada kategori configuration management (dibagi berdasarkan tools umum dan tools AWS).

  - #### Configuration management tools

    - Umum
      - Chef
      - Puppet
      - Ansible

    - AWS
      - AWS OpsWorks











- #### Arsitektur Microservices
  Ketika berbicara tentang microservice, akan ada dua topik hangat yang perlu kita bahas, yakni container dan serverless.

  - ##### Container
    Berikut adalah beberapa contoh tools yang bisa digunakan terkait container orchestration tools (dibagi berdasarkan tools umum dan tools AWS).

    - Container Orchestration tools

      - Umum
        - Kubernetes
        - OpenShift
        - Nomad

      - AWS
        - Amazon ECS
        - Amazon EKS


- #### Serverless
  Berikut adalah beberapa contoh tools yang bisa digunakan terkait serverless function as a service (dibagi berdasarkan tools umum dan tools AWS).

  - #### Serverless Function as a Service tools

    - #### Umum
      - Serverless
      - OpenFaaS
      - OpenWhisk

    - #### AWS
      - AWS Lambda
      




  
- #### Monitoring dan Logging
  Berikut adalah beberapa contoh tools yang bisa digunakan terkait monitoring dan logging (dibagi berdasarkan tools umum dan tools AWS).

  - #### Monitoring and Logging tools

    - #### Umum
      - Prometheus 
      - Elastic Stack
      - Dynatrace
    - #### AWS
      - AWS X-Ray
      - Amazon CloudWatch


# Kisah Implementasi DevOps


## Pengantar Kisah Implementasi DevOps
Kita sudah belajar banyak hal soal DevOps, mulai dari Pengenalan DevOps, Prinsip-Prinsip DevOps, hingga Metodologi DevOps.

Namun, mungkin Anda punya pertanyaan pemungkas terkait DevOps yang sudah bergentayangan di benak Anda, “Apakah ada contoh bagaimana implementasi DevOps di suatu perusahaan ternama yang bisa kita jadikan contoh?”

Meskipun Anda sudah mengetahui manfaat-manfaat menerapkan DevOps dan tahu bagaimana cara-cara mengimplementasikannya, pasti pertanyaan itu masih bersarang di pikiran Anda. Nah, untuk itu, di modul ini kita akan membedah sebuah kisah bagaimana perusahaan tersohor nan kondang seperti Amazon mengimplementasikan DevOps di dalam perusahaannya.

Anda harus tahu bahwa mulanya Amazon pun tidak menerapkan DevOps. Akan tetapi, lambat laun akhirnya mereka mentransformasikan struktur perusahaannya agar bisa mengimplementasikan DevOps.

Amazon merupakan salah satu contoh perusahaan yang awalnya menggunakan praktik pengembangan aplikasi tradisional dan kini bermetamorfosis menjadi lebih fleksibel dan efisien dengan bantuan DevOps.



# Transformasi DevOps pada Perusahaan Amazon
Pada awal 2000-an, situs retail amazon.com merupakan website yang memiliki arsitektur monolitik dan dikembangkan melalui praktik pengembangan aplikasi tradisional. Selain itu, struktur perusahaan Amazon pun bersifat hierarkis, yakni terdiri dari tim Development (Developer), Testing (IT Tester atau QA), dan Operational (IT Operations) yang masing-masing terpisah dan tertutup satu sama lain (siloed team). Ditambah, aplikasi (dalam hal ini website amazon.com) di-deploy sebagai satu unit.

Praktik pengembangan aplikasi yang dilakukan oleh Amazon sesungguhnya banyak masalah yang dapat menyulitkan mereka sendiri, seperti:

1. antarkomponen aplikasi saling bergantung satu sama lain,
2. proses QA (Quality Assurance) dilakukan secara manual,
3. proses deployment berlangsung pelik nan rumit,
4. dan lain-lain.

Untungnya, Amazon segera menyadari bahwa proses pengembangan aplikasi mereka terhambat oleh arsitektur aplikasi dan struktur perusahaan. Pada akhirnya menjadi jelas bahwa ada sesuatu yang perlu diubah dan diperbaiki guna meningkatkan kecepatan pengembangan aplikasi dan kelancaran proses deployment. Dengan demikian, Amazon bisa terbebas dari urusan operasional aplikasi yang terus-menerus menghantui mereka dan lebih fokus pada kebutuhan pengguna. Tentu saja ini tidak terjadi dalam semalam, melainkan berproses secara bertahap.

Amazon membentuk tim kecil yang lintas fungsional dan terdiri dari 8-10 orang bernama two-pizza teams (tim dua pizza). Unik ya namanya? Filosofi di balik penamaan two-pizza teams ini ialah Amazon mencoba untuk membuat tim yang tidak lebih besar dari yang bisa diberi makan oleh dua pizza. Pasalnya, semakin kecil tim, semakin baik kolaborasi akan tercipta. Kolaborasi yang baik tentu akan menghadirkan suasana yang mendukung untuk proses pengembangan aplikasi yang lebih cepat.

Selain itu, Amazon mengubah arsitektur aplikasi menjadi service-oriented (berorientasi layanan). Setiap service (layanan) umumnya berisi satu fungsionalitas bisnis, misal Product Catalog service, Shopping Cart service, atau Order service.

Two-pizza teams ini pun diselaraskan dengan beberapa service tersebut. Mereka diberikan kepemilikan sehingga dapat mengembangkan setiap service secara mandiri.

Dengan cara ini, setiap tim secara konsisten dapat menemukan dan mengeliminasi redundansi dalam proses mereka yang akhirnya mampu mempercepat proses pengembangan aplikasi. Ini merupakan suatu kemajuan.

Akan tetapi, Amazon tahu bahwa mereka bisa berbuat lebih banyak. Mereka menyadari bahwa proses yang manual, penyerahan kode dari satu orang ke orang lainnya, dan siklus perilisan aplikasi yang mereka pakai masih menyebabkan delay (penundaan).

Amazon ingin menghadirkan aplikasi, penambahan fitur, dan pembaruan dengan lebih cepat ke pengguna. Alhasil, arsitektur monolitik yang sebagian masih mereka gunakan selama ini benar-benar diubah menjadi service-oriented sepenuhnya dan kemudian segera menjadi microservice.

Tak hanya itu, Amazon juga membangun dan mengadopsi tools untuk memvisualisasikan dan mengotomatisasi proses perilisan perangkat lunak mereka, mulai dari pengecekan kode, pengujian, hingga deploy ke production. Yakinlah, pemantauan selama proses pengembangan hingga setelah rilis akan memberikan dampak baik kepada tim, salah satunya berupa kepercayaan diri. Segera, tim akan sanggup merilis perangkat lunak secara independen, lebih cepat, dan andal.



# Hikmah dari Transformasi DevOps pada Perusahaan Amazon
Amazon–dan tentu perusahaan-perusahaan lain–telah beralih dari praktik pengembangan aplikasi tradisional yang telah mereka bangun dan lakukan bertahun-tahun ke kultur, praktik, dan tools DevOps. Mesti itu bukan perjalanan yang mudah dan singkat. Perlu upaya dan perjuangan serempak agar perusahaan mampu mengimplementasikan DevOps dan akhirnya mengenyam manfaat-manfaat yang semula tak dirasa.

Amazon telah membuktikan bahwa dengan DevOps, perusahaan mereka dapat berinovasi, menghadirkan produk, dan tumbuh lebih cepat daripada perusahaan lain yang menggunakan praktik pengembangan aplikasi tradisional. Dengan cara ini, Amazon dapat melayani pelanggan mereka dengan lebih baik dan bersaing lebih efektif di pasar.

Namun, terlepas dari semua itu, ada satu pertanyaan yang mungkin masih berkutat di kepala Anda, “Pasti akan terjadi banyak perubahan di perusahaan saya, lantas dari mana saya harus memulai semua ini?”

Praktik terbaik yang perlu Anda lakukan adalah dengan mengambil langkah kecil terlebih dahulu.

Lihat dan amati kembali perusahaan Anda lebih dalam. Mungkin Anda sebenarnya sudah siap secara kultur dan hanya perlu menerapkan praktik dan tools DevOps saja. Atau sebaliknya, bisa jadi Anda sama sekali belum siap secara kultur, yang artinya Anda harus evaluasi dan mulai mendorong terciptanya kultur DevOps ini.

Akan tetapi, bila perusahaan Anda ternyata sudah siap segalanya. Mungkin Anda bisa mulai dengan membuat CI/CD Pipeline, misal dengan menggunakan layanan dari AWS seperti AWS CodePipeline (sudah kita bahas sebelumnya).