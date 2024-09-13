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

## Version History

| Date       | Version | LMS Version  | Firmware         |
|------------|---------|--------------|------------------|
| 02/21/2012 | 6.2.1   | >= 7.6.x     | SB: >=29, Transporter: all, SB Touch: all |
| 03/08/2010 | 5.6.1   | >= 7.4.x     | SB: >= 29, Transporter: all |
|            | 5.5     | 7.x          | SB: >= 29, Transporter: all | 
| 07/26/2008 | 5.4     | 7.x          | SB: >= 29, Transporter: all |
| 05/31/2007 | 4.1.3   | 6.5.x        | SB: >= 29, Transporter: all |
| 08/09/2006 | 3.7     | 6.2.x, 6.3.x | >= 29            |
| 10/11/2005 | 2.6     | 6.2          | >= 23            |

## Additional Information

For more details and technical background, visit the [Slim Devices Wiki](#).

Please post suggestions and issues on the [Slim Devices forum](http://forums.slimdevices.com).
