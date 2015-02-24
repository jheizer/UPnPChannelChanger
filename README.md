# UPnPChannelChanger
UPnP Channel Changing script (Designed for MythTV and the DISH Network VIP 211 but universal)

Supported set top boxes:
 + VIP 211

Set top boxes reported to have no UPnP interface:
+ None yet

  
If your box is not in the list above see: <https://github.com/jheizer/UPnPChannelChanger/blob/master/NewReceiver.md>
  
##Steps to use:
+ Download the script
+ Make it executable
+ Make sure you are using the HD specific channel number or else you will have the SD feed.
+ Change mythtv's channel change script to read /path/to/script/upnpchannelchanger ip.of.settop.box

To test it: /path/to/script/upnpchannelchanger ip.of.settop.box Channel#

Example: /home/jheizer/upnpchannelchanger 10.0.0.123 9520


Special Thanks to https://gist.github.com/markusfisch/6130842  For giving me a great spot to start on this script.


