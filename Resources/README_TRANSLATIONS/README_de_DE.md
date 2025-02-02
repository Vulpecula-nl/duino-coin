<!-- Translate up to line 118 so far :)
*** Offizielles Duino Coin README
*** by revox, 2019-2021
-->

<p align = "center">
  <a href="https://duinocoin.com">
    <img width="300em" src="https://github.com/revoxhere/duino-coin/blob/master/Resources/ducobanner.png?raw=true" />
  </a>
  <br />
  <a href="https://github.com/revoxhere/duino-coin/blob/master/README.md">
    <img src="https://img.shields.io/badge/English-0097e6.svg?style=for-the-badge" />
  </a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_es_LATAM.md">
    <img src="https://img.shields.io/badge/-Espa%C3%B1ol-ff793f?style=for-the-badge" />
  </a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_zh_CN.md">
    <img src="https://img.shields.io/badge/简体中文-2ed573.svg?style=for-the-badge" />
  </a>
  <a href="https://github.com/revoxhere/duino-coin/blob/master/Resources/README_TRANSLATIONS/README_pl_PL.md">
    <img src="https://img.shields.io/badge/Polski-e66767.svg?style=for-the-badge" />
  </a>
  <br />
  <a href="https://wallet.duinocoin.com">
    <img src="https://img.shields.io/badge/Online Wallet-8e44ad.svg?style=for-the-badge&logo=Web" /></a>
  <a href="https://play.google.com/store/apps/details?id=com.pripun.duinocoin">
    <img src="https://img.shields.io/badge/Android App-e84393.svg?style=for-the-badge&logo=Android" /></a>
  <a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">
    <img src="https://img.shields.io/badge/whitepaper-1abc9c.svg?style=for-the-badge&logo=Academia" /></a>
  <br>
  <a href="https://youtu.be/bFnCdqMke34">
    <img src="https://img.shields.io/badge/Video-Watch-e74c3c.svg?style=for-the-badge&logo=Youtube" /></a>
  <a href="https://discord.gg/kvBkccy">
    <img src="https://img.shields.io/discord/677615191793467402.svg?color=5539cc&label=Discord&logo=Discord&style=for-the-badge" /></a>
  <a href="https://github.com/revoxhere/duino-coin/releases/tag/2.4.5">
    <img src="https://img.shields.io/badge/release-2.4.5-ff4112.svg?style=for-the-badge" /></a>
</p>

<h3 align="center">Duino-Coin ist eine Kryprowährung, die zum Beispiel auf Arduinos, ESP boards, Raspberry Pis, Computern, und mehr gemint werden kann</h3>
<h4 align="center">inklusive Wi-Fi Router, SmartTV's, Smartphones, Smartwatches, SBCs, MCUs, GPUs - eigentlich alles das einen kleinen Programmierbaren Microchip hat.!</h4><br />

<table align="center">
  <tr>
    <th>Besonderheiten:</th>
    <th>Technische Spezifikationen</th>
  </tr>
  <tr>
    <td>
      💻 Von vielen Betriebssystem Plattformen unterstützt<br>
      👥 Eine freundliche & wachsende Community<br>
      💱 Einfach zu nutzten & in andere Währungen umzutauschen<br>
      🌎 Überall verfügbar<br>
      :new: Komplett originales Projekt<br>
      :blush: Anfänger freundlich <br>
      💰 Kosten-Effektiv<br>
      ⛏️ Einfach zu minen<br>
      📚 Open-source<br>
    </td>
    <td>
      ♾️ Coin supply: Unendlich (vor Dezember 2020: 350k coins) <br>
      😎 Prämie: <5k blöcke(<500 coins)<br>
      ⚡ Transaktionszeit: sofort<br>
      🔢 Dezimalstellen: bis zu 20<br>
      🔤 Ticker: DUCO (ᕲ)<br>
      ⚒️ Algorithmen: DUCO-S1, DUCO-S1A, XXHASH +mehr geplannt<br>
      ♐ Rewards: unterstützt durch das "Kolka System", welches hilft, miner fair zu belohnen<br>
    </td>
  </tr>
