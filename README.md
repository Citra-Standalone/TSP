# TSupport ( TSP )

This module will automatically replace TS keybox and PIF fingerprint with TSP keybox/fingerprint.

This module automatically disable XiaomiEU Inject Module to give support for XEU ROM. ( might not work for some XiaomiEU ROM )

Automatically add detection app such MoMo, Hunter, NativeDetector to denylist and spoof.

Auto detect TEE Broken, and help make Tricky Store working for TEE Broken device.

## Installation Guide ( Reboot Every Step )
- Install ZygiskNext
- Install PlayIntegrityFix or Fork
- Install Tricky Store
- Install TSupport ( TSP )

<details>
<summary>
<strong>
Troubleshooting
</strong>
</summary>

If you are having issue with Integrity, follow below Instruction :

STEP 1: Delete all module, Install PIF and check Integrity.

If you pass basic and device. Youre good to go to next step.

If youre not passing basic and device, check to your rom setting, maybe it has built-in PIF spoof, such prop spoof or GMS spoof, disable all.

STEP 2: Delete all module, Install Tricky Store and check KeyAttestation.

If showing AOSP root certificate, then youre good to go to full installation.

If showing revoke or something else such, passing GMS root certificate. Maybe you have built-in keybox spoof. Find it in setting and disable.

If youre on a stock ROM but still not showing AOSP, install TSupport and reboot. After boot you will need to remove Tricky Store and reboot again. After the boot, reinstall Tricky Store and do a check again to KeyAttestation.

STEP 3: Full Installation.

Install PIF latest, reboot.
Install Tricky Store and TSupport, reboot.

All Done. ( If you have anything that you don't understand, just ask in group, will reply ASAP )
</details>

Note : Some device will not working to pass Strong Integrity

## Requirements
* PlayIntegrityFix by chiteroman
* Tricky Store by 5ec1cff

## Discussion
[TGRAM](https://t.me/citraintegritytrick)

## Donation
[PAYPAL](https://paypal.me/CitraStanalone?country.x=US&locale.x=en_US)
