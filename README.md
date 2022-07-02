# Loconet
Loconet Accessory Controller
CR4114 Loconet Accessory Controller

Uses: To control Servos, Tortoise etc for turnouts, LED lighting or accessories
      with appropriate Loconet DCC decoders. Uses a Arduino Nano and sketch with a keypad and
      16x2 I2C LCD display to select turnouts 1 to 99. Four Routes are included to 
      select multiple turnouts using 200 thru 203. Each route turnout is hard coded into
      the sketch and may be changed as suitable to the application. Three digit and greater
      entries (other than 200 - 203) result in an invalid entry to show the operator nothing is 
      connected with those addresses. This sketch just sends Loconet accessory commands and 
      does not use feedback from Loconet to determine turnout position.
