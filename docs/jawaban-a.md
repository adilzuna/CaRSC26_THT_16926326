# Jawaban A
**Nama; Adil**  
**NIM: 16925326**

## 1  
email: zunaadil@gmail.com

## 2  
 a.  
    git clone: untuk mengcopy repository dari github menuju ke file pada device  
               contoh: git clone https://github.com/adilzuna/CaESC26_THT_16925326.git  
    git add: untuk menambahkan file ke repository  
             contoh: git add filex.md  
    git commit: untuk melakukan penyimpanan pada suatu perubahan  
                contoh: setelah melakukan perubahan pada suatu file, kita menuliskan code 'git commit'  
    git merge: untuk menggabungkan 2 atau lebih branch yang ada pada repository  
               contoh: git checkout main  
                       git merge branch1  
   [refference](https://git-scm.com/docs)

b.  
   ![jawaban 2b](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2008.37.17.jpeg)

c.  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2009.43.10.jpeg)  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2010.27.51.jpeg)

d.  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2012.10.09.jpeg)

e.  


## 3  
a.  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2012.39.49.jpeg)

b.  
  * menyiapkan, menyetel dan membuat konfigurasi agar pesawat dapat berkerka dengan optimal  
  * mengunduh dan menganalisan log misi yang telah dibuat oleh autopilot pengguna  
  * merencanakan, menyimpan, dan memuat misi otonom ke dalam autopilot pengguna dengan memasukkan titik arah yang mudah menggunakan Google Maps  
  * Memuat software ke dalam autopilot board   
    [reference](https://ardupilot.org/planner/docs/mission-planner-overview.html)

c.  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-17%20at%2021.47.49.jpeg)
 ## 4  
 a.  
   ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/Screenshot%20From%202026-01-18%2009-56-13.png)  

 b.  
   
   
## 5  
a.  
   Fixed wing: UAV bergerak saat take off dan landing secara horizontal. memiliki ketahanan yang lebih baik, kapasitas muatan yang lebih besar, dan membutuhkan runway untuk melakukan take off dan landing.  

   Rotary wing: UAV bergerak saat take off dan landing secara vertikal. tidak membutuhkan area yang luas untuk runway, gerakan lebih lincah, dan kecepatan yang lebih lambat. Rotary wing UAV juga membutuhkan/menggunakan lebih banyak energi, sehingga memiliki ketahanan yang lebih rendah.

   Hybrid: menggabungkan kemampuan VTOL rotary wing dengan kemampuan penggerak dari fixed wing. UAV ini melakukan take off dan landing secara vertikal, lalu ketika di udara, UAV akan bergerak seperti fixed wing. Terdapat 3 mode pada hybrid UAV, yaitu: mode fixed wing, mode transisi, dan mode helikopter. Hybrid UAV memiliki keselamatan yang lebih baik dibandingkan fixed wing UAV karema kecepatan yang rendah diakibatkan oleh kemampuan VTOL, namun memiliki ketahanan yang ebih rendah dikarenakan menggunakan energi lebih banyak.   
   [reference](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/Comparative_Analysis_of_Fixed-Wing_Rotary-Wing_and.pdf)

