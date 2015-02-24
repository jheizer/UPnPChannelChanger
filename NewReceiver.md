If you have a receiver that does not have a file created for it already, these are the steps to see if yours has Upnp control abilities.

+ Confirm you have ethernet running to your set top box
+ Install  gupnp-universal-cp (package gupnp-tools on ubuntu)
+ Run gupnp-universal-cp
+ Look for your receiver to be listed on the left

![Example](https://github.com/jheizer/UPnPChannelChanger/raw/master/documentation/upnp1.png)

+ If you find it note the Control URL and the Type.
+ Next looks for a control point for waking it up, changing the channel, stoping it from falling asleep.  This part will vary from device to device.  For Example changing the channel on my VIP 211 does not wake it up, you must do that step first.

![Wakeup](https://github.com/jheizer/UPnPChannelChanger/raw/master/documentation/upnp2.png)

 + Here is the action for waking up.
 + Note the name of the arguement[s] with the blue arrow meaning on send and the data it wants when executing.  Here Tuner and 0 for tuner 0.
 + Do the same for the channel change action and disabling the idle.
 
![Change](https://github.com/jheizer/UPnPChannelChanger/raw/master/documentation/upnp3.png) 

Now if you take your notes and open up the script you can see all the variables at the top defining what data is to be sent and the action name.  For the parameters they are formatted as xml with <ParameterName>ValueToSend</ParameterName>

If you find that your box does support it please open a new issue with the necessary information and I'll a new script and put it in the supported list.  Likewise I'd appreciate a response if it does not and I'll note those as well.  It'll help save others from wasting time either way.



 

