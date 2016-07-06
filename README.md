# PiRemoteBench
Instructions for setting up a Raspberry Pi as a Remote Test Bench

# Introduction
I work remotely supporting hardware with a number of functions, this hardware sits in a lab several states away.  I need to be able to manage these devices as if I were in that lab.  To this end I am putting together a low-cost remote computing environment that will allow me to work remotely. 

# Interfaces
- Built in Ethernet will tie into the corporate network. This is the interface that I will remote connect through.
- USB/Ethernet dongle will connect to the LAN interface on the network device under test.
- USB Hardware Fax/Modem will connect to the telephony port on the network device under test.
- Wireless interface may be used to also connect to the wireless interface on the network device.

# Hardware
- Raspberry Pi (I am using the Model 3B)
- USB2E100B USB Ethernet dongle 
- TrendNET 56K USB Phone/Internet/Fax Modem TFM-561U

# Software Installation
- Update Rasbperian to latest packages
  - "sudo apt-get update"
  - "sudo apt-get upgrade"
- XRDP (for remote desktop)
  - "sudo apt-get install xrdp"
  - https://www.maketecheasier.com/enabling-remote-desktop-access-on-raspberry-pi/
- 
