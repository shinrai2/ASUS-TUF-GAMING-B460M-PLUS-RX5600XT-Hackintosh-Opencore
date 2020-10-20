# ASUS-TUF-GAMING-B460M-PLUS-RX5600XT-Hackintosh-Opencore

# Configuration 
Opencore: 0.6.1  
Version: macOS Big Sur Beta (Beta 10 not supported!!)  
Motherboard: ASUS TUF Gaming B460M PLUS (WIFI)  
Graphics: RX5600XT  
Wireless network card: BCM94360CD  

![ABOUT](IMG/about.png)

# Situation
Graphics：RX5600XT work well, UHD 630 not work  
Sound card：work well  
Wireless: wifi & Bluetooth work well, AX200 not work  
Sleep & wake：work well  
Location：work well  
NVRAM：work well  
USB：work well  (including usb2.0 and usb3.0)

# Issue tracking

```
Q: Sleep and wake error: Sleep Wake failure in EFI.
A: Run `sudo pmset -a standby 0` in terminal.
```
```
Q: Problem with the display scale of Opencore.
A: Change the value `UIScale` in NVRAM settings (also need to reset NVRAM and rebuild UEFI record).
```


