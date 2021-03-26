# Dokumentation Projekt Telefonzelle

## Überblick
Das Projekt "Telefonzelle" soll Pensionen für Wohnungslose eine technisches System zur Verfügung stellen, um Bewohner:innen Zugang zu kostenlosem Telefon und Internet zu ermöglichen. Die folgende Dokumentation umfasst sowohl die Umsetzung der Software (Web-Application, Online-Repository) als auch der Hardware (Raspberry Pi, Input, Output). Use Cases und Priorisierung der einzelnen Features und Umsetzungsdetails basiert auf nutzerzentriertem Vorgehen, d.h. kontextuierten Interviews vor Ort und iterativen Tests von Prototypen.

<img width="1418" alt="image" src="https://user-images.githubusercontent.com/10279394/112653937-2e94db00-8e4f-11eb-9554-1d11e02384dc.png">


## Voraussetzungen
### Hardware
Als Setup in Pensionen werden aktuell folgende Komponenten genutzt. Prinzipiell kann die Web-Application jedoch auf jedem beliebigen grafischen und mit dem Internet verbundenen System genutzt werden. 
* Rasperry Pi 4 (mind. 4 GB RAM)
* Tastatur (ohne Alt+F4 Tasten)
* Maus
* Bildschirm
* SD oder SSD Karte mit Raspian und installiertem Chromium

Der Raspberry Pi sollte gegen freien Zugang abgesichert sein. Folgende Maßnahmen sind aktuell umgesetzt:
* Chromium Browser via Autostart im Kiosk Modus starten. Ein Guide dafür ist hier zu finden: https://goneuland.de/raspberry-pi-chromium-kiosk-modus-aktivieren/
* Whitelisting nutzen für Chromium. Aktuell wird hierfür die Chromium Extention "Whitelist Manager" genutzt: https://chrome.google.com/webstore/detail/whitelist-manager/dopjoipaenahonjgpdijmgbdilehfkbl?hl=de
* Chromium Extention für Navigation im Kiosk-Mode. Damit trotz Kiosk-Mode auch ein Zurück- und ein Home-Button zur Verfügung steht (Startseite: Link der Web-Application), wird die Extention "Kiosk Extention" in Chromium eingebunden: https://chrome.google.com/webstore/detail/kiosk-extension/aimjancijiedgnfcljgkhdmppakhlmmc

### Software
Die Web-Application kann über den folgenden, öffentlich zugänglichen Link aufgerufen werden: https://johannestscharn.github.io/Telefonzelle/ 


## Versionen
Die folgenden Versionen wurden bisher erstellt
* **v0.3 (26.03.2021): Ausarbeitung der Inhalte und Links, demonstriert und getestet in Pension**
* v0.2 (24.03.2021): Anbidnung an Raspberry Pi, Anpassungen Inhalte und CSS Styles, Tests in Pension
* v0.1 (22.03.2021): Initiale Version der Web-Application
