
GRoot V 1.3.0 , (Gambas RunAsRoot Tool) A VERY simple GUI sudoer like GKSU.
Written by Bruce Steers using the excellent GambasBasic

V3.0
Added it app icon view (show icon of command being run)
Added routine to check for incorrect password and retry if fail.

V2.0
Added colour/font settings
Option to ask how to run if blank password or just run without root

V1.0
A basic window no frills nothing fancy


Works VERY simply by creating a hidden Terminal and launching a program prefixed with 'sudo'.
Then simply auto-types the entered password.

Has an option to run the command normally without superuser.
Uses MaskBox to hide password characters but has a "peek" button to show text.
Change font / colour defaults.
Has a simple Install script to copy it to /usr/bin (or somewhere else)
Package contains the source code and source code for a simplified example version.


Example Usage: (once copied to /usr/bin)
Drag and drop your system menu launcher for your text editor (mine is pluma) onto your desktop and right click it and select it's properties...
For my launcher the default command set to run is 'pluma %U' so i change it to 'groot pluma %U' and save.
Now i can double click the desktop icon or drag-n-drop files onto it and before the editor loads i get the requester shown below giving me the option to run as root or not. 
