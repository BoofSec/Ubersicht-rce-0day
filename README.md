# Übersicht RCE 0day
Unauthenticated remote command execution 0day exploit for Übersicht.


## Description
Übersicht is a desktop widget application for macOS. Widgets are easily customizable as they are written using HTMl5, and can execute OS shell commands and display their output.

Übersicht provides a HTTP server exposing an endpoint that's used for widgets to execute OS shell commands. The endpoint is not protected with any form of authentication, meaning if the webserver is exposed to WAN, a remote attacker can execute arbitrary shell commands and gain remote access to the vulnerable system.

The HTTP webserver is listening on port 41416 by default.


## Author

**cs:**
- [GitHub](https://github.com/ecriminal)
- [Twitter](https://twitter.com/elordcs)
- [Telegram](https://t.me/erapist)
- Discord: cs#0420 | 806059275678908418

## Date

The vulnerability was discovered and exploit was developed on **08/09/2021**, and made public on **09/09/2021**.

```
 ________  ________  ________  ________ ________  _______   ________     
|\   __  \|\   __  \|\   __  \|\  _____\\   ____\|\  ___ \ |\   ____\    
\ \  \|\ /\ \  \|\  \ \  \|\  \ \  \__/\ \  \___|\ \   __/|\ \  \___|    
 \ \   __  \ \  \\\  \ \  \\\  \ \   __\\ \_____  \ \  \_|/_\ \  \       
  \ \  \|\  \ \  \\\  \ \  \\\  \ \  \_| \|____|\  \ \  \_|\ \ \  \____  
   \ \_______\ \_______\ \_______\ \__\    ____\_\  \ \_______\ \_______\
    \|_______|\|_______|\|_______|\|__|   |\_________\|_______|\|_______|
                                          \|_________|                   
```
