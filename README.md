# UPnPChannelChanger
UPnP Channel Changing script (Designed for MythTV and the DISH Network VIP 211 but universal)

Supported set top boxes:
 + VIP 211
 + VIP 211k
 + VIP 222k (vip222k_changer)

Set top boxes reported to have no UPnP interface:
+ None yet

  
If your box is not in the list above see: <https://github.com/jheizer/UPnPChannelChanger/blob/master/NewReceiver.md>
  
##Steps to use:
+ Download the script
+ Test that sure you are using the HD specific channel number or else you may have the SD feed.  (Dish I have to use the 9XXX channel numbers.)
+ Change mythtv's channel change script to read /path/to/script/upnpchannelchanger ip.of.settop.box

For usage information for your particular script: /path/to/script/upnpchannelchanger -h

To aid in converting you channel data over to the HD specific numbers download and run the channellist script above.  It will return all subscribed channel numbers from your receiver. Run channellist -h for curl and wget usage.


Special Thanks to https://gist.github.com/markusfisch/6130842  For giving me a great spot to start on this script.


