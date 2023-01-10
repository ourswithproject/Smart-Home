# Smart-Home
![image](https://user-images.githubusercontent.com/122025479/211527255-aa959f2e-5e30-461b-9139-bc78c156a648.png)
Smart Home merupakan rumah pintar dengan sistem kendali perangkat elektronik menggunakan smartphone.
Smart Home dirancang dengan aplikasi antar muka Blynk, Google Asistant, Webhooks, dan IFTT.
Latar belakang dibuatnya alat ini adalah ketika sedang bepergian keluar rumah, terkadang seseorang lupa untuk mematikan peralatan elektronik seperti lampu, kipas angin, dan air conditioner (AC). Pada sistem rumah pintar ini, pengontrolan peralatan elektronik dapat diaktifkan dan dinonaktifkan menggunakan perintah suara atau menggunakan gawai pengguna walaupun dilakukan dari jarak jauh. 

**Alat dan Bahan :**
Relay
LED Strip
Motor DC
Selenoid Door Lock
LCD 16X2
ESP 8266
Arduino Uno

**Diagram Alir**
![image](https://user-images.githubusercontent.com/122025479/211526576-8f69bc11-74a4-4706-9b45-940c229aa3b5.png)

**Diagram Skematik**

![image](https://user-images.githubusercontent.com/122025479/211526835-3d2bac3f-634a-4d84-b2e5-adf3f3a7df6f.png)

**Cara Kerja**

![image](https://user-images.githubusercontent.com/122025479/211526957-e6863029-6638-46aa-9746-77f979cd621e.png)
Peralatan elektronik dapat diaktifkan melalui perintah suara atau langsung melalui antarmuka Blynk. Perintah suara diterjemahkan menjadi data high atau low menggunakan google assistant, IFTTT, dan webhooks. Data high atau low digunakan oleh Blynk untuk mengaktifkan atau menonatifkan peralatan elektronik dengan memberikan perintah kepada nodeMCU ESP-8266 untuk mengaktifkan atau menonatifkan relay yang telah terhubung ke peralatan elektronik tersebut.

