# DuckyInPython Instructions!
___________________
## Written By u/Sl66pBTW / Sl66p
### THIS IS INSTRUCTIONS ON HOW TO TURN A RASPBERRY PI PICO INTO A HID MANIPULATOR
### I AM NOT RESPONSIBLE FOR ANY ACTIONS TAKEN WITH THIS HID MANIPULATOR IN ANY WAY SHAPE OR FORM!
### USE AT YOUR ON DISCRETION!
___________________
## Step 1, Format:

Firstly, open the "neededfiles" folder, then plug in your pico.

Now you will take the file named "adafruit-circuitpython-raspberry_pi_pico-en_US-7.2.3.uf2",
and drag it into your pico's memory. It will restart and pop up as "circutinpython".

Then, drag the "duckyinpython.py" file into your pico's memory. Delete the "code.py" file,
and rename the "duckyinpython.py" to "code.py", then take the "adafruit_hid" folder and drag it
into the library (file named "lib"), congrats! Now your pico will work as an HID Manipulator.

## Step 2, Payload:

Now you will take your payload script (written in an .txt form, typically.), and you will save
the file as (do this in the top left corner), and name it "payload.dd", drag this into your pico's
memory, 

(Payloads can be found at https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads !)

!!!CAUTION!!! THE FILE WILL IMMEDIATELY RUN AFTER THE FILE IS UPLOADED! BE READY TO UNPLUG YOUR PICO! !!!CAUTION!!!

congrats! your payload can now be dumped onto another machine!

## Resetting The Pico:

Simply hold the little white "BOOTSEL" button on your pico while plugging it into your machine, then drag the "Flash_Nuke.uf2" file 
into your pico's memory, it will restart and boot like factory new!