b.  
  yaw: pergerakan pesawat menuju kanan dan kiri dengan cara membelokkan ekor pesawat, sehingga pesawat memutar terhadap sumbu yang tegak lurus dengan sayap pesawat.  
  pitch: pergerakkan pesawat ke atas dan ke bawah dengan memainkan gaya angkat yang ada pada sayap dan ekor pesawat. pergerakkan ini dikontrol oleh pilot menggunakan tuas elevator dan pitch axis selalu tegak lurus terhadap titik pusat pesawat.  
  roll: pegerakkan pesawat agar bisa belok ke kanan dan ke kiri dengan cara "menggulingkan" pesawat searah dengan jarum jam atau berlawanan dengan jarum jam. pergerakkan roll dikontrol dengan aileron.  
  [reference](https://calaero.edu/aeronautics/aerodynamics/aircraft-axes-pitch-yaw-roll/)

  airspeed: kecepatan pesawat terhadap angin di sekitar pesawat. biasanya menggunakan unit knots atau km/h.  
  groundspeed: kecepatan pesawat relativ terhadap tanah.  
  [reference](https://monroeaerospace.com/blog/airspeed-vs-groundspeed-whats-the-difference/?srsltid=AfmBOoqohWoNsLuzFkoGqyxCwK3IwzlQnSlu7gMo2VdwJvAmjz3KFCM_)

  HDOP: Indikator seberapa akurat suatu gps atau dgps. perubahan angka pada indikator disebabkan oleh keakuratan posisi horizontal penerima gps dengan satelit geometri. semakin kecil angkanya semakin akurat. [reference](https://www.lerus.com/articles/hdop-horizontal-dilution-of-precision-in-gps-and-dgps-systems.html)  
  RSSI: sensor atau indikator dari seberapa kuat gelombang radio diterima oleh UAV. Menunjukkan jarak dari sumber gelombang.  
  (referenece: Pak, Jeonghyeon & Kim, Bosung & Son, Hyoung. (2025). RSSI-based Autonomous Tracking System for Radio-tagged Flying Insects using UAV with Rotational Antenna. IEEE Access. PP. 1-1. 10.1109/ACCESS.2025.3562007.)  

C.  
  frame: rangka yang digunakan sebagai penampung komponen komponen lain  
  propeller & motor: baling baling beserta motor untuk memberi gaya angkat  
  GPS & GNSS receiver:  satelit navigasi untuk melacak posisi  
  flight controller: otak drone yang mengatur gerak drone dan kestabilan drone  
  sensor utama: mengambil data citrauntuk pemetaan  
  sensor tambahan: menstabilisasi dengan cara menambah data  
  Baterai: sebagai sumber energi  
  GCS: sebagai alat pengendali untuk pilot  
  ![](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/WhatsApp%20Image%202026-01-18%20at%2022.45.56.jpeg)

d.  
  [publikasi](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/6791139.pdf)  
  Pertama tama, dalam publikasi itu menjelasksan mengenai perkembangan perkembangan pada teknologi UAv pada beberapa taun kebelakang. Lalu, pada publikasi tersebut, ia menjelasksan mengenai berbagai jeis perkembangan pada teknologi UAV.  
  * sensor yang lebih maju: sensor ini berguna untuk memberikan data data yang ada di sekitar UAV, yang membuat UAV dapat menavigasi dan berinteraksi dengan lingkungan sekitar secara ootomatis.
  * Algoritma mesin dan visi komputasional: kedua ini membuat pesawat dapat melakukan decision making dan mengeskstrak informasi yang tertangkap pada sensor.
  * teknologi komunikasi dan networking: Ini sangat berguna dalam menghubungkan UAV dengan ground station sehingga dapat terkendali oleh pilot. teknologi ini berkembang seiring berkembangnya telekomunikasi seperti data seluler, wifi, dan sebagainya.
  * tenaga penggerak: tenaga penggerak ini menentukan seberapa banyak energi yang bissa dipakai pada UAV tersebut. teknologi ini berkembang dari engine engine biasa seperti jet engine atau combustion engine hingga adanya bertenaga listrik dan hybrid.
  * sistem flight control: sistem ini berdungsi sebagai otak pesawat yang mengatur segala gerak gerik pesawat. lalu, teknologi ini semakin berkembang hingga teknologi modern menggunakan AI pada sistem tersebut.  
  * sistem navigasi otomatis: sistem ini sangat berguna uagar pesawat dapat melakukan tugas tugasnya dengan otomatis secara aman dan efisien. salah satu perkembangan teknologi ini adalah SLAM, yang dapat membuat map dari lingkungan sekitar pesawat secara real time dan menentukan arah yang tepat.  
  * Kawanan UAV: kawanan UAV adalah salah satu perkembangan teknologi yang dimana kumpulan UAV akan bersatu untuk menyelesaikan suatu misi bersama.
  * sistem pengiriman paket: pengiriman paket dapat menjadi lebih cepat, efisien, dan lebih murah dengan adanya UAV sebagai media pengiriman paket.
  * sistem inspeksi dan perbaikan: dengan berkembangnya teknologi, inspeksi dan perbaikan objek dapat dilakukan dengan lebih efisien menggunakan UAV yang dapat menemukan kecacatan dari objek tersebut. UAV juga dapat menjangkau apa yang mungkin sulit bagi manusia untuk mnejangkau.
  * sistem anti tabrak dan keamanan: sistem ini sangat diperlukan agar suatu misi dapat terjalani dengan aman. slah satu perkembangan teknologi ini adalah sensor LIDAR dan RADAR yang dapat memberikan map #D dan informasi cuaca secara real time.

  perkembangan teknologi sudah menjadikan banyak hal menjadi lebih efisien dan mencapai potensial yang dapat dilakukan.   

## 6  
a.  
  Algoritma A* dan D* adalah algoritma untuk menemukan rute terpendek. Perbedaan A* dan D* hanyalah bahwa D* adalah versi dinamis dari A*. Dinamis pada konteks ini bermaksud bahwa D* dapat menyesuaikan dengan perubahan kondisi di sekitar. A* memiliki kekurangan lamanya waktu untuk menemukan jalan dan dan hanya bisa satu kondisi saja. Sedangkan D*, memiliki kekurangan panjangnya rute yang disebabkan oleh berubahnya atau tidak diketahuinya kondisi lingkungan sekitar. cara A* menemukan rutenya adalah dengan mulai mencari dari starting point hingga ke target. Sebaliknya, D* mencari rute dari target menuju starting point atau reverse dari A*.  
  [reference](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/Optimization_methods_for_A_and_D_algorithms.pdf)  

b.  
  Proportional-Integral-Derivative (PID) adalah sebuah controller untuk meminimalisir error dari sebuah pengukuran. Dalam dunia industri, banyak sekali pengaplikasian dari PID ini. PID dapat diaplikasikan dalam kontrol suhu, kontrol arus, dan kontrol motor. Ini dikarenakan tujuan dari PID sendiri adalah untuk meminimalisir dan membuat pengontrolan menjadi semakin akurat. berdasarkan namanya, PID memiliki 3 komponen, yaitu: Proportional, Integral, dan Derivatif. semua komponen ini bergantung kepada perbedaan antara value set point dengan value asli yang terukur pada saat itu (e(t) = SP - PV). output yang dikeluarkan dari PID sendiri adalah jumlah dari proprtional + integral + derivatif. yang dimana masing masing memiliki konstanta tersendiri. Lalu, proprotional sendiri menggunakan value dari e(t), integral menggunakan hasil integral dari e(t), dan derivatif menggunakan turunan dari e(t). Dikarenakan SP adalah sebuah nilai konstan. maka, turunan dari e(t) hanyalah turunan dari -PV. proprtional sendiri berarti adalah error yang terdapat pada pengukuran pada sistem di saat itu. Integral sendiri mengukur akumulasi error yang ada sehingga kita dapat mengeliminasi error error yang terbilang cukup stabil. Dan derivatif dapat mengukur perubahan perubahan error seiringnya waktu sehingga dapat mengeliminasi value value fluktuatif. akan ada value tambahan untuk bias ketika mode diubah dari manual menjadi otomatis.  
  [reference](https://apmonitor.com/pdc/index.php/Main/ProportionalIntegralDerivative)  

c.  
  Kalman filter adalah algoritma untuk mengestimasi suatu nilai. Kalman filter berguna untuk meminimalisir error pada nilai tersebut. extended kalman filter adalah peluasan dari kalman filter. Kalman filter diatur oleh persamaan linear stokastik. persamaan linear stokastik tersebut adalah 𝑥𝑘 = 𝐶𝑥𝑘−1 + 𝐷𝑢𝑘 + 𝑤k. dimana k adalah waktu nya. kalman filter mengestimasi suatu nilai dengan bentuk loop feedback control. Lalu, persamaan pada kalman filter memiliki 2 bagian, yaitu pembaruan waktu untuk memproyeksikan kondisi saat ini dan pembaruan pengukuran untuk memberikan feedback. Pada extended kalman filter, fungsi stokastik tidak linear (𝑥𝑘 = 𝑓(𝑥𝑘−1, 𝑢𝑘, 𝑤𝑘)). dikarenakan tidak linear, maka penurunan fungsinya berhubungan denga value waktu sebelumnya.  
[reference](https://github.com/adilzuna/CaRSC26_THT_16926326/blob/main/lampiran/Perbandingan_Metode_Kalman_Filter_Extended_Kalman_.pdf)
