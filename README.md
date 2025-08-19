# :partly_sunny: VIS2 View für die Wetterstation Bresser 4CAST MD

![status](https://img.shields.io/badge/status-alpha-orange)
![version](https://img.shields.io/badge/version-0.1-orange)
![license](https://img.shields.io/badge/license-Public%20Domain-lightgrey)
![GitHub all releases](https://img.shields.io/github/downloads/quinti123/Bresser_4CAST-for-VIS2/total)

![Station](Bresser_readme1.png)

Dieses VIS2 view für iobroker simuliert eine 
[Bresser 4Cast MD](https://www.bresser.de/p/bresser-wlan-4cast-md-funk-wetterstation-7-in-1-7003800) 
Wetterstation (Art.Nr. 7003800).

Sie blendet Daten aus dem iobroker über eine Abbildung der Wetterstation ein.
Die Daten werden aus dem Objekttree des Projektes [WLAN-Wetterstation von SBorg2014](https://github.com/SBorg2014/WLAN-Wetterstation) übernommen.
Angezeigt werden der Standardmässig Daten des 7in1 Aussensensor sowie 1 zusätzlicher Temp/Hydro Innensensor.


## Systemvoraussetzungen
Benötigt werden folgende Adapter:
  - Vis2 (sollte aber auch noch mit Vis1 funktionieren)
  - materialdesign Widgets
  - timeandweather Widgets
  - influxdb,sql oder history
  
## Changelog

### 0.2 alpha (2025-08-19)

	- Batteriestatus in/out img eingebaut
	- Farbe Graph Druck angepasst

### 0.1 alpha (2025-08-17)

	- initial release


## Todo
geplant ist für die Zukunft eine Nutzung der Tasten um die verschiedenen Funktionen der Wetterstation zu simulieren.
  


  
  
