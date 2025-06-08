# mfsclock

Arduino Multi Function Shield countdown timer.

## Installation

Please install first [PlatformIO](http://platformio.org/) open source ecosystem for IoT development compatible with **Arduino** IDE and its command line tools (Windows, MacOs and Linux). Also, you may need to install [git](http://git-scm.com/) in your system.

```bash
git clone https://github.com/hpsaturn/mfstimer.git
cd mfstimer
pio run -e uno --target upload
```

[![Multi Function Shield Library Demo](https://raw.githubusercontent.com/hpsaturn/MultiFuncShield-Library/refs/heads/master/images/mfs_demo_video.jpg)](https://youtu.be/_Wlip01aUAY)

## Features

- [x] Max time: 99min 59secs
- [x] Restored last config
- [x] Fast increment with long press
- [x] Beep effects

## Usage

left button   :  start/stop timer. Clear with long press  
center button :  set minutes  
right button  :  set seconds  
reset button  :  restore last timer setup  

### Troubleshoting

If in the display is showed an "E", only perform a left button long press to clear the EEPROM and set right values.

## Credits

Please review the full contributions details [here](https://github.com/hpsaturn/MultiFuncShield-Library?tab=readme-ov-file#credits).
