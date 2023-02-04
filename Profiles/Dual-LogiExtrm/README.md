# Star Citizen Dual Logitech Extreme Joystick Config
Star Citizen Dual Logitech Extreme 3D Pro configuration using Joystick Gremlin.

Follow the instructions from my [joystick gremlin dual logi.pdf](
https://github.com/Chadarius/star-citizen-dual-logi-extreme/blob/main/joystick%20gremlin%20dual%20logi.pdf).

## Quick Reference
Seriously read the PDF above before just trying this because it won't work :)

### Joystick Gremlin

Download the ["joystick gremlin dual logi.xml"](https://raw.githubusercontent.com/Chadarius/star-citizen-dual-logi-extreme/main/joystick%20gremlin%20dual%20logi.xml) and load the profile in Joystick Gremlin. 

Adjust your deadzones in Joystick Gremlin as required. Every joystick is a little different!

Because your joysticks have a different identifier than mine, you must now use the swap devices tool. Open the “Actions” menu and select “Swap devices”. Click the “Assigned to” box and follow the instructions to click a button or move an access for the device you want to assign. The right joystick should be assigned to the first Extreme 3D pro in the list and the left the second joystick. 

Make sure to click the game controller icon on the Gremlin taskbar and that it shows as green. If it is green, it is enabled. If you ever unplug and re-plug in a joystick you will need to switch to Joystick Gremlin and re-enable the profile again. The cool thing is that you can do that without having to restart Star Citizen thanks to vJoy always having a virtual joystick ready to use.

### Star Citizen Layout

Download and copy [vjoy-dual-logi.xml](https://raw.githubusercontent.com/Chadarius/star-citizen-dual-logi-extreme/main/vjoy-dual-logi.xml) to 
"C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings" or wherever your install happens to be. 

In Star Citizen, open the console and cut and paste the following command:

pp_rebindkeys vjoy-dual-logi

## Dual Logi Layout
![dual logi layout](https://github.com/Chadarius/star-citizen-dual-logi-extreme/blob/main/dual%20logi%20layout.png?raw=true)