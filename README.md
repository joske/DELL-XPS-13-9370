# DELL-XPS-13-9370

OpenCore 0.6.4 EFI files for the Dell XPS 13 9370

Updated to Big Sur

* i7 8550U (UHD 630 claimed by marketing - linux lspci says: Intel Corporation UHD Graphics 620 [8086:5917] (rev 07))
* 13 inch FHD non-touch
* 16GB RAM
* 512 GB skhynix NVMe SSD
* Qualcomm Atheros QCA6174 802.11ac WiFi (soldered)
* Intel Corporation UHD Graphics 620 [8086:5917] (rev 07)
* dual boots with Linux

## What works
* Boots fine
* Power Management
* Video acceleration
* brightness
* touchpad + all gestures
* Onboard audio (USB & HDMI audio also work)
* internal bluetooth
* Card reader using https://github.com/cholonam/Sinetek-rtsx
* USB WiFi Edimax 7822ULC (Using chris1111's driver at https://github.com/chris1111/Wireless-USB-Adapter)
* USB hotplugging (at least when using a powered USB C dock - does not work without dock). Left 2 ports only work when plugged at boot.
* 2 external screens 2560x1440@60Hz (via thunderbolt USB dock) - one via HDMI one via DP

## What doesn't (yet)
* sleep/wake sometimes works, sometimes broken: reboots at resume
* brightness keys, but Fn-S Fn-B work to control the brightness (so not a big deal).
* internal WiFi obviously
* Webcam (shows up in IOReg but black screen).
