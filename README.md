# firmware_brick
Firmware release for TG3040 Brick

# Firmware version: 1.1.1 - 20251126
=================================
1. Fix main grid style status saving issue.
2. Fix the favorites crash issue when deleting an item from the list.
3. Fix the SSID and password issues with special characters, fix the hotspot empty password issue.
4. Reset Wi-Fi passwords when 'factory reset'.
5. Add keytone ON/OFF setting.
6. Fix occasional deadlocks when coming back from any apps to Main UI.
7. Fix ARISC firmware for the occasional not being able to start up when USB plugged and force poweroff.
   (the battery needs to be drained when the problem occurs).
8. Add SSH support.
9. Fix OSD layout issue 'last widget does not show'.
10. Fix language issue 'device crashed when an incorrect lang file was used'.
11. Fix BGM toggle issue 'BGM will still turn on when toggle was set to OFF and then suspend/wakeup'.
    
# Firmware version: 1.1.0 - 20250610
=================================
1. Add theme selector preview image (pop-up display)
2. Add homepage TAB visibility settings in homepage settings, which can hide unnecessary items except 'settings'.
3. New feature OSD hot function board, default hotkey 'menu+select' to pop up.
4. Add various pop-up notifications: global volume/brightness/plug+unplug charging cable/ ..
5. Add application 'Picture', for jpg/png/bmp/...
6. Add application 'Reader', for pdf/mobi/epub/...
7. Add application 'Music', for MP3/wma/wav/flac/ape/..
8. Game list page flipping improvement, add L2/R2 letter scrolling.
9. Add automatic SD error checking and repairing in USB mode.
10. Add Russian/Vietnamese language translations.
11. Increase the boot partition space to 22MB for the boot logo, increase the system partition to 2GB.
12. The system app theme follows Main UI theme.
13. The game list folder supports thumbnails with the same name, such as Roms/EASYRPG/AAA/AAA.png.
-------------------------------------------------------
Attachment 1.1.0 SD Basic Package Update Record:
1. Update RetroArch to version 1.21.0, add hotkey 'B + menu' to enter RetroArch's native menu.
2. Add SS yabasanshiro standalone emulator (as default).
3. Added N64 standalone cores as an option: mupen64plus-gliden64-mk2/mupen64plus-gliden64-rice.

This SD package is a patch base on 1.0.5: https://github.com/trimui/assets_brick/releases/download/20241105/tg3040_Brick_SD_base_package_20241105.zip
Just replase file or folders according to your needs.
Replace file: RetroArch\ra64.trimui
Replace folder:　Emus\N64 Emus\SS, Notice if the folder contains game savestates.


# Firmware version: 1.0.6 - 20241215
1. Fix alsa period/buffer size for some applications' sound issue (drastic/...).
2. Turn on top LED when boot.
3. Low battery red blinking LED moved to front F1/F2;
4. Battery curve update. Increase protecting pre-charge current (100mA -> 400mA).
5. Add main page setting to set TAB/HOME focus behavior.
6. Add 'confirm key' setting to choose B or A.
7. Fix some language translations.
8. Fix lcd timing.
9. Add thumbnail size setting in game list menu.
10. Fix 'mute' function in Fn Editor.

# Firmware version: 1.0.5 - 20241105
first release.
