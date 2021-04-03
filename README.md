# Ergodone-keyboard


This is a summary of what I had to do to flash my ergodone, this use various tutorial I could find online...
For the whole proccess I used Windows.

I bought an ergodone PCB on Aliexpress, K.T.E.C. Ver 1.3. 

<img src="Images/Ergodone.PNG" width="500" heigth="500">

This PCB uses an Arduino Pro Micro with a MEGA32U4 chip.




To enter the flashing mode for the ergodone you need to press to keys while plugging in the keyboard.

<img src="Images/Flashmode.PNG" width="500" heigth="500">

Once the keyboard is in flashing mode you can do the following instruction to upload the hex file to the micro controller.


```
C:\WINDOWS\system32>cd C:\tkg-toolkit-master\windows\bin

C:\tkg-toolkit-master\windows\bin>hid_bootloader_cli -mmcu=atmega32u4 ergodone_test123.hex
```
