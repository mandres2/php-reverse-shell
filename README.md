# php-reverse-shell

This file contains PHP code used to connect to a target's computer utilizing system applications

The tool is designed for those situations during a pentest where one has upload access to a webserver that’s running PHP.  Uploading this script to somewhere in the web root then running it by accessing the appropriate URL in a browser will allow the script to open an outbound TCP connection from the webserver to a host and port of choice.  Bound to this TCP connection will be a shell.

This interactive shell will allow one to run interactive programs like telnet, ssh and su.  It differs from a web form-based shell which allows one to send a single command, then return the output.
