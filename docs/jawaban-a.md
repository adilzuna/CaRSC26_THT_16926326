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
  ![]()

