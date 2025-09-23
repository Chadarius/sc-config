# Star Citizen Initial Setup 3.21

## PC Configuation
### Performance Settings
[See my Nvidia Performance Guide on the Spectrum Forums](https://robertsspaceindustries.com/spectrum/community/SC/forum/51473/thread/my-nvidia-performance-settings) for more discussions.
  * Virtual Memory
  * Anti-virus exclusions
  * Nvidia Driver and Configurations
  * etc..

## Third Party Software
### Comms
  * Discord
  * Mumble, DCS-SRS Client, etc...
### Voice Attack
  * [Voice Attack and HCS Voice Pack ASTRA - See my StarCitizenVoiceAtk Github for more](https://github.com/Chadarius/StarCitizenVoiceAtk) 
### OpenTrack
  * Head Tracking configured to use TrackIR with Star Citizen
### SmoothTrack
  * Phone app that works with OpenTrack
### Joystick Config
  * See main Readme for more
### Streaming
  * OBS

## Star Citizen Config
  * Copy control profile to C:\Program Files\Roberts Space Industries\StarCitizen\LIVE\USER\Client\0\Controls\Mappings
  * Copy user.cfg to C:\Program Files\Roberts Space Industries\StarCitizen\LIVE
### In-game Config
#### Game Settings
  * Show Hints – No
  * Control Hints - No
  * Defaults - Flight Automatic Slowdown On - No
  * Defaults - Flight – Gsafe – Defaults On – No (Removed in 3.23)
  * Defaults - Fligth – Gsafe – Disable When Boosting - Yes
  * Defaults - Flight – Proximity Assist Defaults On – No 
  * Pilot - E.S.P. - Strength – 1.0 (3.23 was .8?)
  * Pilot - E.S.P. Damping Curvature – 1.0 (Removed in 3.23)
  * Pilot – Velocity Indicator – Always On
  * Guns - Fallback Convergence Distance (meters) - 100
  * Defaults - Weapons - Precision Lines On - Yes
  * Defaults - Weapons - Fading PiPs On - No
  * Vehicles - Spaceship - Weapons - Gimbal Mode - Default - Fixed
  * Vehicles - Ground - Weapons - Gimbal Mode - Default - Fixed
  * Vehicles - Targeting - Enable Crosshair Animation - No (new in 3.23)
  * Vehicles - Targeting - Enable Auto Zoom On Locked Target - No
  * Pilot – Look Ahead – Enabled – No 
  * Driver – Look Ahead – Enabled - No
  * Turret – Look Ahead – Enabled – No 
  * G-force Induced Head Movement – .25
  * G-Force Induced Afterburner Zoom – 0
  * Global Camera Shake – .25
  * Show Friendly Contact Nameplate – Yes
  * Show Neutral/Hostile Contact Nameplate – Yes
  * Show Contact Distance – Yes
  * Emissions HUD – Display Signature Values

#### Graphics
  * Gamma – 50-60
  * Brightness – 50
  * Contrast – 50
  * Resolution 1920x1080 – user.cfg
  * Window Mode – Borderless/Fullscreen – user.cfg
  * Quality – Very high
  * Scattered Object Distance – Low/Medium
  * Terrain Tessellation Distance – Low/Medium
  * Screen Space Shadows - Medium
  * Planet Volumetric Clouds – Medium (or off)
  * Field of View – 85 
  * Motion Blur – off
  * Vsync – no
  * Sharpening - 0
  * Chromatic Aberration – 0
  * Film Grain – No
#### Audio
  * Sound effects volume – 75
  * Music volume – 0
  * Speed volume - 75
  * Ship computer speed volume – 75
  * Simulation announcer volume – 75
  * Ship computer verbosity - Medium
  * Audio-Driven Camera Shake Strength - 0
  * Play Audio when Game in Background – Yes 
#### Controls
  * Inversion – Invert controller axes as needed. Can also be controlled in Joystick Gremlin
  * Deadzone Joystick All Axes – set to zero (deadzones handled in Joystick Gremlin)
  * Joystick Sensitivity Curves – all set to 1.0 (curves are handled in Joystick Gremlin)
#### Keybindings
  * run the pp_rebindkeys command with the appropriate controller export XML file
#### Comms, FOIP, & Head Tracking
  * Faceware – Enable FOIP (Facial Tracking) – No
  * Head Tracking – General – Source – TrackIR
  * Head Tracking – General – Toggle – Enabled – Yes
  * Head Tracking – General Toggle – Disable During mobiGlas - Yes
  * Head Tracking – General Toggle – Disable During Interaction Mode - Yes
  * Head Tracking – General Toggle – Enable Roll in Seats - No
  * Head Tracking – General – External View – Disabled in Inventory – Yes
