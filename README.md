# Telegram

INSTALASI
Open Terminal OpenWRT

opkg update
opkg install git
opkg install git-http
opkg install php8-cli
opkg install php8-mod-curl
git clone https://github.com/agentvaedah/Telegram &&  chmod +x Telegram/src/plugins/*.sh


Buka File Manager 
Folder Root Untuk mengganti ID BOT

Buka Teminal OpenWRT
cd Telegram

Memulai Bot
php8-cli index.php

untuk starting bot
*/5 * * * * cd XppaiWRT && php8-cli index.php

