# get-wifi-password-windows
How to get the password of a known Wi-Fi network on a Windows system

Situation:
You need the password of a Wi-Fi network that your Windows computer is or was connected to.
Therefore, the Wi-Fi password is stored somewhere on your computer.
With the command below you can make Windows show you the Wi-Fi password.

## Command
Copy the command below and paste it into a CMD terminal or a Powershell terminal.

```
netsh wlan show profile name="my_wifi_name" key=clear
```
Replace "my_wifi_name" with the name (SSID) of your Wi-Fi network.

Links:
- https://www.asus.com/en/support/faq/1046400/
