# DELL-XPS-13-9370

OpenCore 0.6.4 EFI files for the Dell XPS 13 9370

* i7 8550U (UHD 630)
* 13 inch FHD non-touch
* 16GB RAM
* 512 GB skhynix NVMe SSD
* Broadcom WiFi (soldered)
* dual boots with Linux

## What works
* Boots fine
* Power Management
* Video acceleration
* touchpad + all gestures
* Onboard audio (USB & HDMI audio also work)
* sleep/wake
* USB WiFi (Using chris1111's driver at https://github.com/chris1111/Wireless-USB-Adapter)
* USB hotplugging (at least when using a powered USB C dock)
* 2 external screens 2560x1440@60Hz (via thunderbolt USB dock) - one via HDMI one via DP

## What doesn't (yet)
* brightness keys (brightness in general doesn't do anything)
* internal WiFi obviously
* Card reader
* Webcam
