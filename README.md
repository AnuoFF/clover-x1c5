# clover-x1c5  

Clover Bootloader settings and fixs for ThinkPad X1 Carbon Gen5(2017) 
>### work on 10.13.6  

this repo based on jqqqqqqqqqq's work(original post :  
http://bbs.pcbeta.com/viewthread-1772056-1-1.html

# My hardware configeration 
>Model:     ThinkPad X1 Carbon 2017 20HR  
CPU:        Core i5 7300U  
RAM:        16G LPDDR3 1866  
Graphics:   HD620  
LCD:        1080p  
Lan:        Intel I219V4  
Audio:      CX8200  
Wifi :      replaced with BCM94352z , no whitelist  
SSD:        intel 600p (replaced with sm961)  
TouchPad:   synaptics on SMBus  

# State
> ## fully working
>CPU HWP  
NvRam  
Graphic  and backlight adjusting  
Audio  
Wifi with 5G  
BT  
Lan  
Fan and sensor  
Cam  
Redpoint with three-key  
Hotkey  
Mic  
Sleep  and lid  
SSD with sm961 highperformance  
Usb3.0  

> ## partly working or issues
>thunderbolt 3 no test  
type c can be detected only plug in on first boot  
usb3.1 no test  
trackpad no multi gesture  
system lags caused by ssd 600p lowspeed  
battery percentage 4% more than in windows which is actual value  

> ## none working:  
>fingerprint  
cardreader  


# Changelogs:  
> ### 2018-3-1:  
>backlight lowlevel fixed. now lowlevel as in windows, tested on  1080p LCD B140HAN03.1. for detail see note.md  
volume slide fix  
change VoodooPS2Controller.kext for redpoint. mid-key fixed  
apfs.efi update  
add same tools  


