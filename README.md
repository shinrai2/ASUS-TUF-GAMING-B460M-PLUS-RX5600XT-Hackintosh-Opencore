# ASUS-TUF-GAMING-B460M-PLUS-RX5600XT-Hackintosh-Opencore

![about](/IMG/about.png)

# Configuration 
Opencore: 0.7.8  
Version: macOS Monterey  
Motherboard: ASUS TUF Gaming B460M PLUS WIFI  
Graphics: RX5600XT  
CPU: Intel i5 10400  
Wireless network card: BCM94360CD  

# Situation
Work well except UHD 630 and AX200  

# Issue tracking

```
Q: Sleep and wake error: Sleep Wake failure in EFI.
A: Run `sudo pmset -a standby 0` in terminal.
```
```
Q: Problem with the display scale of Opencore.
A: Change the value `UIScale` in NVRAM settings (also need to reset NVRAM and rebuild UEFI record).
```

