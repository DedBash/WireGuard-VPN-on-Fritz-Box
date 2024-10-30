# WireGuard-VPN-on-Fritz-Box
This tutorial uses Mullvad VPN to show you how to connect yout Fritz!Box to a Wireguard VPN server and manage your entire network through a VPN.

### Translations
[German](https://github.com/DedBash/Mullvad-VPN-on-Fritz-Box/blob/main/german.md)

## Get your wireguard file for Mullvad:
For other VPN providers, the configuration steps may be different but the setup in the Fritz!Box remains the same<br>

1. Go to the [WireGuard](https://mullvad.net/en/account/wireguard-config) configuration file generator.
2. Use Linux as Platform.<br>
3. Select a Location.<br>
4. Click on Download zip archive and save it to your computer.<br>
5. Extract the zip file.<br>

## Setup in the webinterface
1. Log in to your Fritz!Box click on "Internet" -> "Permit Access"  -> "VPN (WireGuard)" and then click on "Add Connection"<br>
![image](https://user-images.githubusercontent.com/79027536/236583105-372c30d5-8532-465a-b5fd-807389c96758.png)
2. Select "Connect networks or establish special connections"<br>
![image](https://user-images.githubusercontent.com/79027536/236583174-90aba2f1-1a8b-4f96-91c1-d4b5af232faa.png)
3. At "Has this WireGuard® connection already been set up at the remote connection?" select "Yes"<br>
![image](https://user-images.githubusercontent.com/79027536/236583267-418e98f6-b6ba-4b5e-947b-8bedb58ae444.png)
4. Now give your connection a name and select the downloaded conf file. It is also important to select "Send all IPv4 network traffic via the VPN connection" because otherwise an error will occur.<br>
![image](https://user-images.githubusercontent.com/79027536/236583410-e775b379-a560-4c03-b3ba-dae891c4e100.png)
5. Now confirm the change by entering the code via telephone or by pressing one of the buttons on the Fritz!Box. Then press "OK". <br>
![image](https://user-images.githubusercontent.com/79027536/236583577-aa86b100-0856-4471-bb6f-c422b26407a1.png)
![image](https://user-images.githubusercontent.com/79027536/236583586-13447829-4b2b-45d5-bf21-9656310f21ea.png)
6. Now you will get a confirmation which you can close and after that you are connected to the Mulvad VPN.<br>
![image](https://user-images.githubusercontent.com/79027536/236583650-92fb0fdf-c0d1-4c7c-8755-a8104383fd09.png)
![image](https://user-images.githubusercontent.com/79027536/236583763-4d1687e1-21b9-433a-8a64-3311d2bad684.png)

## Info:
If you see this screen, check again if you have internet and if you are registered at myFritz , and then reload the page.
![image](https://user-images.githubusercontent.com/79027536/236584344-a9027a75-f8de-4d4a-994e-9fd7f44419f7.png)

## Test:
I have tested this with a Fritz!Box 6850 LTE with firmware 7.51 but it also works with all other Fritz!Boxes that support VPN (WireGuard).
