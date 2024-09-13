# IR Blaster Plugin for Logitech Media Server

## Overview

This plugin adds a web interface for each SB2/3, Transporter, or SB Touch connected to the Logitech Media Server (LMS), enabling the use of the IR Blaster / Repeater / Learning functionality. It requires an IR emitter plugged into the headphone jack of your SB2/3 or SB Touch, or the IR out jack on the Transporter.

### Compatibility
- **Supported Devices**: 
  - Transporter 
  - SB2/3 
  - SB Touch

### Features
- **IR Blaster**: Use the IR emitter to control external devices via infrared.
- **LIRC Compatible**: Reads LIRC (Linux Infrared Remote Control) compatible remote files. You can find more information about LIRC at [www.lirc.org](http://www.lirc.org).
- **Remote File Setup**: Put the remote file into the IRBlaster directory and make sure its extension is `.conf`.

## Known Limitations

- SB Touch does not support RAW, IR learning, and IR repeating.
- RC6 remote support has not yet been tested.
- Technics remote support has not yet been tested.
- Remotes not using 36kHz - 40kHz carrier frequencies cannot be learned or repeated.
- **LMS Skins**: Non-default skins might show an empty IR Blaster settings page.
  - **Possible Fix**: To make it work with the Classic skin, try copying all IR Blaster HTML pages from the Default folder into a new Classic folder.

## Additional Information

Please post suggestions and issues on the [Slim Devices forum](http://forums.slimdevices.com).
