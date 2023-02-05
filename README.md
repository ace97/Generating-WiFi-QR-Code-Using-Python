# Generating-WiFi-QR-Code-Using-Python

Whenever my friends visit me, the first thing they'd ask me is the WiFi password. Remembering all of the WiFi passwords that we use is hard (especially, long alphanumeric sequences) so I searched for an easier way to get it than going to the dark corner in the basement to check what the password was...

-For this simple project, I used "wifi_qrcode_generator" and "subprocess" functions.

-Using "subprocess" to run cmd/bash commands to get connected network details such as SSID and Password from my PC.

-And finally using "wifi_qrcode_generator" I'm generating a QR code with the SSID and Password we got from running script in "subprocess"

-- The arguments to get the values for netwrk SSID and Passwrod may vary from system to system , I had to print the output to see how the values are displayed 
and sometimes there may be hidden tabs/spaces in SSIDs or Passwords so watch out for those little errors.
