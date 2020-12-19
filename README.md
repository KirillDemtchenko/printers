* Install raspberry pi OS DEBIAN 10.6
* Enable wifi (raspi-config)
* Enable ssh (raspi-config)
* Install CUPS
  sudo apt-get install cups
  service cups start
  sudo usermod -a -G lpadmin pi
* Install driver (?)
  hplip-3.20.11.run
* Download .ppd file
  HP-LaserJet_Pro_P1102.ppd
* Open port on CUPS + command(?)
* Add printer via web interface or command line
* Install wrapper
  sudo apt-get install printer-driver-foo2zjs-common printer-driver-foo2zjs
* Try print file
