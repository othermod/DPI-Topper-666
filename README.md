# DPI Topper 666
 
## Software
### For 800x480 LCDs, add the following code to config.txt:
```
#Set GPIO pins to 18-Bit DPI Mode 6
#GPIO 0 and 1 needed for DPI Clock and Data Enable
gpio=0=a2,np
gpio=1=a2,np
#Set GPIO pins 2 and 3 to I2C Mode. These can be used for other things, if needed.
gpio=2=a0,np
gpio=3=a0,np
#Set up color pins
gpio=4=a2,np
gpio=5=a2,np
gpio=6=a2,np
gpio=7=a2,np
gpio=8=a2,np
gpio=9=a2,np
#GPIO 10 is available for use
#GPIO 11 is available for use
gpio=12=a2,np
gpio=13=a2,np
gpio=14=a2,np
gpio=15=a2,np
gpio=16=a2,np
gpio=17=a2,np
#GPIO 18 is available for use
#GPIO 19 is available for use
gpio=20=a2,np
gpio=21=a2,np
gpio=22=a2,np
gpio=23=a2,np
gpio=24=a2,np
gpio=25=a2,np
#GPIO 26 is available for use
#GPIO 27 is available for use

#Configure DPI signal
framebuffer_width=800
framebuffer_height=480
enable_dpi_lcd=1
display_default_lcd=1
dpi_group=2
dpi_mode=87
dpi_output_format=503846
dpi_timings=800 0 40 48 88 480 0 13 3 32 0 0 0 60 0 32000000 6
```
### For 480x272 LCDs, add the following code to config.txt:
```
#Set GPIO pins to 18-Bit DPI Mode 6
#GPIO 0 and 1 needed for DPI clock and Data Enable
gpio=0=a2,np
gpio=1=a2,np
#Set GPIO pins 2 and 3 to I2C Mode. These can be used for other things, if needed.
gpio=2=a0,np
gpio=3=a0,np
#Set up color pins
gpio=4=a2,np
gpio=5=a2,np
gpio=6=a2,np
gpio=7=a2,np
gpio=8=a2,np
gpio=9=a2,np
#GPIO 10 is available for use
#GPIO 11 is available for use
gpio=12=a2,np
gpio=13=a2,np
gpio=14=a2,np
gpio=15=a2,np
gpio=16=a2,np
gpio=17=a2,np
#GPIO 18 is available for use
#GPIO 19 is available for use
gpio=20=a2,np
gpio=21=a2,np
gpio=22=a2,np
gpio=23=a2,np
gpio=24=a2,np
gpio=25=a2,np
#GPIO 26 is available for use
#GPIO 27 is available for use

#Configure DPI signal
framebuffer_width=480
framebuffer_height=272
enable_dpi_lcd=1
display_default_lcd=1
dpi_group=2
dpi_mode=87
dpi_output_format=503846
dpi_timings=480 0 5 0 40 272 0 8 0 8 0 0 0 60 0 9600000 3
```
