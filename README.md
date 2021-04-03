# Dumbways.Jabal.github.io

Soal Nomor 1
Dalam sebuah perusahaan Andi bekerja sebagai DevOps, jelaskan menurut pendapatmu definisi tentang DevOps dan seberapa penting DevOps di suatu perusahaan serta gambarkan flow DevOps dari development hingga ke production?
Bobot: (5)

DevOps adalah kombinasi dari filosofi budaya, penerapan, dan peralatan yang meningkatkan kemampuan organisasi untuk memberikan aplikasi dan layanan dalam kecepatan yang tinggi: mengembangkan dan meningkatkan produk dalam waktu yang lebih cepat dari organisasi yang menggunakan pengembangan perangkat lunak dan proses pengelolaan infrastruktur tradisional. Kecepatan ini memungkinkan organisasi untuk melayani pelanggan mereka dengan lebih baik dan berkompetisi dengan lebih efektif di pasaran. 
(sumber: https://aws.amazon.com/devops/what-is-devops/)

https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/01%20step%201.png

Devops sangat penting bagi perusahaan, salah satu best practices dalam DevOps yaitu melakukan update produk yang kecil dan cepat. Dalam industri IT, ini bisa disebut dengan minor / patch update. Dengan melakukan update produk yang kecil, organisasi/perusahaan dapat melakukan inovasi lebih cepat bagi produknya, juga dapat melakukan rollback dengan mudah jika ditemukan bug yang tidak ter-cover oleh automated testing maupun tim QA. Dengan praktek ini, Organisasi/Perusahan dapat me-monitor produk dan mendapatkan data yang paling berharga yaitu data pengguna. (sumber: https://medium.com/programmer-geek/apa-itu-devops-dca7c1c2dc92)

https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/01%20step%202.png


Soal Nomor 2
Sebutkan perbedaan antara AWS dan OpenStack? Sebutkan secara jelas list tersebut!
Bobot: (10)
AWS
 Ini adalah platform di mana kita dapat melakukan sebagian besar segala jenis proses. Ini bisa penyimpanan, unit pemrosesan, platform Big Data, platform ML dll. Untuk platform ini, itu berubah jumlah yang sangat sedikit, siapa pun mampu sesuai dengan kebutuhan mereka. Tetapi aws tidak opensource, cara kerjanya secara internal, kita tidak bisa tahu. Kami hanya dapat menggunakannya sebagai pengguna. Ini membuat perbedaan dengan OpenStack.

OpenStack
OpenStack-Ini juga merupakan platform di mana kita dapat melakukan tugas yang disediakan aws. Tapi OpenStack adalah platform opensource. Kita dapat membuat cloud kita sendiri dan menyesuaikan hal-hal sesuai dengan kebutuhan kita. Kita bisa melihat cara kerjanya secara internal.

Perbedaan layanan AWS dan OpenStack:
    1) Computation
       Untuk menghitung berarti menjalankan aplikasi apa pun di server virtual. Anda harus menyediakan CPU dan perangkat keras lain yang diperlukan bersama dengan aplikasi sistem operasi yang telah diinstal sebelumnya (atau tidak). Pada keduanya, pengguna OpenStack dan AWS dapat mengunggah image mereka sendiri. AWS memiliki EC2, yang merupakan jaringan virtual yang dapat diskalakan dengan analitik big data berbasis Xen dan EMR Hadoop. OpenStack, di sisi lain, membanggakan infrastruktur Iaas. Ini menskalakan secara horizontal dan dirancang untuk menskalakan pada perangkat keras tanpa persyaratan khusus.
    2) Networking
       Penting untuk menghubungkan server Anda ke server internal dan eksternal lainnya. Ini pada dasarnya berarti menghubungkan pengguna ke server virtual. Ketika fasilitas semacam itu ditawarkan kepada admin, dia harus memiliki hak untuk mengetahui siapa yang memiliki akses ke jaringan. AWS memiliki DNS rute 53 yang dapat diskalakan, Amazon ELB (Elastic Load Balancing), dan, Amazon VPC (Virtual Private Cloud) yang memperluas kemampuannya untuk terhubung ke server perusahaan. AWS akan mengalokasikan alamat IP pribadi untuk instans yang berjalan di DHCP dan ELB hanya membantu dalam mendistribusikan lalu lintas masuk ke instans Amazon EC2. Openstacks LBaas dan jaringan datar VLAN memungkinkan otomatis serta manajemen manual alamat ip dan jaringan. Anda memiliki kekuatan untuk membuat fungsi dan jaringan.
    3) Identity 
       Keystone untuk OpenStack dan IAM untuk AWS memutuskan fungsi identitas. Server identitas memungkinkan Anda untuk memiliki kekuatan atas siapa yang akan mengakses cloud Anda dengan menerapkan autentikasi multifaktor. Ini juga dapat diintegrasikan dengan beberapa penyedia eksternal seperti AD atau LAPD. Ini adalah layanan utama yang harus ditawarkan OpenStack dan AWS. Semua layanan lain berjalan sesuai dengan layanan dan aplikasi ini dan merupakan subset untuk fungsi utama.
    4) Security
       Istilah ini pada dasarnya berarti kontrol akses atas server dan mesin Virtual. Setiap kali instans diluncurkan, grup keamanan terpisah harus tersedia untuk dilampirkan ke instans tersebut. Keamanan OpenStack tertinggal dari AWS dalam hal kondisi ini dan mungkin tidak merender array layanan yang diinginkan saat diperlukan. AWS menanamkan pendekatan yang lebih pribadi untuk mendapatkan akses ke instans yang dikunci oleh pengguna menjadikannya pemenang yang jelas antara AWS Vs OpenStack.
    5) Storage
       Anda memerlukan dua jenis unit penyimpanan saat anda datang ke komputasi cloud – Block Storage dan Object Storage. Penyimpanan blok digunakan untuk menetapkan nilai ke server virtual untuk meningkatkan kapasitas mereka saat mencapai ambang batas serta mencadangkan server virtual. Penyimpanan objek berisi file media, gambar, dan sebagainya. AWS memiliki S3 dan OpenStack memiliki Swift sebagai layanan penyimpanan blok mereka sementara Cinder dan EBS adalah mitra penyimpanan objek mereka.
