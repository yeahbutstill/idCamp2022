# Rangkuman Praktik DevOps


## Pengantar Praktik DevOps
Kita suah membedah secara tuntas mengenai metodologi DevOps melalui CALMS Framework. Kini kita akan menyambangi materi lain mengenai bagaimana sebenarnya DevOps dipraktikkan supaya Anda mendapat gambaran dengan lebih jelas.

Anda harus paham terlebih dahulu bahwa poin-poin yang tadi kita bahas pada modul CALMS Framework akan mengarah pada praktik DevOps yang merampingkan dan meningkatkan siklus pengembangan aplikasi agar bisa menyajikan update (pembaruan) lebih sering secara andal seraya menjaga stabilitas infrastruktur (seperti server).

Ini pada akhirnya berujung pada dua hal praktis nan penting, yakni DevOps pipeline dan DevOps tools. Kita akan bahas ini lebih mendalam di submodul berikutnya. Yuk, lanjut!



## DevOps Pipeline
DevOps Pipeline (atau biasa disebut juga sebagai CI/CD Pipeline) merupakan serangkaian proses dan tools terotomatisasi yang memungkinkan Developer dan IT Operations untuk bekerja secara kohesif untuk men-deploy kode ke lingkungan production.

Mari kita bedah setiap tahapan pada DevOps Pipeline satu per satu.

- Code
Pada tahap ini, tim Developer menulis dan mengembangkan kode aplikasi dalam bahasa pemrograman tertentu, entah itu Java, JavaScript, Python, C#, dsb. Selepas kode siap, Developer pun kemudian mengirimkan/mengunggah (push) kode yang telah ditulis ke sebuah lokasi terpusat, umumnya adalah Git repository.

- Build
Selepas kode di-push ke repository dan dipastikan aman untuk lanjut ke fase berikutnya, kode tadi lantas dieksekusi melalui proses build. Usai semua proses build sukses, barulah kita bisa masuk ke fase berikutnya.

- Test
Tahapan berikutnya adalah test alias pengujian. Di sini, artifact yang sedianya sudah dibuat akan diuji apakah memenuhi persyaratan fungsional, kinerja, desain, dan implementasi yang ditentukan atau tidak. Setelah semua pengujian berhasil lolos, tahapan selanjutnya pun dimulai.

- Release
Di fase ini, artifact yang telah lolos pengujian kemudian dikemas/dibungkus dengan nomor versi (version number) tertentu sebelum nanti akhirnya di-deploy.

- Deploy
Usai diberi nomor versi, artifact akan di-deploy ke target environment/lingkungan (kumpulan sumber daya–seperti server, dll–untuk meng-hosting aplikasi) yang sesuai, entah itu ke lingkungan test, staging, alpha, beta, atau production sekalipun.

- Monitor
Dalam tahap ini, umumnya aplikasi sudah di-deploy ke lingkungan production dengan sempurna sehingga bisa dinikmati oleh pengguna. Oleh karenanya, kita perlu memonitor aplikasi agar bisa mendeteksi error ataupun kejanggalan dengan cepat dan secara tanggap langsung memperbaikinya.

Jika terjadi kegagalan di salah satu tahapan, proses yang tengah dilakukan akan dihentikan sehingga tak bisa lanjut ke fase berikutnya.

Selain itu, saat kita belajar tentang DevOps pipeline atau CI/CD pipeline, maka akan erat kaitannya pula dengan istilah-istilah seperti Continuous Integration, Continuous Delivery, dan Continuous Deployment. Apa sih perbedaan mendasar di antara ketiganya?

Mari kita bedah ketiganya satu per satu.

- Continuous Integration
Continuous integration (CI) merupakan praktik pada proses pengembangan aplikasi di mana Developer dengan rutin dan teratur memasukkan (commit) atau menggabungkan (merge) setiap perubahan kode (code changes) mereka ke sebuah repositori terpusat (central repository), setelah itu proses build dan test secara otomatis pun dijalankan.


