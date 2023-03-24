# Dual-VKB
Star Citizen Joystick Profile for dual VKB sticks (Right Gladiator NXT Premium and Left Gladiator EVO Omni Throttle). This is the ultimate controller setup for Star Citizen for the price, as far as I'm concerned. I somehow managed to get the right and left sticks on eBay for $165 and $163 respectively. It tooks months of checking before that happened. There are not a lot of people selling their VKB sticks. That should tell us something. The right-hand NXT Premium stick came with all the accessories. The left hand Omni Throttle didn't come with anything other than the USB cable. But I saved at least $80 on shipping by getting them used.  



## Beta Version - Still in progress!
I just got these configured on March 23, 2023. It is new. I'll probably be making a bunch of small changes. After using dual sticks and a throttle (HOTASAS) for quite some time. I've got a basic idea of how I like to use the controls in Star Citizen and which ones are the most important for me to use. I have looked at a number of layouts and found all of them to not quite be what I was looking for. But I also saw some great ideas, especially for the dual stage triggers, which are new to me. 

I started off with Subliminal/Buzzzkiller's bindings and changed them significantly to my own way of doing things. We'll see how that pans out in the coming weeks! Subliminal has an awesome blank template so I used that for my layout. 

## VKB Config
The VKB config app is a hot mess. There isn't really any documentation either. But I figured out how to get the analong mini stick buttons to work as a regular joystick button with a single press but still work to switch the mini sticks from a hat to an analog mini stick with a long press. This gives me 6 axes and 30 buttons per stick. 

I set both sticks to the defaults and then changed the mini stick config, then exported the config which are available here as .CFG files. (There is a video here that describes how to configure them)[https://youtu.be/fidQmVGsvZQ?t=542].

### Joystick Gremlin

Download the ["dual-vkb_joystick-gremlin.xml"](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/dual-vkb/dual-vkb_joystick-gremlin.xml) and load the profile in Joystick Gremlin. 

Adjust your deadzones in Joystick Gremlin as required (the VKB sticks probably won't need much if any). Every joystick is a little different!

Because your joysticks have a different identifier than mine, you must now use the swap devices tool. Open the “Actions” menu and select “Swap devices”. Click the “Assigned to” box and follow the instructions to click a button or move an access for the device you want to assign. 

Make sure to click the game controller icon on the Gremlin taskbar and that it shows as green. If it is green, it is enabled. If you ever unplug and re-plug in a joystick you will need to switch to Joystick Gremlin and re-enable the profile again. The cool thing is that you can do that without having to restart Star Citizen thanks to vJoy always having a virtual joystick ready to use.


### Star Citizen Layout

Download and copy [dual-vkb_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/dual-vkb/dual-vkb_exported.xml) to 
"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings" or wherever your install happens to be. 

In Star Citizen, open the console and cut and paste the following command:

pp_rebindkeys dual-vkb_exported.xml

### Joystick Layout
Here is a PDF of the [dual-vkbl](https://github.com/Chadarius/sc-config/raw/main/Profiles/dual-vkb/dual-vkb.pdf). I designed it with LibreOffice Draw. The original file is available in the repo as dual-vkb.odg. There is also a PNG at 150 dpi. 