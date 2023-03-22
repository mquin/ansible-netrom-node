This is an ansible role intended to be used to configure a Debian Linux system 
as an AX.25 NET/ROM node.
It is based on https://www.elite.uk.com/mike/posts/linux-netrom-setup/ , and assumes
a NinoTNC USB KISS TNC is being used.

It has been tested on Raspberry Pi OS Lite (bullseye).

The variables defined in defaults/main.yml should be overriden to define your callsign
and other relevant parameters for your environment.
