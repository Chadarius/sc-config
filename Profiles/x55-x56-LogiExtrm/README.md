# x55-x56-LogiExtrm
Star Citizen Joystick Profile for X-55/X-56 Plus Logitech Extreme for Throttle and Dual Sticks. It works best with the X-56 because you can get true 6 degrees of movement with just the right stick and throttle. I use the left stick when I dogfight. This is because I have 6 degrees of movement with dual sticks and can still control power to weapons, shields, and engines with my thumb. That just isn't possible with the throttle in my left hand. 

That being said, you can always add in Voice Attack to control power, and use just the HOTAS I suppose. I think HOSAS is still the best for dogfighting. 

## Beta Version - Still in progress!
I'm not really finished with the whole thing, but I'm using it as my daily driver at this point. 

## Quick Reference

### Joystick Gremlin

Download the ["x55-x56-LogiExtrm_joystick-gremlin.xml"](https://github.com/Chadarius/sc-config/raw/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm_joystick-gremlin.xml) and load the profile in Joystick Gremlin. 

Adjust your deadzones in Joystick Gremlin as required. Every joystick is a little different!

Because your joysticks have a different identifier than mine, you must now use the swap devices tool. Open the “Actions” menu and select “Swap devices”. Click the “Assigned to” box and follow the instructions to click a button or move an access for the device you want to assign. The right joystick should be assigned to the first Extreme 3D pro in the list and the left the second joystick. 

Make sure to click the game controller icon on the Gremlin taskbar and that it shows as green. If it is green, it is enabled. If you ever unplug and re-plug in a joystick you will need to switch to Joystick Gremlin and re-enable the profile again. The cool thing is that you can do that without having to restart Star Citizen thanks to vJoy always having a virtual joystick ready to use.

The basic layout is that the X55/56 joysticks are vJoy Device 1, while the X55/56 throttle is vJoy Device 2. The Logitech Extreme left-hand stick is combine into both vJoy Device 1 and vJoy Device 2. This is primarily to keep things simple for Star Citizen and the fact that the Extreme stick shares axis and buttons with both the throttle and the right stick. 

### Star Citizen Layout

Download and copy [x55-x56-LogiExtrm_exported.xml](https://github.com/Chadarius/sc-config/raw/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm_exported.xml) to 
"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings" or wherever your install happens to be. 

In Star Citizen, open the console and cut and paste the following command:

pp_rebindkeys x55-x56-LogiExtrm_exported.xml

### Joystick Layout
Here is a PDF of the [x55-x56-LogiExtrm](https://github.com/Chadarius/sc-config/raw/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm.pdf). I designed it with LibreOffice Draw. The original file is available in the repo as x55-x56-LogiExtrm.odg. 