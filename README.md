# PicoPN532
Raspberry Pi Pico code for PN532 NFC reader/writer


Step 1. Go to https://circuitpython.org/board/raspberry_pi_pico/ and Download the CircuitPython and install on your Raspberry Pi Pico.

Step 2. To install hold down the boot/sel button on Raspberry Pi Pico before you plug it into your laptop. Once you have plugged it in drag the downloaded CircuitPython code you downloaded and rop onto the pico drive.

Step 3. Go to https://github.com/adafruit/Adafruit_CircuitPython_PN532 and download the adafruit_pn532 folder and add it to your Raspberry Pi Pico.

Step 4. Download a copy of the pn532_readwrite_mifare.py from this repo and also put it on your Raspberry Pi Pico. 

Step 5. Wire up your NFC532 hat to Pico using Pin Layout from here. https://www.raspberrypi-spy.co.uk/2021/01/pi-pico-pinout-and-power-pins/#prettyPhoto

  NFC Hat Pin       Pico
  Gnd -------->     Gnd
  5v5 -------->     VBUS
  RX  -------->     GP5
  TX  -------->     GP4
  
Run Code from Thony it will take awhile for the code to show but should now work.:-)
