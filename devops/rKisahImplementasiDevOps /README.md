# Rangkuman Kisah Implementasi DevOps


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