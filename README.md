# NTP-Clock

ESP8266 NTP Clock

TM1637 CLK -> weMos-d1 gpio 12

TM1637 DIO -> weMos-d1 gpio 14

Ap-WiFi -> weMos-d1 gpio 13

SFH203  -> weMos-d1 ADC 0


Get esp8266ntp.ino.generic.bin and program esp8226.

https://www.aranacorp.com/en/generating-and-uploading-bin-files-to-an-esp8266/

To get Ap mode WiFi press buttom S1

 ssid = "espnet";
 
 password = "espnetpass";
 
 Open web http://192.168.4.1/ and put your ssid, password and utc Offset (0-24)
 
 Reboot and profit!
