Funkce
1-klikové nahrání firmware přes webový prohlížeč

WiFi konfigurace přímo v rozhraní

Port scanner pro základní síťovou diagnostiku

Kontrola síly hesla

Kompatibilní s ESP32-S3-N16R8

Jak používat
Instalace firmware
Připojte ESP32-S3 přes USB

Otevřete webové rozhraní flasheru

Klikněte na "Connect" a vyberte COM port

Klikněte na "Install" pro nahrání firmware

Po nahrání
Připojte se k WiFi AP CyberSec_AP (heslo StrongP@ss123!)

Otevřete http://192.168.4.1 v prohlížeči

V menu vyberte požadovanou funkci

Jak hostovat na GitHub
Forkněte tento repozitář

Přejděte do Settings → Pages

Nastavte:

Branch: main

Folder: / (root)

Nahrajte svůj firmware jako firmware.bin

Vývoj
Kompilace firmware
Otevřete projekt v Arduino IDE

Vyberte správný board: ESP32S3 Dev Module

Sketch → Export Compiled Binary

Výsledný .bin soubor nahrajte do repozitáře

Přizpůsobení
Upravte index.html pro změnu vzhledu

Upravte manifest.json pro změnu nastavení flasheru

Pro nové funkce upravte hlavní firmware

Bezpečnostní upozornění
Změňte výchozí heslo AP v kódu

Nepoužívejte pro citlivé sítě bez úprav

Port scanner používejte pouze na vlastní zařízení

Licence
MIT License - volně k použití a modifikaci

Report issues: Issues section