- Continuous Delivery
Continuous delivery (CD) adalah praktik pada proses pengembangan aplikasi di mana perubahan kode (code changes) secara otomatis dipersiapkan sebelum nantinya dikirim ke lingkungan production.

    Continuous delivery merupakan teknik lanjutan dari continuous integration. Jika di CI hanya sampai proses build dan unit test, di CD ini prosesnya hingga deploy semua perubahan kode ke lingkungan testing, staging (pre-production), dan/atau production. Namun, untuk bisa men-deploy ke production, perlu melalui persetujuan manual (manual approval) terlebih dahulu, entah itu oleh Developer yang lebih senior, manajer, atau siapa pun yang berhak.


- Continuous Deployment
Continuous delivery dan continuous deployment pada hakikatnya adalah proses yang “serupa tapi tak sama”. Perbedaannya, continuous delivery memiliki proses persetujuan manual (manual approval) sebelum aplikasi di-deploy ke production, sementara continuous deployment tidak ada.

Jadi, dengan continuous deployment, proses deploy aplikasi ke lingkungan production berlangsung secara otomatis tanpa ada persetujuan eksplisit dan intervensi manusia.



## DevOps Tools
Dalam mendukung kesuksesan praktik DevOps di suatu perusahaan, ada beberapa kategori best practice yang perlu kita perhatikan berikut dengan tools yang sesuai untuk menerapkannya (akan dibagi antara tools yang bersifat umum dan AWS).



### Komunikasi dan Kolaborasi
Berikut adalah beberapa tools yang bisa membantu mengimplementasikan komunikasi dan kolaborasi antartim di perusahaan.

- #### Platform komunikasi dan kolaborasi terpadu
    Berikut adalah beberapa contoh platform komunikasi dan kolaborasi terpadu (dibagi berdasarkan tools umum dan tools AWS).

| Umum              | AWS          |
|-------------------|--------------|
| Microsoft Teams   | Amazon Chime |
| Slack             |              |
| Workplace         |              |
| Cisco Webex Teams |              |


- #### Cloud
    Alih-alih harus membeli dan memelihara perangkat-perangkat server secara fisik, Anda bisa dengan mudah membuat suatu environment (yang berisi server, jaringan, penyimpanan, dll) secara on-demand (sesuai permintaan) menggunakan cloud provider seperti AWS.

- #### IDE
    Berikut adalah beberapa contoh IDE yang mendukung collaboration tool(dibagi berdasarkan tools umum dan tools AWS).

| Umum                                    | AWS        |
|-----------------------------------------|------------|
| Visual Studio dengan fitur Live Share   | AWS Cloud9 |
| Intellij IDEA dengan fitur Code With Me |            |




- #### CI/CD
    Dalam poin CI/CD ini, tools yang digunakan dibagi menjadi beberapa kategori berdasarkan siklus DevOps pipeline.

  - ##### Code
    Berikut beberapa contoh version control system yang bisa Anda pakai (dibagi berdasarkan tools umum dan tools AWS).

    | Version Control System |                |
    |------------------------|----------------|
    | Umum                   | AWS CodeCommit |
    | GitLab                 |                |
    | GitHub                 |                |
    | BitBucket              |                |


  - ##### Build
    Berikut beberapa contoh tools yang digunakan pada proses build (dibagi berdasarkan tools umum dan tools AWS).

    | Build Tools   |               |
    |---------------|---------------|
    | Umum          | AWS           |
    | Jenkins       | AWS CodeBuild |
    | AWS CodeBuild |               |
    | Travis CI     |               |


- ##### Test
Tahapan test ini sebenarnya tergantung. Apabila sekadar unit test, maka itu bisa dilakukan saat proses build berlangsung. Namun, jika ingin melakukan load testing, kita perlu men-deploy-nya terlebih dahulu ke lingkungan testing dengan bantuan AWS CodeDeploy. Opsi lain, jika Anda menginginkan suatu pengujian yang spesifik, bisa juga memanfaatkan third-party tools dan mengintegrasikannya dengan AWS.


- ##### Release
Kode aplikasi yang telah lolos pengujian kemudian disimpan ke repository, registry, atau storage dalam bentuk software packages, container image, dsb., dengan diberi nomor versi tertentu yang menandakan bahwa aplikasi sudah final dan siap di-deploy.

