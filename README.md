# Embedded-System-Jobsheet-1-1
Ayudya Sawitri

TE-3B/4.31.20.1.05

JARINGAN SENSOR NIRKABEL MENGGUNAKAN ESP-NOW

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

![image](https://user-images.githubusercontent.com/121160856/210812724-4346179c-6dd4-4774-b41c-04f2815c7375.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166115-6b5bd888-23f0-487b-96c4-0f341a103da9.png)

Tx-Rx tinggi 1 meter jarak 1 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210812456-678d5da3-4ccd-49e8-8d82-6b99a583e6dd.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210812402-24bf6bce-8054-46e1-bb75-7dccaf9b8512.png)

Rx-Tx Ground 2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210812264-b27c1f69-a848-4c7c-bcdb-166475886bce.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210812213-3975515e-9237-4f25-8370-2cd35f84b339.png)

Tx-Rx tinggi 30 cm jarak 2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210812044-85950a42-b834-4d8e-995e-0a977a3e8d2d.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210811971-2384e8d4-6b4e-4b04-a4d5-ce06f042d63c.png)

Tx-Rx tinggi 1 meter jarak 2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210811756-5da6f9cc-143e-4b1c-9a66-d7caa7312049.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166252-5c7781d4-4e63-47dd-bac6-f03013b35d7b.png)

Tx-Rx ground 3 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210811653-5d3701ce-2997-4511-89d2-fe3ea20adec7.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210802301-6fbf092e-e790-4252-b714-1f13c2b3dd09.png)


C. One-Way, One-to-Many Communication

Tx-Rx tinggi 30cm jarak 3 Meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210811539-c1813aff-9386-434e-8523-584948450bf2.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166317-9afc9320-dc2c-4d3c-92a6-6642a3a39e8e.png)


Tx-Rx tinggi 1 meter jarak 3 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210811270-74fdf26f-7d06-4ebd-96ff-6523140962aa.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166349-1e16b3cc-ab33-465a-88d1-55a691b917f1.png)

Tx-Rx Ground 4,2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810979-f4843ac2-697a-4a7a-a2d9-c43baecee7c5.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166376-869772d8-e414-4843-933c-25755ba5083a.png)

Tx-Rx tinggi 30 cm jarak 4,2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810886-45fd9f2b-8e20-4914-82b3-93f82fa75c37.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166401-64828c7e-f082-477e-98a5-b3c507bee45e.png)

Tx-Rx tinggi 1 meter jarak 4,2 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810725-26f20b88-1d87-4f29-a3a7-645b6e5fd038.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166422-41331d56-c8ff-498e-9f4a-ff5c041ee0dd.png)

Tx-Rx ground 5,4 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810617-4b53b098-0c5b-436e-8164-b602b1fb8e17.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166446-c347927a-57c1-483d-9112-d438c7dd1b93.png)

Tx-Rx tinggi 30 cm jarak 5,4 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810432-e3edd8be-7283-43c3-a803-7b5e137817b7.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166473-a6277c4d-d7b2-47c6-9815-5902a1f9c547.png)

Tx-Rx tinggi 1 meter jarak 5,4 meter

Sender (pengirim)

![image](https://user-images.githubusercontent.com/121160856/210810314-d86f8572-3aa3-42fe-92b1-f0a051719cde.png)

Receiver (penerima)

![image](https://user-images.githubusercontent.com/121160856/210166498-9b033e1d-c2fb-439d-b95f-f4142eb63706.png)

a) Mengirim Pesan yang Sama Ke Beberapa Board ESP32

MAC Address Sender (Ayudya & Salist) : 24:6F:28:2B:6D:D8 

MAC Address Receiver 1 (Satria & Adika) : 24:6F:28:02:C3:1C 

MAC Address Receiver 2 (Fariz & Josandy) : 24:6F:28:95:D5:80

Sender (Ayudya & Salist)

![image](https://user-images.githubusercontent.com/121160856/210808620-4453099f-db08-4a2c-adfa-c73d1efb238b.png)

Receiver 1 (Satria & Adika)

![image](https://user-images.githubusercontent.com/121160856/210808748-1ece70a2-7359-482e-b20e-d5f1cc6d1881.png)

Receiver 2 (Fariz & Josandy)

![image](https://user-images.githubusercontent.com/121160856/210808863-ed6eb6c4-2b44-42ad-9af7-09146d8aebb0.png)


D. One-Way, Many-to-One Communication 

MAC Address Sender 1 (Fariz & Josandy) : 24:6F:28:95:D5:80 

MAC Address Receiver (Ayudya & Salist) : 24:6F:28:2B:6D:D8

Sender 1 (Fariz & Josandy)

![image](https://user-images.githubusercontent.com/121160856/210807846-b44c2b1c-deb8-4fd3-9e83-a5fd21274504.png)

Receiver (Ayudya & Salist)

![image](https://user-images.githubusercontent.com/121160856/210807768-34989d57-76e9-4058-b160-daee1768bd2f.png)


E. Two-Way Communication Pengecekan Sensor menggunakan DHT22

![image](https://user-images.githubusercontent.com/121160856/210166735-a7d38c38-afd7-42aa-b500-4bd55f652de9.png)

![image](https://user-images.githubusercontent.com/121160856/210166746-547c61ee-ddfa-4a52-94a8-cb4385cc99ef.png)

