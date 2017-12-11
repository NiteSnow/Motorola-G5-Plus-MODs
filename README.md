# Motorola-G5-Plus-MODs
NFC, DTV, Dual SIM. Tested on XT1687, Backups will make you not look like a dumb ass on XDA.

adb shell "dd if=/dev/block/mmcblk0p50 of=/tmp/mmcblk0p50.bak"; adb pull /tmp/mmcblk0p50.bak
wget https://github.com/NiteSnow/Motorola-G5-Plus-MODs/raw/master/p50.mod.bin; adb push p50.mod.bin /tmp/p50.mod.bin; adb shell "dd if=/tmp/p50.mod.bin of=/dev/block/mmcblk0p50"
