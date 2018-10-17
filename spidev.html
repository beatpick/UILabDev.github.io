#!/usr/bin/python
import spidev
import time
import os
import RPi.GPIO as gpio

# Start SPI connection
spi = spidev.SpiDev()
spi.open(0,0)

# Read MCP3008 data
def analogInput(channel):
  adc = spi.xfer2([1,(8+channel)<<4,0])
  data = ((adc[1]&3) << 8) + adc[2]
  return data

while True:
  print("0: "+str(analogInput(0)))
  print("1: "+str(analogInput(1)))
  print("2: "+str(analogInput(2)))
  print("3: "+str(analogInput(3)))
  print("4: "+str(analogInput(4)))
  print("5: "+str(analogInput(5)))
  print("6: "+str(analogInput(6)))
  time.sleep(0.2)
