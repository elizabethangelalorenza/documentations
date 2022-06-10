### Flashing Guide Poco X3 Pro (vayu/bhima)

Clean Flash from MIUI:
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Clean Flash from Custom ROM with prebuilt vendor build (Non OSS):
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Clean Flash from custom ROM with OSS vendor build (OSS):
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Clean Flash from Android 11 ROM with OSS vendor build (OSS):
1. Reboot to Recovery
2. Wipe Dalvik/ART Cache, Data, and Cache on Advanced Wipe
3. Flash ROM
4. Flash DFE (optional)
5. Format Data, type "yes" and press enter
6. Reboot to System
7. Enjoy!

Dirty Flash from my build (Evolution X) with OSS vendor build (OSS):
1. Reboot to Recovery
2. Flash ROM
3. Flash DFE (optional)
4. Wipe Dalvik/ART Cache
5. Reboot to System
6. Enjoy!

Flashing for DFE user with OSS vendor build (OSS):
1. Reboot to Recovery
2. Flash ROM
3. Flash DFE (mandatory)
4. Wipe Dalvik/ART Cache
5. Reboot to System
6. Enjoy!

### Notes:
* I recommended to flash Magisk after booted up.
* You can't dirty flash Non-OSS ROM over OSS ROM.
* If you are DFE User, you must always to flash DFE file .zip after flashing ROM (before reboot to system).
* What if I forgot to flash DFE and rebooted? Say goodbye to your data.
* All my build (Evolution X) already include GApps, so no need to flash GApps again.
* Flashing firmware is not mandatory, that is "optional". No need to flash every flashing ROM.

### Important Link:
* Magisk:
  - [**Magisk v23.0 Stable (Magisk Hide)**](https://github.com/topjohnwu/Magisk/releases/tag/v23.0)
  - [**Magisk v24.3 Stable (Zygisk)**](https://github.com/topjohnwu/Magisk/releases/tag/v24.3)
  - [**Magisk Canary**](https://raw.githubusercontent.com/topjohnwu/magisk-files/canary/app-debug.apk)
* Firmware: 12.0.X.X or 12.5.X.X (choose your favorite firmware)
  - [**12.0.X.X-RJUIDXM**](https://sourceforge.net/projects/vayu-repository/files/Firmware/ID/)
  - [**12.5.X.X-RJUMIXM**](https://xiaomifirmwareupdater.com/firmware/vayu/)
  - [**Archive all region**](https://xiaomifirmwareupdater.com/archive/firmware/vayu/)
* Recovery:
  - [**TWRP Recovery OFFICIAL**](https://dl.twrp.me/vayu/)
  - [**OrangeFox Recovery OFFICIAL**](https://orangefox.download/device/vayu)
* Disable Force Encryption (DFE) for Custom ROM AOSP (only):
  - [**dynDFE_v1.0**](https://sourceforge.net/projects/vayu-repository/files/Additional/dynDFE/dynDFE_v1.0_vayu.zip/download)
  - [**dynDFE_v2.0**](https://sourceforge.net/projects/vayu-repository/files/Additional/dynDFE/dynDFE-v2.0_vayu.zip/download)
* Report bug on [**Group Support**](https://t.me/GengKapakVayu)
