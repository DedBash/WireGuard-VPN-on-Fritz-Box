# Mullvad-VPN-on-Fritz-Box
Diese Anleitung zeigt Ihnen, wie Sie Mullvad VPN auf Ihrer Fritz!Box installieren.

## WireGuard datei Runterladen:
1. Rufen Sie den [WireGuard](https://mullvad.net/de/account/#/wireguard-config)-Konfigurationsdateigenerator auf.<br>
2. Verwenden Sie Linux als Plattform.<br>
3. Wählen Sie einen Standort.<br>
4. Klicken Sie auf Download zip archive und speichern Sie es auf Ihrem Computer.<br>
5. Entpacken Sie die Zip-Datei.<br>

## Einrichtung über das Webinterface
1. Loggen Sie sich in Ihre Fritz!Box ein, klicken Sie auf "Internet" -> "Freigaben" -> "VPN (WireGuard)" und dann auf "Verbindung hinzufügen".<br>
![image](https://user-images.githubusercontent.com/79027536/236585140-d8b9c2cd-e3c3-4bc2-94ea-0cba7bc1cf64.png)
2. Wählen Sie "Netzwerke koppeln oder spezielle Verbindungen herstellen".<br>
![image](https://user-images.githubusercontent.com/79027536/236585133-28169091-ddd8-4581-8f70-147a09de3fbf.png)
3. Wählen Sie bei "Wurde diese WireGuard®-Verbindung bereits an der Gegenstelle erstellt?" "Ja".<br>
4. ![image](https://user-images.githubusercontent.com/79027536/236585115-43c4f096-f2b8-4959-91f0-32b2cbcfb123.png)
5. Geben Sie nun Ihrer Verbindung einen Namen und wählen Sie die heruntergeladene conf-Datei aus. Wichtig ist auch, dass Sie "Gesamten IPv4-Netzwerkverkehr über die VPN-Verbindung senden" auswählen, da sonst ein Fehler auftritt.<br>
![image](https://user-images.githubusercontent.com/79027536/236585105-c8f2e171-63eb-474a-b3f7-b272099fe516.png)
5. Bestätigen Sie nun die Änderung durch Eingabe des Codes per Telefon oder durch Drücken einer der Tasten an der Fritz!Box. Drücken Sie dann "OK". <br>
![image](https://user-images.githubusercontent.com/79027536/236585085-a4660d8a-7c49-4145-93cd-f289c1289c7b.png)
![image](https://user-images.githubusercontent.com/79027536/236585092-defaec3a-8e59-42b2-bfaf-c381f4445f8f.png)
6. Nun erhalten Sie eine Bestätigung, die Sie schließen können und danach sind Sie mit dem Mulvad VPN verbunden.<br>
![image](https://user-images.githubusercontent.com/79027536/236585074-9e301c4d-70e4-452d-836f-25a8d1ef8094.png)
![image](https://user-images.githubusercontent.com/79027536/236586374-39ffffc1-07af-400d-a658-c3aaf6d70aa2.png)

## INFO: 
Wenn Sie diesen Bildschirm sehen, überprüfen Sie noch einmal, ob Sie Internet haben und bei myFritz registriert sind, und laden Sie die Seite dann neu. 
![image](https://user-images.githubusercontent.com/79027536/236620526-502ce7ba-0468-499b-b19f-8de2d2e8803a.png)




## Test:
Ich habe das mit einer Fritz!Box 6850 LTE mit Firmware 7.51 getestet, aber es funktioniert auch mit allen anderen Fritz!Boxen, die VPN (WireGuard) unterstützen.




