# dell5540-efi

#EFI for Dell Latitude E5540 (Hackintosh)

Supported version:
- macOS 10.15 (Catalina - Not tested)
- macOS 10.14.6 (Mojave)
- macOS 10.13.6 (High Sierra)

Specification:
- Core i3 4010U with Intel Integrated Graphics HD4400
- ALC292 (you will need a alcjack patch for noise)
- 8GB of DDR3L
- DW1506 (contain AR9485)

What's working:
- Ethernet (IntelMausiEthernet)
- Touchpad (VoodooPS2ControllerR6)
- Wifi (AtherosWifiInject but it's very SLOW!)
- ALC292 with layout 13
- 4 Ports USB (not remap yet)
- PNLF (Brightness but FN key not working)
- Battery Percents (but show wrong percents!)

Not Working:
- Sleep (not fixed yet :<)
- VGA Port (maybe not supported in macOS?)
- Touchpad sometime freeze... (i hate my trackpad :>)
