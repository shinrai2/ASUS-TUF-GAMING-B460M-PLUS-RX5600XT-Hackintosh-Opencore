# ASUS-TUF-GAMING-B460M-PLUS-RX5600XT-Hackintosh-Opencore

![about](/IMG/about.png)

# Configuration
- Opencore: 0.7.8  
- Version: macOS Monterey  
- Motherboard: ASUS TUF Gaming B460M PLUS WIFI  
- Graphics: RX5600XT  
- CPU: Intel i5 10400  
- Wireless network card: BCM94360CD  

# BIOS settings
> Upgrade BIOS firmware to 1501 first.
- Advanced \ CPU Configuration \ Software Guard Extensions (SGX): Software Controlled  
- Advanced \ CPU Configuration \ Intel (VMX) Virtualization Technology: Disabled  
- Advanced \ System Agent (SA) Configuration \ VT-d: Disabled  
- Advanced \ System Agent (SA) Configuration \ Graphics Configuration \ Primary Display: Auto  
- Advanced \ System Agent (SA) Configuration \ Graphics Configuration \ iGPU Multi-Monitor: Enabled  
- Advanced \ System Agent (SA) Configuration \ Graphics Configuration \ DVMT Pre-Allowcated: 256M  
- Advanced \ System Agent (SA) Configuration \ Graphics Configuration \ Primary Display: Auto  
- Advanced \ PCI Subsystem Settings \ Above 4G Decoding: Enabled  
- Advanced \ PCI Subsystem Settings \ SR-IOV Support: Disabled  
- Advanced \ USB Configuration \ XHCI Hand-off: Enabled  
- Advanced \ Onboard Devices Configuration \ Serial Port Configuration \ Serial Port: Off  
- Boot \ CSM (Compatibility Support Module) \ Lauch CSM: Disabled  
- Boot \ Secure Boot \ OS Type: Other OS  
- Boot \ Boot Configuration \ Fast Boot: Enabled  

For Windows:
- Tool \ ASUS Armoury Crate \ Download & Install ARMOURY CRATE app: Disabled  

# Situation
- Work well except AX200  
- UHD 630 work well now :confetti_ball: :confetti_ball:  

# Issue tracking

```
Q: Sleep and wake error: Sleep Wake failure in EFI.
A: Run `sudo pmset -a standby 0` in terminal.
```
```
Q: Problem with the display scale of Opencore.
A: Change the value `UIScale` in NVRAM settings (also need to reset NVRAM and rebuild UEFI record).
```

