# MacVM-VBox

```
VBoxManage modifyvm "MacVM" --cpuidset 00000001 000106e5 00100800 0098e3fd bfebfbff
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/efi/0/Config/DmiSystemProduct" "iMac19,1"
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/efi/0/Config/DmiSystemVersion" "1.0"
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/efi/0/Config/DmiBoardProduct" "Mac-AA95B1DDAB278B95"
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/smc/0/Config/DeviceKey"
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/smc/0/Config/DeviceKey" "ourhardworkbythesewordsguardedpleasedontsteal(c)AppleComputerInc"
```
```
VBoxManage setextradata "MacVM" "VBoxInternal/Devices/smc/0/Config/GetKeyFromRealSMC" 1
```
```
VBoxManage setextradata "MacVM" VBoxInternal2/EfiGraphicsResolution 1920x1080
```
```
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Core i7-6700K"
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Xeon X5482 3.20GHz"
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Core i7-2635QM"
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Core i7-3960X"
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Core i5-3570"
VBoxManage modifyvm "MacVM" --cpu-profile "Intel Core i7-5600U"

```
### Efi shell
```
FS#:/System/Library/CoreService
boot.efi
