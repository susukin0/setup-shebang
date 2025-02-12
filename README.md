### Setup Wi-Fi

Ethernet is setup automatically and Wi-Fi is setup with something like:
```
sudo vim /etc/wpa_supplicant/wpa_supplicant.conf
sudo sv restart wpa_supplicant
```

### Setup Shebang

Run the script as root:
```
sudo setup-shebang
```
