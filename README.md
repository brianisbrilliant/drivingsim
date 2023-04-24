# drivingsim
An unreal project to talk to the driving sim at WSU.

I am sending the following message at start of game and every 4 seconds.

#id unreal

and I get, in the SimCorDX log, the following message:

PluginHandler: Received first plugin packet from 127.0.0.1:52592

Which leads me to believe that the UDP message is sent successfully and that SimCorDX has received it. I then start sending movement messages, like this one:

~M 0 0 0 0 0 0 -0.34 0 0 0 0 9.81 0 0 0 

But I do not get movement. I do not get what Euro-truck simulator gets from the log, which is

PluginHandler: Detected plugin eut2 on 127.0.0.1:54340
PluginHandler: Connected plugin eut2

Can you tell me what messages I am missin to get the plugin to receive my input?