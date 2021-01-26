# dell5540-efi

#EFI for Dell Latitude E5540 (Hackintosh)
Note: We no-longer supported this model with CLOVER (We are building Opencore to fixing this problem) due to the fact that USB (XHCI and EHxx) has critical problem!

Supported version:
- macOS 10.15.x (Catalina)
- macOS 10.14.6 (Mojave)

Specification:
- Core i3 4010U with Intel Integrated Graphics HD4400
- ALC292
- 8GB of DDR3L
- DW1506 (contain AR9485) - i used Intel AGN 5100 Dual (5Ghz and 2,4GHz working perfectly)

What's working:
- Ethernet (IntelMausiEthernet)
- Touchpad (VoodooPS2ControllerR6)
- Wifi (AtherosWifiInject but it's very SLOW!)
- ALC292 with layout 13
- 4 Ports USB (not remap yet)
- Brightness
- Battery
- Sleep (but you lid, the hack will SHUTDOWN :>)

Not Working:
- VGA Port (NEVER WORKING!)
- Touchpad sometime freeze... (ALPS)
