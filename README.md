# Multitouch-capabilities-of-Synaptics-Touchpad-with-VoodooPS2-2.2.9-Acidanthera-


* Download last VoodooPS2 from Kext Updater/ Kextmanager/ NightlyBuilds
* Open VoodooPS2Trackpad.kext's Info.plist file with PlistEditor
* Delete ALPS GlidePoint and Elantech TouchPad under IOKitPersonalities. (it works even if it is not deleted, but it takes a long time to boot)
* Dump it to EFI/OC/kext and processed it to the config file. (VoodooPS2Mouse.kext passive)
* Clear the NVRAM while restarting the computer and the synaptics PS2 trackpad's multitouch features are now available.
* 
NOTE1: Not Working: Trackpad's left and right physical buttons
NOTE2: The DEBUG version of VoodooPS2Controller.kext, which I got directly from Acidanthera's site, worked, but RELEASE does not work.

If you find a solution to make the left and right buttons work, please open issue.
