# ascript-esp32
ESP32 projects for ascript
该项目固件皆来源于AScript官网，该固件属于蓝牙连接非usb，此仓库仅用于个人编译

烧录说明（esp32flasher）
bootloader.bin
0x0

partitions.bin
0x8000

firmware.bin
0x10000

烧录完成后点击rst重启，在手机蓝牙中便能配对连接
