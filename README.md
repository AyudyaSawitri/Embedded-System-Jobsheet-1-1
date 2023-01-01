# Embedded-System-Jobsheet-1-1
Ayudya Sawitri

TE-3B/4.31.20.1.05


A. Memperoleh MAC Address ESP32 Receiver

Kemudian ketikkan script program berikut di Arduino IDE

Catat Mac Address ESP32.

![image](https://user-images.githubusercontent.com/121160856/210162792-377d9f20-51d1-4f48-a2bd-7da7d311d2ed.png)

MAC Address yang diperoleh : 24:6F:28:2B:6D:D8 

B. ESP-NOW One-Way Point-to-Point Communication

Setelah ESP32 sender dikonfigurasi, kemudian konfigurasikan ESP32 yang lain sebagai Receiver. ketikkan script program berikut untuk mengkonfigurasi ESP32 sebagai
sender.

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210162886-082a86e7-bb90-4f1d-8d23-7ffd4cf4faa1.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210165859-dc3ab097-a64d-4a68-98a7-a84a174f3120.png)

Aturlah jarak awal komunikasi antara sender dan receiver yaitu 1 meter. Kemudian ubah jarak komunikasi dengan penambahan 1 meter. Data yang dikirim pada tiap iterasi pengujian adalah 10 data. Aturlah tinggi antena atau peletakan ESP32 pada ground level (menempel tanah), 30 cm di atas tanah, dan 1 meter di atas tanah.

Masukkan hasil pengukuran pada kolom berikut dan buatlah analisisnya dengan pendekatan teori freshnel zone.

![image](https://user-images.githubusercontent.com/121160856/210165958-63b9c360-cd10-4f56-a448-340a5167f460.png)

Tx-Rx Ground 1,2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210166062-aa32a6aa-00ae-4a68-a8a1-037333900503.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210165998-43db83ea-8047-4d2f-954e-6df4936a763b.png)

Tx-Rx tinggi 30 cm jarak 1 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210166110-fc0daf0e-6108-4864-a37a-d6cb73fd562b.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166115-6b5bd888-23f0-487b-96c4-0f341a103da9.png)

Tx-Rx tinggi 1 meter jarak 1 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166154-ccbfefe7-259e-4d3c-8b3b-8331af9c0dde.png)

Rx-Tx Ground 2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166173-90892e86-e29b-4203-9a22-cc9bd3ab8b49.png)

Tx-Rx tinggi 30 cm jarak 2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166209-3ac1fefb-56da-4ae7-bf66-eaef7382bc29.png)


Tx-Rx tinggi 1 meter jarak 2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166252-5c7781d4-4e63-47dd-bac6-f03013b35d7b.png)

Tx-Rx ground 3 meter

Sender (pengirim)

gambar

Receiver (penerima)

gambar

C. One-Way, One-to-Many Communication

Tx-Rx tinggi 30cm jarak 3 Meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166317-9afc9320-dc2c-4d3c-92a6-6642a3a39e8e.png)

Tx-Rx tinggi 1 meter jarak 3 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166349-1e16b3cc-ab33-465a-88d1-55a691b917f1.png)

Tx-Rx Ground 4,2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166376-869772d8-e414-4843-933c-25755ba5083a.png)

Tx-Rx tinggi 30 cm jarak 4,2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166401-64828c7e-f082-477e-98a5-b3c507bee45e.png)

Tx-Rx tinggi 1 meter jarak 4,2 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166422-41331d56-c8ff-498e-9f4a-ff5c041ee0dd.png)

Tx-Rx ground 5,4 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166446-c347927a-57c1-483d-9112-d438c7dd1b93.png)

Tx-Rx tinggi 30 cm jarak 5,4 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166473-a6277c4d-d7b2-47c6-9815-5902a1f9c547.png)

Tx-Rx tinggi 1 meter jarak 5,4 meter

Sender (pengirim)

gambar

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166498-9b033e1d-c2fb-439d-b95f-f4142eb63706.png)

a) Mengirim Pesan yang Sama Ke Beberapa Board ESP32

MAC Address Sender (Ayudya & Salist) : 24:6F:28:2B:6D:D8 

MAC Address Receiver 1 (Satria & Adika) : 24:6F:28:02:C3:1C 

MAC Address Receiver 2 (Fariz & Josandy) : 24:6F:28:95:D5:80

Sender (Ayudya & Salist)

gambar

Receiver 1

gambar

Receiver 2

gambar

D. One-Way, Many-to-One Communication 

MAC Address Sender 1 (Satria & Adika) : 24:6F:28:02:C3:1C 

MAC Address Sender 2 (Fariz & Josandy) : 24:6F:28:95:D5:80 

MAC Address Receiver (Ayudya & Salist) : 24:6F:28:2B:6D:D8

Sender 1 (Satria & Adika)

gambar

Sender 2 (Fariz & Josandy)

gambar

E. Two-Way Communication Pengecekan Sensor menggunakan DHT22

![image](https://user-images.githubusercontent.com/121160856/210166735-a7d38c38-afd7-42aa-b500-4bd55f652de9.png)

![image](https://user-images.githubusercontent.com/121160856/210166746-547c61ee-ddfa-4a52-94a8-cb4385cc99ef.png)

