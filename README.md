# Übersicht RCE 0day
Unauthenticated remote command execution 0day exploit for Übersicht.

![screenshot](https://raw.githubusercontent.com/BoofSec/Ubersicht-rce-0day/main/poc/screenshot.png)

## Description
[Übersicht](https://tracesof.net/uebersicht/) is a desktop widget application for macOS. Widgets are easily customizable as they are written using HTML5, and can execute OS shell commands and display their output.

Übersicht provides a HTTP server exposing an endpoint that's used for widgets to execute OS shell commands. The endpoint is not protected with any form of authentication, meaning if the webserver is exposed to WAN, a remote attacker can execute arbitrary shell commands and gain remote access to the vulnerable system.

The webserver is listening on port 41416 by default.


## Author

**cs:**
- [GitHub](https://github.com/ecriminal)
- [Twitter](https://twitter.com/elordcs)
- [Telegram](https://t.me/erapist)
- Discord: cs#0420 | 806059275678908418

## Date

The vulnerability was discovered and exploit was developed on **08/09/2021**, and made public on **09/09/2021**.

#

```

 '||''|.                     .'|.  .|'''.|                  
  ||   ||    ...     ...   .||.    ||..  '    ....    ....  
  ||'''|.  .|  '|. .|  '|.  ||      ''|||.  .|...|| .|   '' 
  ||    || ||   || ||   ||  ||    .     '|| ||      ||      
 .||...|'   '|..|'  '|..|' .||.   |'....|'   '|...'  '|...' 

```
[GitHub](https://github.com/boofsec) · [Twitter](https://twitter.com/boofsec) · [Instagram](https://instagram.com/boofsec) · [Website](https://zeroday.lol/)
