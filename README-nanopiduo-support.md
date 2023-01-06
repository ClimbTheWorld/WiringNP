# README_npiduo.md  
Lukas, 2019-12-04  
# to use WiringNP with NanoPiDuo and armbian ubuntu 18.04  
added nanopi duo board support due to error:  
  $gpio readall  
  piBoardRev: Unable to determine board revision from /proc/cpuinfo  
  -> Is not NanoPi based board.  
  ->  You may want to check:  
  ->  http://www.lemaker.org/  
  open /sys/class/sunxi_info/sys_info failed.  
  
## WiringNP fix  
https://forum.armbian.com/topic/11426-wiringpi-for-nanopi-neo-air/  
1. copy sys_info to /etc  
2. normally build the project  