Apabila artifact yang dimaksud berbentuk compressed file, kita bisa menaruhnya di object storage seperti Amazon S3. Akan tetapi, jika berbentuk container image, berikut adalah contoh tools yang bisa digunakan (dibagi berdasarkan tools umum dan tools AWS).

| Container Image Registry tools |            |
|--------------------------------|------------|
| Umum                           | AWS        |
| Docker Hub                     | Amazon ECR |


- ##### Deploy
Berikut adalah beberapa contoh tools yang bisa digunakan untuk deploy aplikasi (dibagi berdasarkan tools umum dan tools AWS).

| Deployment Tools |                       |
|------------------|-----------------------|
| Umum             | AWS                   |
| Heroku           | AWS CodeDeploy        |
| Netlify          | AWS Elastic Beanstalk |
| GitHub Pages     |                       |



- ##### Monitor
Berikut adalah beberapa contoh tools yang bisa digunakan untuk memantau aplikasi (dibagi berdasarkan tools umum dan tools AWS).

| Monitoring Tools |                   |
|------------------|-------------------|
| Umum             | AWS               |
| Prometheus       | AWS X-Ray         |
| Elastic Stack    | Amazon CloudWatch |
| Dynatrace        |                   |



AWS CodePipeline adalah layanan continuous delivery yang memungkinkan kita untuk membuat model, memvisualisasikan, dan mengotomatiskan langkah-langkah yang diperlukan untuk merilis perangkat lunak. Dengan layanan ini, kita bisa mengonfigurasi tahapan-tahapan pada CI/CD pipeline sehingga memudahkan dalam proses pengembangan aplikasi.



- ##### Infrastructure as Code
Dalam pembahasan Infrastructure as Code ini, umumnya terdapat 2 kategori yang perlu kita bedah, yakni infrastructure automation dan configuration management.

- ##### Infrastructure automation
Infrastructure automation dalam hal ini adalah pembuatan infrastruktur dan sumber daya sejenis secara otomatis hanya dengan menggunakan kode. Dengan cara ini, baik Developer maupun IT Operations dapat berinteraksi dengan infrastruktur secara terprogram dalam skala besar, tanpa perlu mengonfigurasinya secara manual.

Berikut adalah contoh tools yang bisa digunakan untuk kategori infrastructure automation (dibagi berdasarkan tools umum dan tools AWS).

| Infrastructure automation tools |                    |
|---------------------------------|--------------------|
| Umum                            | AWS                |
| Terraform                       | AWS CloudFormation |


- ##### Configuration management
Berikut adalah beberapa contoh tools yang bisa digunakan pada kategori configuration management (dibagi berdasarkan tools umum dan tools AWS).

| Configuration management tools |              |
|--------------------------------|--------------|
| Umum                           | AWS          |
| Chef                           | AWS OpsWorks |
| Puppet                         |              |
| Ansible                        |              |



- ##### Arsitektur Microservices
Ketika berbicara tentang microservice, akan ada dua topik hangat yang perlu kita bahas, yakni container dan serverless.

- ##### Container
    Berikut adalah beberapa contoh tools yang bisa digunakan terkait container orchestration tools (dibagi berdasarkan tools umum dan tools AWS).

| Container Orchestration tools |            |
|-------------------------------|------------|
| Umum                          | AWS        |
| Kubernetes                    | Amazon ECS |
| OpenShift                     | Amazon EKS |
| Nomad                         |            |



- ##### Serverless
    Berikut adalah beberapa contoh tools yang bisa digunakan terkait serverless function as a service (dibagi berdasarkan tools umum dan tools AWS).

| Serverless Function as a Service tools |            |
|----------------------------------------|------------|
| Umum                                   | AWS        |
| Serverless                             | AWS Lambda |
| OpenFaaS                               |            |
| OpenWhisk                              |            |




- ##### Monitoring dan Logging
Berikut adalah beberapa contoh tools yang bisa digunakan terkait monitoring dan logging (dibagi berdasarkan tools umum dan tools AWS).

| Monitoring and Logging tools |                   |
|------------------------------|-------------------|
| Umum                         | AWS               |
| Prometheus                   | AWS X-Ray         |
| Elastic Stack                | Amazon CloudWatch |
| Dynatrace                    |                   |


