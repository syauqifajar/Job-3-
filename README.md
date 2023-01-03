# Job-3-
Jobsheet 3 Embedded System  TOPOLOGI JARINGAN LOKAL DAN WIFI

A. ALAT DAN BAHAN

1) ESP32
2) Breadboard
3) Kabel jumper
4) Sensor DHT 11, RFID
5) LED (5) dan Push Button (3)
6) Servo
7) Resistor 330,1K, 10K Ohm (@ 3)

B. TEORI SINGKAT

Wireless Fidelity atau yang lebih awam kita sebut wifi adalah suatu teknologi yang menggunakan gelombang radio dalam rentang 2,4GHz sampai dengan 5GHz
untuk menghubungkan perangkat seperti PC/laptop, smartphone, dan perangkat microcontroller seperti ESP32 dan ESP8266 ke jaringan lokal wireless untuk bisa
mengakses internet. Untuk dapat melakukan akses internet tersebut,makaperangkat elektronik diatas perlu berada dalam satu titik akses atau hotspot
jaringan nirkabel sehingga terhubung dengan wifi. Pada umumnya jaringan wifidapat menjangkau hingga 20 meter didalam ruangan dan lebih dari 20 meter untuk
di luar ruangan. Pada awal kemunculannya, wifi hanya digunakan sebagaiperangkat nirkabel pada jaringan LAN (Local Area Network) akan tetapi karena
pesatnya teknologi di zaman sekarang wifi menjadi kebutuhan sehari-hari untukakses jaringan internet dan IoT.Berbagai data yang kita minta atau kirimkan melalui wifi didistribusikanmelalui gelombang radio di udara. Supaya data tersebut bisa terbaca maka harusada yang namanya wireless adaptor yang menghubungkan ke wifi. Gelombang
radio yang berwujud sinyal ini lalu dikirim menuju router yang fungsinya untukmemecahkan kode. Setelah terbaca maka data dikirim ke jaringan internet yang memanfaatkan koneksi ethernet. Karena jaringan wifi ini bekerja dua arah makatiap data yang diterima dalam waktu yang sama menjadi kode pada tiap paket datalalu dikirim kembali dalam bentuk sinyal radio yang diterima adaptor komputernirkabel.



C. LANGKAH PERCOBAAN

Percobaan a.  ESP32 Wi-Fi Modes dan Wifi-Scan

1. run program pada file job3_A



Hasil Percobaan :

![A](https://user-images.githubusercontent.com/121158751/208882954-e5ec10ea-b95a-4ad0-a2d9-7826ba4c7adb.jpg)


Pada percobaan pertama ESP32 berhasil mendeteksi jaringan WI-FI yang tersedia

Percobaan b. Menghubungkan ESP32 dengan Jaringan Wi-Fi

![B](https://user-images.githubusercontent.com/121158751/208883010-e5dca2c5-7f23-43ac-8343-23e899844e1a.png)


Berdasarkan data perocbaan diatas dapat dilihat bahwa ESP32 berhasil terkoneksi dengan salah satu jaringan WI-FI

Percobaan c.  Menghubungkan Kembali (Re-connect) ESP32 dengan Jaringan Wi-Fi

![C](https://user-images.githubusercontent.com/121158751/208883067-bc574e16-f1e6-42dd-a2d2-7feacebac499.png)


Pada percobaan di atas dilakukan percobaan unntuk mengkoneksikan ulang ESP dengan jaringan wifi

Percobaan d.  Mengganti Hostname ESP32

![D](https://user-images.githubusercontent.com/121158751/208883101-ba38a56f-9baa-4846-ada8-995252121303.png)


Pada percobaan di atas yaitu mencoba untuk mengganti nama hostname ESP
