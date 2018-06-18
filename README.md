# rpi2caster-configuration
rpi2caster interface configuration files


1. check the MAC address(es) for a built-in LAN interface, 
   WLAN interface (RPi3 built-in or USB dongle if you use it),
   additional USB LAN interfaces
2. edit etc/udev/rules.d to include these MACs
3. copy the contents to Raspberry Pi root (make sure every file is owned by root!)
4. set up a password for user monotype (usually, rpi2caster)
5. edit rpi2caster.conf (typesetting software configuration) 
   and rpi2casterd.conf (hardware configuration) if needed
