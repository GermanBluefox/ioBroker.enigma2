![Logo](admin/enigma2.png)
ioBroker enigma2 Adapter
==============
Adapter für ioBroker um Informationen von einem enigma2 Receiver abzufragen.


## Funktionen
- BOX_IP
- NETWORK
- CHANNEL_SERVICEREFERENCE
- CHANNEL
- EVENTDESCRIPTION
- EVENTDURATION
- EVENTREMAINING
- HDD_CAPACITY
- HDD_FREE
- MESSAGE_ANSWER
- MODEL
- MUTED
- PROGRAMM
- PROGRAMM_INFO
- PROGRAMM_AFTER
- PROGRAMM_AFTER_INFO
- STANDBY
- VOLUME
- WEB_IF_VERSION
## ab V 0.2.2  (nur in Verbindung mit folgenden Script)
 https://github.com/Matten-Matten/ioBroker.enigma2/blob/master/admin/COMMAND
 Dieses JAVA script muss im SCRIPT ADAPTER (Script Engine) angelegt, konfiguriert gespeichert und gestartet werden.

- command.CHANNEL_DOWN
- command.CHANNEL_UP
- command.DOWN
- command.UP
- command.EPG
- command.EXIT
- command.LEFT
- command.MENU
- command.MUTE_TOGGLE
- command.OK
- command.PAUSE
- command.PLAY
- command.RADIO
- command.REC
- command.RIGHT
- command.SET_VOLUME
- command.STANDBY_TOGGLE
- command.STOP
- command.TV
- command.UP


## Version

### 0.2.3 (2018-08-17)
* (Matten-Matten)      Admin V3.51

### 0.2.2 (2018-05-12)
* (Matten-Matten)      Button hinzugefügt

### 0.2.1 (2018-03-22)
* (Matten-Matten)      Fehlerbehebung in der HDD Abfrage

### 0.2.0 (2018-03-22)
* (Matten-Matten)      keine Fehlermeldung mehr wenn Box in DeepStandby
* (Matten-Matten)      Erweiterung (PROGRAMM_AFTER ; PROGRAMM_AFTER_INFO ; WEB_IF_VERSION ; NETWORK) hinzugefügt

### 0.1.0 (2018-03-21)
* (Matten-Matten)      installierbar

### 0.0.11 (2018-03-19)
* (Matten-Matten)                  Adapterkonfigurationsmaske (für Admin3) überarbeitet
* (wendy2702 & Matten-Matten)      Admin3 

### 0.0.10 (2018-03-19)
* (Matten-Matten)  Umstellungsversuch Admin3

### 0.0.9 (2018-02-07)
* (Matten-Matten)  Kategorie geändert
* (Matten-Matten)  Abfrage Werte sind nur noch lesbar nicht mehr beschreibbar.

### 0.0.8 (2017-11-25)
* (Matten-Matten)  Fehlerbehebung in HDD Abfrage
* (Matten-Matten)  Fehlerbehebung wenn Box Heruntergefahren (nicht erreichbar)
                    jetzt nur noch mit: info	received error: connect ECONNREFUSED 192.168. ...
* (Matten-Matten)  Konfigurations-Maske vereinfacht 

### 0.0.7 (2017-09-20)
* (Matten-Matten) add Fehlerbehebung in der MUTED Abfrage

### 0.0.6 (2017-09-19)
* (Matten-Matten) add Erweiterung der Adapterkonfiguration

### 0.0.5 (2017-09-18)
* (Matten-Matten) add grafische Optimierung der Adapterkonfiguration

## issues
* kein Senden von Befehlen aus dem Adapter heraus.

