# Controller Profiles
## Joystick Gremlin
These configs require the use of Joystick Gremlin. Follow the instructions from the [Joystick Gremlin website here](https://whitemagic.github.io/JoystickGremlin/quickstart/). Make sure you install vJoy as instructed and create the virtual joysticks you will need. I only use two virtual joysticks in my Joystick Gremlin profiles below. So you need to create a minimum of two. 

### HIDHide
It is also very important that you [download, install and configure HIDHide](https://github.com/ViGEm/HidHide).This app blocks other apps from seeing your real joysticks and only allows them to see the virtual joysticks from vJoy and Joystick Gremlin. 

  * Open HIDHide and make sure the Application tab is selected. 
  * Hit the "+" button and find the path to the joystick_gremlin.exe and add it to the Applications list. The HidHideClient.exe should be in the applications list by default. Add any other application that you want to see the physical joysticks. I didn't add anything else.  
  * Open the Devices tab.
    * Check the physical devices to hide. In this case, both Logitech joysticks. Leave the Virtual Joystick unchecked.
    * Ensure that all three check boxes on the bottom are checked. 
    * Check "Filter-out disconnected"
    * Check "Gaming devices only"
    * Check "Enable device hiding"

## Profiles Directory
Contains Folders with Star Citizen profiles, Joystick Gremlin profiles, and joystick layout diagrams.
1. Download the "..._exported.xml" to the "C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings".
    * Load profile in the Star Citizen console (hit ~ to open) and enter
    pp_rebindkeys "filename of the _exported.xml" See below for exact command for each profile
2. Download "..._joystick-gremlin.xml" to "%userprofile%/joystick gremlin"
    * Load the profile in Joystick Gremlin. 
    * Because your joysticks have a different identifier than mine, you must now use the swap devices tool. Open the “Actions” menu and select “Swap devices”. Click the “Assigned to” box and follow the instructions to click a button or move an access for the device you want to assign.
    * Make sure to use the awesome Input Viewer under the Tools menu to see that your controllers are working properly.
    * Adjust the curves and deadzones to match your individual devices and personal tastes. I highly suggest turning off all the controller deadzones, curves, and sensitivity settings inside of Star Citizen and only set those in Joystick Gremlin. 
    * Press the game controller icon in the taskbar to enable virtual sticks

### Dual VKB (Right Premium and Left Omnithrottle)
  * [dual-vkb_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/dual-vkb/dual-vkb_exported.xml)
  * Star Citizen Console command:
    * pp_rebindkeys dual-vkb_exported.xml
  * [dual-vkb_joystick-gremlin.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/dual-vkb/dual-vkb_joystick_gremlin.xml)
  ![dual-vkb](https://github.com/Chadarius/sc-config/blob/main/Profiles/dual-vkb/dual-vkb.png?raw=true)

### Razor Tartarus v2
* [Razor Synapse Profile](./Profiles/tartarus%20v2/tartarus-star_citizen.synapse4)
* [Razor Chroma Effects profile](./Profiles/tartarus%20v2/tartarus-star_citizen.ChromaEffects)
![Tartarus v2 Diagram](./Profiles/tartarus%20v2/Star%20Citizen%20Razer%20Tartarus.png)

### Dual-LogiExtrm
  * [Dual-LogiExtrm_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/Dual-LogiExtrm/Dual-LogiExtrm_exported.xml)
  * Star Citizen Console command:
    * pp_rebindkeys Dual-LogiExtrm_exported.xml
  * [Dual-LogiExtrm_joystick-gremlin.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/Dual-LogiExtrm/Dual-LogiExtrm_joystick-gremlin.xml)
![Dual-LogiExtrm](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/Dual-LogiExtrm/Dual-LogiExtrm_layout.png)

### DualLogiExtrm-X56-Thrtl
  * [DualLogiExtrm-X56-Thrtl_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/DualLogiExtrm-X56-Thrtl/DualLogiExtrm-X56-Thrtl_exported.xml)
  * Star Citizen Console command:
    * pp_rebindkeys DualLogiExtrm-X56-Thrtl_exported.xml
  * [DualLogiExtrm-X56-Thrtl_joystick-gremlin.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/DualLogiExtrm-X56-Thrtl/DualLogiExtrm-X56-Thrtl_joystick-gremlin.xml)
  ![DualLogiExtrm-X56-Thrtl - 1](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/DualLogiExtrm-X56-Thrtl/DualLogiExtrm-X56-Thrtl%20-%201.png)
  ![DualLogiExtrm-X56-Thrtl - 2](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/DualLogiExtrm-X56-Thrtl/DualLogiExtrm-X56-Thrtl%20-%202.png)

### LogiExtrm
  * [LogiExtrm_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/LogiExtrm/LogiExtrm_exported.xml)
  * Star Citizen Console command:
    * pp_rebindkeys LogiExtrm_exported.xml
  * [LogiExtrm_joystick-gremlin.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/LogiExtrm/LogiExtrm_joystick-gremlin.xml)
  ![LogiExtrm - 1](https://github.com/Chadarius/sc-config/blob/main/Profiles/LogiExtrm/LogiExtrm%20-%201.png?raw=true)

### x55-x56-LogiExtrm
  * [x55-x56-LogiExtrm_exported.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm_exported.xml)
  * Star Citizen Console command:
    * pp_rebindkeys x55-x56-LogiExtrm_exported.xml
  * [x55-x56-LogiExtrm_joystick-gremlin.xml](https://raw.githubusercontent.com/Chadarius/sc-config/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm_joystick-gremlin.xml)
  ![x55-x56-LogiExtrm - 1](https://github.com/Chadarius/sc-config/blob/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm%20-%201.png?raw=true)
  ![x55-x56-LogiExtrm - 2](https://github.com/Chadarius/sc-config/blob/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm%20-%202.png?raw=true)
  ![x55-x56-LogiExtrm - 3](https://github.com/Chadarius/sc-config/blob/main/Profiles/x55-x56-LogiExtrm/x55-x56-LogiExtrm%20-%203.png?raw=true)

