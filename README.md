# Gigabyte-Z390-Gaming-X-Hackintosh-I7-9700K-SAPPHIRE-5500XT
Gigabyte Z390 Gaming X + I7 9700K + SAPPHIRE 5500XT  
## 版本
OS: Catalina 10.15.4  
BIOS: F10C    
OC: 0.5.7  


## 硬件：  

类型|型号
------------ | -------------
主板|Gigabyte Z390 Gaming X
cpu|i7 9700k
显卡|蓝宝石 5500XT
网卡&蓝牙|BCM94360CD
内存|金士顿  DDR4 3200 16G*2
硬盘|SAMSUNG EVO 970 PLUS M.2 512G
显示器|DELL P2415Q 4k

## 功能：  
显卡免驱  
网卡免驱  
蓝牙免驱  
USB内建  
睡眠正常  
变频正常  
AIRDOP正常   
声卡正常  

## BIOS设置
csm 关闭  
vt-d 关闭  
fast boot 关闭  
Above 4G decoding 开启  
EHCI handoff 开启  
CFG lock 关闭


## 修改BIOS

需要解锁cfg lock，直接修改BIOS重新刷入，一劳永逸解决问题。   
修改版BIOS需要在DOS命令行下刷入，不能使用官方工具刷入。  
也可以使用命令行方式关闭cfg lock   
此外用鼠标拖动声音滑块的时候，存在飘动卡顿现象，  
此故障需要关闭BIOS中的serial port功能修复，但是BIOS设置中已经取消，需要修改BIOS重新刷入。  

## 主题
使用了NDK第三方主题控件


