# All-Magisk-Module-Compatible-With-Redmi-12
In this repo I have mentioned some of the magisk module that are compatible with Redmi 12 (codename: Fire) I have tested these modules on HyperOS 2 (specifically on 2.0.202.0 Indian ROM)

## Introduction
Welcome to the Redmi 12 (codename "fire") modules collection! This repository lists some of the best Magisk modules and tweaks that work smoothly on Xiaomi Redmi 12 (MediaTek Helio G88 chipset) devices. These modules enhance your device’s performance, customization, and overall experience without compromising stability. Since this is a low-end device some features are locked out (EG: iOS style control centre, Advanced Blur etc)

> [!WARNING]  
> Please keep in mind that the modules mentioned needs root access via Magisk, while getting the access is not hard, it does carry a risk of soft bricking your device also rooting requires unlocking the Bootloader which will void your warrenty (if any)

##Unlocking The Bootloader
Xioami usually locks the bootloader on its devices for reasons like privacy, to protect against malware, and prevent any modifications to the device that they do not want. While most other phone brands do the same you can unlock the BL with a permission (differ from brand to brand). Xiaomi also require you to do the same, they have recently changed the unlock requirements, like CN (mainland china) model have a diff method to unlock the bootloader. To get the permission you have to apply for unlock bootloader in the Xiaomi community app, which will allways give you a error, no matter the time or the number of times you try. So then to get the permission you would have to contact someone who speciallizes in unlocking the bootloader (@robon3xus on telegram is one these guys, he is legit, i unlocked my 
BL with his help), they will get you the permission after that follow the below steps:

> [!WARNING]
> Unlocking the Bootloader will Erase the data kept in the phone, please take a backup before you do this

1. Go to the setttings app --> About Phone --> Tap 7 time on OS version
2. Go back to the main Settings screen --> Aditional Setting (scroll down) --> Developer Options
3. Enable OEM unlocking (will probably ask for confirmation)
4. Go to MI unlock status --> Agree (the popup named Permission required) --> Add account and device (needs Mobile Data and a Mi account at least 30 days or older) --> If it says success or simillar proceed, if not try again after a few min
5. Download the MI Flash Unlock tool from any reputable website or from thie repo
6. Extract the files from the .rar or .zip file
7. Launch the tool by double clicking on the miflash_unlock.exe
8. In the application a popup is diplayed just click on the close button (x) of the popup
9. Click on agree --> Sign in with the MI account that is present on the phone (Use the QR option on the top right of the window if normal sign doe not work)
10. Now power off the phone (not reboot) --> Hold the power button and the Vol- (Volume Down) button --> Once your feel the vibration release the Power Button --> A orange logo appeares with the text fastboot release the Vol- button
11. connect the phone to the PC (use the cable that came with the phone) --> On the MiFLash tool click on Unlock --> Ok/agree --> Ok/agree
12. It will fail, telling you to wait a certain amount of time, wait that long and try  step 10 & 11 again