(Sumber: https://www.geeksforgeeks.org/aws-vs-openstack/)


Soal Nomor 3
Ketika sebuah aplikasi yang ingin kita jalankan menggunakan port yang sama dengan aplikasi lain, apa yang harus kita lakukan agar kedua aplikasi tersebut jalan berdampingan? Rekam menjadi sebuah video!
Bobot: (5)

Soal Nomor 4
CI/CD (Continuous Integration/Continuous Development) merupakan hal yang sering ditemui oleh seorang DevOps. Menurut pendapatmu mengapa CI/CD diperlukan dan berikan gambaran diagram kerjanya (Workflow)!
Bobot: (5)
Karena jika terjadi kesalahan/bug dalan build/test, Development Team dapat dengan cepat melakukan perbaikan code sehingga kesalahan yang terjadi dapat di tanggulangi dan mengurangi waktu untuk melakukan validasi sebuah update. (CI)
Pada saat Continuous Delivery dijalankan, tim Software Developer akan selalu memiliki sebuah bagian aplikasi atau aplikasi itu sendiri yang siap untuk di deploy ke environment production. Ini dilakukan untuk membantu mengurangi biaya, waktu, dan risiko dalam perubahan aplikasi dengan memungkinkan untuk menambah update lebih banyak untuk aplikasi yang sedang berjalan. Sebuah proses penyebaran langsung dan berulang sangat penting dalam Continuous Delivery. (CD)
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/04%20step%201.jpeg
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/04%20step%202.png


Soal Nomor 5
Buatlah script sederhana untuk membuat user baru di linux dan menjalankan sudo apt update dan sudo apt upgrade menggunakan file .sh ? Rekam menjadi sebuah video!
Bobot: (10)
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/05.mkv


Soal Nomor 6
Kita sering mengenal platform yang bernama GitLab, Github dan Bitbucket, ketiga platform tersebut memiliki keunggulan masing-masing yang mendukung pekerjaan seorang DevOps, menurut pendapat kamu dari ketiga platform tersebut berikan alasan kenapa harus memilih 1 di antara yang lain?
Bobot: (5)
Menurut saya dari ketiga platform tersebut, saya memilih Gitlab karena menyediakan layanan yang gratis untuk unlimited user dan unlimited private repositori dan mendapat akses penuh untuk kebanyakan fitur bagus yang disediakan Gitlab termasuk built in Docker Registry dan integrated CI pipeline untuk projek, syntax theme, dan integrasi 3rd party.

Soal Nomor 7
Aplikasi monitoring apa yang dapat digunakan untuk memonitoring server dengan skala besar? Sertakan gambaran umumnya 
Bobot: (10)
Monitoring server adalah kegiatan memantau sumber daya sistem server seperti: penggunaan CPU (CPU Usage), konsumsi memori (Memory RAM Consumption), jaringan, penggunaan disk (disk usage), dan lain sebagainya. Lewat server monitoring, Anda dapat memperoleh data yang berkaitan dengan sistem operasi Anda. Misalnya, melihat cara kerja sistem Anda. Hal lainnya yang tak kalah penting, Anda juga dapat memantau keamanan server Anda. 
Ganglia adalah monitoring sistem open-source (BSD License) yang didesain khusus untuk sistem komputerisasi berperforma tinggi seperti cluster dan grid. Tool ini menghasilkan data analisis yang terukur dan mudah didistribusi. 
Sistem monitoring ini memanfaatkan teknologi yang banyak digunakan seperti XML untuk representasi data, dan XDR untuk transportasi data. Salah satu tujuannya adalah untuk merekayasa struktur data dan algoritma untuk memaksimalkan efisiensi. 
Keunggulan:
Sebagai platform monitoring yang solid, Ganglia mendukung banyak operating system dan prosesor. Cluster besar di seluruh di dunia menggunakan platform ini, terutama di lingkungan universitas. 
(Sumber: https://www.niagahoster.co.id/blog/monitoring-server/#:~:text=Monitoring%20server%20adalah%20kegiatan%20memantau,besar%20bergantung%20pada%20performa%20server.)

Soal Nomor 8
    1. 
Buatlah sebuah aplikasi statis seperti jekyll atau hugo, kemudian upload aplikasi tersebut dari komputer lokal ke github pages (https://pages.github.com), agar aplikasi tersebut dapat diakses secara publik.Contoh : sgnd.github.io Sertakan screenshot step by step-nya atau record menjadi sebuah video 
Bobot: (5)
1. Install Hugo
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%201.png





2. Create New Project
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%202.png


3. Create theme using git and create new post
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%203.png

4. Run Hugo Server
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%204.png


5. Change the title to “Website Baruku”
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%205.png

6. Tampilan Web
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%206.png


7. https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%207.pngUploading our files to repository github


8. File Uploaded at repository github.com/babalabal/JabalT.github.io
https://github.com/babalabal/Dumbways.Jabal.github.io/blob/main/Images%20and%20Video/08%20step%208.png
