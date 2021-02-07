A python script that can download and build a number of kexts.

Additional SDKs can be found [here](https://github.com/phracker/MacOSX-SDKs) if need be.

 * Copy them to */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs* to use
 * You may need to change the `MinimumSDKVersion` in */Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Info.plist* if using Xcode 7.3+

***

## To install:

Do the following one line at a time in Terminal:

    git clone https://github.com/corpnewt/Lilu-and-Friends
    cd Lilu-and-Friends
    chmod +x Run.command
    
Then run with either `./Run.command` or by double-clicking *Run.command*

***

Currently Builds 50 kexts:

* ACPIBacklight
* ACPIBatteryManager
* ALXEthernet
* ATH9KFixup
* AirportBrcmFixup
* AppleALC
* AppleBacklightFixup
* AtherosE2200Ethernet
* AzulPatcher4600
* BCM5722D
* BT4LEContinuityFixup
* BrcmPatchRAM
* BrcmPatchRAM (Headkaze)
* CPUFriend
* CodecCommander
* DiskArbitrationFixup
* EnableLidWake
* FakePCIID
* FakeSMC
* FakeSMC (Kozlek)
* FakeSMC (Legacy)
* FakeSMC (RehabMan)
* GenericUSBXHCI
* HWSensors (FakeSMC + Plugins)
* HWSensors (Kozlek)
* HWSensors (Legacy)
* HWSensors (RehabMan)
* HibernationFixup
* IntelBacklight
* IntelMausi (Acidanthera)
* IntelMausiEthernet
* IntelMausiEthernet (RehabMan)
* Lilu
* LiluFriend
* NightShiftUnlocker
* NightShiftUnlocker (aabdellah)
* NoTouchID
* NoVPAJpeg
* NullCPUPowerManagement
* RealtekRTL8100
* RealtekRTL8111
* USBInjectAll
* VirtualSMC
* VirtualSMC (All Tools)
* VoodooHDA
* VoodooI2C
* VoodooPS2Controller
* VoodooPS2Controller (Acidanthera)
* VoodooTSCSync
* WhateverGreen

