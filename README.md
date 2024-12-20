# Pi4_AWUS036AXML_Kali
For installing the correct drivers for Alfa AWUS036AXML on a raspberry pi 4 running kali Linux with 5.15.44-Re4son-v8l kernel

**Download the firmware**
```
sudo wget https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/plain/mediatek/WIFI_MT7961_patch_mcu_1a_2_hdr.bin -O /lib/firmware/mediatek/WIFI_MT7961_patch_mcu_1a_2_hdr.bin
sudo wget https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/plain/mediatek/WIFI_RAM_CODE_MT7961_1.bin -O /lib/firmware/mediatek/WIFI_RAM_CODE_MT7961_1.bin
sudo wget https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/plain/mediatek/BT_RAM_CODE_MT7961_1_2_hdr.bin -O /lib/firmware/mediatek/BT_RAM_CODE_MT7961_1_2_hdr.bin
```
**Reboot**
```
sudo reboot
```


Below is a link to the mediatek drivers and a comprehensive rundown for this and many more by morrownr

https://github.com/morrownr/USB-WiFi/blob/main/home/How_to_Install_Firmware_for_Mediatek_based_USB_WiFi_adapters.md

https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git/tree/mediatek
