# ESP8266_blink_SOS_xiaolaba
burn in test for ESP8266, builtin LED will be flashing SOS

https://youtu.be/kLBpjeUCMfE
   
[![ESP8266_blink_SOS_xiaolaba](http://img.youtube.com/vi/kLBpjeUCMfE/0.jpg)](https://www.youtube.com/watch?v=kLBpjeUCMfE)

Update by xiaolaba, 2019-MAR-02

// ESP8266_blink_SOS
// 2019-MAR-02

hardware : NodeMCU or ESP01 / ESP-12 or those clone.
           set CPU 80MHZ, 4M no SPIFF

Burn rom image:
  hold GPIO-0 down, prese RESET, releasr RESET, release GPIO-0, MCU in flash mode
  open dosbox.bat, under command line, specifiy COM#
  c.bat : to clear flash
  b.bat : to burn in rom images
  
  example : c 12
  explain clear flash via COM PORT 12

Run this ESP8266, up on burn in is done
  power up, builtin LED will be flash SOS

optional:

Remark:

special note:
  PL2303 is not working for 26MHZ & boot time 74880 baud.
  CH340G / CP2102 is fine.