</table>

<h2 align="center">Get started</h2><br>

Offiziele Start-Guide um einen Account zu erstellen und einen Miner zu auf vielen Geräten zu Starten, sind verfügbar und Helfen euch bei der Einrichtung. <a href="https://revoxhere.github.io/duino-coin/getting-started">auf der offizielen Website</a>.<br>
Ein FAQ und Hilfe kann in der Wiki-Seite gefunden werden [Wikis](https://github.com/revoxhere/duino-coin/wiki).
<br>

| Offiziele Wallets | Offiziele Miner |
:-----------------:|:----------------:
[<img src="https://i.imgur.com/msVtLHs.png">](https://duinocoin.com/getting-started#register)  |  [<img src="https://i.imgur.com/SMkKHOK.png">](https://duinocoin.com/getting-started#computer)

<h3 align="center">Duino-Coin Installieren</h2><br>

Der einfachste Weg zu starten, ist  [den neusten release](https://github.com/revoxhere/duino-coin/releases/latest) für dein OS herunterzuladen.<br>
<br> Wenn der Download fertig ist, Entpacke ihn und öffnen dein gewünschtes Programm. Es sind keine anderen Programme nötig. <br>

<hr>

 Wenn du die Programme vom Master.zip Starten willst, musst du vielleicht einige zusätzliche erweiterungen hierfür Installieren. So kann man es auf Debian-based Linux distros (z.B. Ubuntu, Debian oder Raspian) machen:
```BASH
sudo apt install python3 python3-pip git
git clone https://github.com/revoxhere/duino-coin
cd duino-coin
python3 -m pip install -r requirements.txt
```
Wenn du Windows nutzt, musst du [Python 3](https://www.python.org/downloads/) herunterladen, und dann die [Master Repository](https://github.com/revoxhere/duino-coin/archive/master.zip), diese dann Entpacken (WinRar, 7zip) Danach kannst du ein CMD Fester öffnen (Windows + R Taste). 

Im CMD Fenster, Schreibe/kopiere dies hinein:
```BASH
py -m pip install -r requirements.txt
```
Wichtig für Windows nutzer: Immer sicher gehen das [Python 3](https://www.python.org/downloads/) und Python3-pip installiert sind und geupdatet sind.

Nach all diesen Schritten, bist du so weit das du den Miner starten kannst. (z.b. `python3 PC_Miner.py` oder `py PC_Miner.py`).

<hr>

Du kannst das ganze Duino-Coin Paket auch mit AUR laden - dazu einfach ein Ladevorgang starten mit deinem Favorisierten AUR Helfer Programm:

```BASH
sudo pacman -S yay
yay -S duino-coin
```

Duino-Coin AUR Paket wird bereitgestellt von [PhereloHD](https://github.com/PhereloHD).

<h3 align="center">Von der Community erstellte Software von Talentierten Mitgliedern</h3><br>

**Andere Miner-/Software/Hardware/Chips die bekannt sind das Duino-Coin damit Funktioniert:**
*   [duino-coin-kodi](https://github.com/SandUhrGucker/duino-coin-kodi) - Mining addon for Kodi Media Center by SandUhrGucker
*   [MineCryptoOnWifiRouter](https://github.com/BastelPichi/MineCryptoOnWifiRouter) - Python Script für das Mining von Duino-Coin auf Routern by BastelPichi
*   [Duino-Coin_Android_Cluster Miner](https://github.com/DoctorEenot/DuinoCoin_android_cluster) - Mining mit weniger Bandbreite für Android Handy by DoctorEenot
*   [ESPython DUCO Miner](https://github.com/fabiopolancoe/ESPython-DUCO-Miner) - MicroPython Miner / ESP Boards  by fabiopolancoe
*   [DUCO Miner für Nintendo 3DS](https://github.com/BunkerInnovations/duco-3ds) - Python Miner für Nintendo 3DS by PhereloHD & HGEpro
*   [Dockerized DUCO Miner](https://github.com/Alicia426/Dockerized_DUCO_Miner_minimal) - Miner in Docker (Linux/ARM) by Alicia426
*   [nonceMiner](https://github.com/colonelwatch/nonceMiner) -  Schneller Duino-Coin Miner by colonelwatch
*   [NodeJS-DuinoCoin-Miner](https://github.com/DarkThinking/NodeJS-DuinoCoin-Miner/) - Einfach NodeJS Miner by DarkThinking
*   [d-cpuminer](https://github.com/phantom32-0/d-cpuminer) - Pure C Miner by phantom32
*   [Go Miner](https://github.com/yippiez/go-miner) by yippiez
*   [ducominer](https://github.com/its5Q/ducominer) by its5Q
*   [Unofficial miners directory](https://github.com/revoxhere/duino-coin/tree/master/Unofficial%20miners)
    *   [Julia Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Julia_Miner.jl) by revox
    *   [Ruby Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Ruby_Miner.rb) by revox
    *   [Minimal Python Miner (DUCO-S1)](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner.py) by revox
    *   [Minimal Python Miner (XXHASH)](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Minimal_PC_Miner_XXHASH.py) by revox
    *   [Teensy 4.1 code for Arduino IDE](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Teensy_code/Teensy_code.ino) by joaquinbvw
<!--*   [Multithreaded Python Miner](https://github.com/revoxhere/duino-coin/blob/master/Unofficial%20miners/Multithreaded_PC_Miner.py) by Bilaboz (DEPRECATED) -->

**Other tools:**
*   [Duino-Coin Mining Dashboard](https://lulaschkas.github.io/duco-mining-dashboard/) Dashboard und Problembeseitigungs Hilfe by Lulaschkas
*   [duco-miners](https://github.com/dansinclair25/duco-miners) CLI Mining Dashboard by dansinclair25
*   [Duco-Coin Symbol Icon ttf](https://github.com/SandUhrGucker/Duco-Coin-Symbol-Icon-ttf-.h) by SandUhrGucker
*   [DUCO Browser Extension](https://github.com/LDarki/DucoExtension) Für Chrome  by LDarki
*   [DUCO Monitor](https://siunus.github.io/duco-monitor/) Account Statistiken by siunus
*   [duino-tools](https://github.com/kyngs/duino-tools) by kyngs
*   [Duino Stats](https://github.com/Bilaboz/duino-stats) DUINO-COIN Discord Bot by Bilaboz
<!--*   [Duino-Coin Auto Updater](https://github.com/Bilaboz/duino-coin-auto-updater) by Bilaboz (DEPRECATED) -->

Diese Liste wird ständig geupdatet. Wenn auch du deine Software hier auflisten möchtest die zum Projekt beiträgt, Einfach einen Antrag in Git stellen, oder einen der Programmierer Dev's auf Discord anschreiben.

<h3 align="center">wDUCO Tutorial</h3><br>

Duino-Coin is a hybrid currency, meaning that it can be converted to wDUCO which is DUCO wrapped on the [Tron](https://tron.network) network (as a token). Currently there aren't many uses for it, other than just storing funds in external wallet or exchanging wDUCO to another token on JustSwap. Tutorial on using wDUCO is available in the [wDUCO wiki](https://github.com/revoxhere/duino-coin/wiki/wDUCO-tutorial).

<h2 align="center">Development</h2><br>

Contributions are what make the open source community such an amazing place to be learn, inspire, and create.
Any contributions you make to the Duino-Coin project are greatly appreciated.

How to help?

*   Fork the Project
*   Create your feature branch
*   Commit your changes
*   Make sure everything works as intended
*   Open a pull request

Server source code, documentation for API calls and official libraries for developing your own apps for Duino-Coin are available in the [useful tools](https://github.com/revoxhere/duino-coin/tree/useful-tools) branch.

<h2 align="center">Some of the officially tested devices (DUCO-S1)</h2><br>

| Device/CPU/SBC/MCU/chip                                   | Average hashrate<br>(all threads) | Mining<br>threads | Power<br>usage | Average<br>DUCO/day |
|-----------------------------------------------------------|-----------------------------------|-------------------|----------------|---------------------|
| Arduino Pro Mini, Uno, Nano etc.<br>(Atmega 328p/pb/16u2) | 170 H/s                           | 1                 | 0.2 W          | 15-20               |
| Teensy 4.1                                                | 12.8 kH/s                         | 1                 | -              | -                   |
| NodeMCU, Wemos D1 etc.<br>(ESP8266)                       | 9.3 kH/s                          | 1                 | 0.6 W          | 6-8                 |
| ESP32                                                     | 27 kH/s                           | 2                 | 1.25 W         | -                   |
| Raspberry Pi Zero                                         | 17 kH/s                           | 1                 | 0.7 W          | -                   |
| Raspberry Pi 3                                            | 440 kH/s                          | 4                 | 5.1 W          | -                   |
| Raspberry Pi 4                                            | 1.3 MH/s                          | 4                 | 6.4 W          | -                   |
| Atomic Pi                                                 | 690 kH/s                          | 4                 | 6 W            | -                   |
| Orange Pi Zero 2                                          | 740 kH/s                          | 4                 | 2.55 W         | -                   |
| Khadas Vim 2 Pro                                          | 1.12 MH/s                         | 8                 | 6.2 W          | -                   |
| Libre Computers Tritium H5CC                              | 480 kH/s                          | 4                 | 5 W            | -                   |
| Libre Computers Le Potato                                 | 410 kH/s                          | 4                 | 5 W            | -                   |
| Pine64 ROCK64                                             | 640 kH/s                          | 4                 | 5 W            | -                   |
| Intel Celeron G1840                                       | 1.25 MH/s                         | 2                 | -              | 5-6                 |
| Intel Core i5-2430M                                       | 1.18 MH/s                         | 4                 | -              | 6.5                 |
| Intel Core i5-3230M                                       | 1.48 MH/s                         | 4                 | -              | 6.1                 |
| Intel Core i5-5350U                                       | 1.35 MH/s                         | 4                 | -              | 6.0                 |
| Intel Core i5-7200U                                       | 1.62 MH/s                         | 4                 | -              | 7.5                 |
| Intel Core i5-8300H                                       | 3.67 MH/s                         | 8                 | -              | 9.1                 |   
| Intel Core i3-4130                                        | 1.45 MH/s                         | 4                 | -              | -                   |


<h2 align="center">License</h2><br>

Duino-Coin is mostly distributed under the MIT License. See `LICENSE` file for more information.
Some third-party included files may have different licenses - please check their `LICENSE` statements (usually at the top of the source code files).

<h2 align="center">Terms of service</h2><br>
1. Duino-Coins ("DUCOs") are earned by miners with a process called mining.<br/>
2. Mining is described as using DUCO-S1 algorithm (explained in the <a href="https://github.com/revoxhere/duino-coin/blob/gh-pages/assets/whitepaper.pdf">Duino-Coin Whitepaper</a>), in which finding a correct result to a mathematical problem gives the miner a reward.<br/>
3. Mining can be officially done using CPUs, AVR boards (e.g. Arduino boards), Single-board computers (e.g. Raspberry Pi boards), ESP32/8266 boards with the usage of official miners (other officially allowed miners are described in the upper part of README).<br/>
4. Mining on GPUs, FPGAs and other high-efficiency hardware is allowed, but using only the `EXTREME` mining difficulty.<br/>
5. Any users using miners on difficulty not suited for their hardware (see the <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#socket-api">difficulty list</a>) will be automatically throttled and/or blocked.<br/>
6. Any users spotted using inappropriate and/or overpowered hardware will be banned manually or automatically from the network without prior notice.<br/>
7. Banning involves blocking the user from accessing his coins along with the removal of an account.<br/>
8. Only coins earned legally are eligible for the exchange.<br/>
9. Users spotted using a VPN (or similar) with malicious intents (e.g. bypassing limits) may be banned without prior notice.<br/>
10. Multiple accounts used to bypass limits may be banned without prior notice.<br/>
11. Accounts may be suspended temporarily to investigate ("investigations") ToS violations ("violation" or "abuse").<br/>
12. Multiple accounts used to evade bans will be banned without prior notice.<br/>
13. An exchange request made to the offical DUCO-Exchange ("the offical exchange") may be delayed and/or declined during investigations. <br/>
14. Exchange requests made to the offical exchange may be declined due to ToS violations and/or low funding.<br/>
15. A user's DUCOs may be burnt if a violation can be proven.<br/>
16. These terms of service can change at any time without prior notice.<br/>
17. Every user using Duino-Coin agrees to comply with the above rules.<br/>
<h4 align="center">Privacy policy</h2><br>
1. On the master server we only store usernames, hashed passwords (with the help of bcrypt) and e-mails of users as their account data.<br/>
2. E-mails are not publicly available and are only used for contacting user when needed, confirming exchanges on the <a href="https://revoxhere.github.io/duco-exchange/">DUCO-Exchange</a> and receiving an occasional newsletter (planned for the future).<br/>
3. Balances, transactions and mining-related data is publicly available in the public <a href="https://github.com/revoxhere/duino-coin/tree/useful-tools#http-json-api">JSON APIs</a>.<br/>
4. The privacy policy may be changed in the future with a prior notification.

<h2 align="center">Developers</h2><br>

*   **Developers:**
    *   [@revox](https://github.com/revoxhere/) (Founder/lead dev) - robik123.345@gmail.com
    *   [@Bilaboz](https://github.com/bilaboz/) (Lead dev)
    *   [@connorhess](https://github.com/connorhess) (Lead dev)
    *   [@JoyBed](https://github.com/JoyBed) (Lead dev)
    *   [@LDarki](https://github.com/LDarki) (Web dev)
    *   [@travelmode](https://github.com/colonelwatch) (Dev)
    *   [@ygboucherk](https://github.com/ygboucherk) ([wDUCO](https://github.com/ygboucherk/wrapped-duino-coin-v2) dev)
    *   [@Tech1k](https://github.com/Tech1k/) - kristian@beyondcoin.io (Lead Webmaster and DUCO Developer)

*   **Contributors:**
    *   [@5Q](https://github.com/its5Q)
    *   [@kyngs](https://github.com/kyngs)
    *   [@httsmvkcom](https://github.com/httsmvkcom)
    *   [@Nosh-Ware](https://github.com/Nosh-Ware)
    *   [@BastelPichi](https://github.com/BastelPichi)
    *   [@suifengtec](https://github.com/suifengtec)
    *   Thanks to [@Furim](https://github.com/Furim) for help in the early development stage
    *   Thanks to [@ATAR4XY](https://www.youtube.com/channel/UC-gf5ejhDuAc_LMxvugPXbg) for designing early logos
    *   Thanks to [@Tech1k](https://github.com/Tech1k) for [Beyondcoin](https://beyondcoin.io) partnership and providing [duinocoin.com](https://duinocoin.com) domain
    *   Thanks to [@MrKris7100](https://github.com/MrKris7100) for help with implementing SHA1 algorithm
    *   Thanks to [@daknuett](https://github.com/daknuett) for help with Arduino SHA1 library

<hr>

Project Link: [https://github.com/revoxhere/duino-coin/](https://github.com/revoxhere/duino-coin/)
