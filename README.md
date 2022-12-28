# Dell Optiplex 3040 SFF

This is a working configuration for a Dell Optiplex 3040 SFF,
which supports MacOS Ventura.

You can finda EFI-folder with all necessary parts (based on OpenCore).

What works:
  * S-ATA disks
  * Realtek network card (with kext)
  * Audio (not checked every port, but the internal speaker is working ...)
  * WLAN/BT with BMC94360cs2 PCIe card (not tested yet)
  * internal intel graphics HD 530 (HDMI only), to use with Ventura there 
is a spoof to use the 530 as a HD 630 from KabyLake
  * USB injection


Notes:
 * sleep is working but the wakeup is crashing, this is a known problem 
with the HD 530 graphics
