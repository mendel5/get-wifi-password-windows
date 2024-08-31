# get-wifi-password-windows
How to get the password of a known Wi-Fi network on a Windows system

Situation:
You need the password of a Wi-Fi network that your Windows computer is or was connected to.
Therefore, the Wi-Fi password is stored somewhere on your computer.
With the command below you can make Windows show you the Wi-Fi password.

## Command
```
netsh wlan show profile name="my_wifi_name" key=clear
```
- Copy the command above.
- Replace "my_wifi_name" with the name (SSID) of your Wi-Fi network.
- Paste it into a CMD terminal or a Powershell terminal.

Links:
- https://www.asus.com/en/support/faq/1046400/
