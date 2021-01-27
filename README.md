# ISPro-USB
Image for ISPro Demo Appliance
to write to USB drive
Download the ISPro-USB.zst file 

# used zstd to write the image to USB with minmum 16G capacity.
## zstdcat -v /temp/ISPro-USB.zst >/dev/sdh
where sdh is your USB drive.
