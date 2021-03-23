# DPI Topper 666
 
## Software
### For 800x480 LCDs, add the following code to config.txt:
```
#Set GPIO pins to 18-Bit DPI Mode 6
gpio=0-1=a2,np
gpio=4-9=a2,np
gpio=12-17=a2,np
gpio=20-25=a2,np
#Set remaining GPIO pins to I2C Mode
gpio=2-3=a0,np
#Configure DPI signaling
framebuffer_width=800
framebuffer_height=480
enable_dpi_lcd=1
display_default_lcd=1
dpi_group=2
dpi_mode=87
dpi_output_format=503846
dpi_timings=800 0 40 48 88 480 0 13 3 32 0 0 0 60 0 32000000
```
### For 480x272 LCDs, add the following code to config.txt:
```
#Set GPIO pins to 18-Bit DPI Mode 6
gpio=0-1=a2,np
gpio=4-9=a2,np
gpio=12-17=a2,np
gpio=20-25=a2,np
#Set remaining GPIO pins to I2C Mode
gpio=2-3=a0,np
#Configure DPI signaling
framebuffer_width=480
framebuffer_height=272
enable_dpi_lcd=1
display_default_lcd=1
dpi_group=2
dpi_mode=87
dpi_output_format=503846
dpi_timings=480 0 5 0 40 272 0 8 0 8 0 0 0 60 0 9600000 3
```
