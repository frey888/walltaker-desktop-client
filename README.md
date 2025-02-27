# walltaker-go-client
Desktop client for Walltaker powered by golang

v2.0.0+ - Now a System Tray App! 

v2.1.0+ - Now using websockets!

## Usage
- Download the release for your OS. Edit `walltaker.toml` to use the ID associated with your link.
- Set the interval to however many seconds you want to wait between check-ins. 
- Set if you want the wallpapers cropped ("crop") or fit to show the whole image on screen ("fit")
- ???
- Profit

### Linux

Tested on Ubuntu 20.04; the following pre-requisite packages must be installed to run Walltaker 2.0.0+.

```sh
$ sudo apt install zenity libayatana-appindicator3-dev
```
## Debug Log Paths
Depending on what operating system you use the debug log path will be different

**Windows Path:** ```%LOCALAPPDATA%\.walltaker\logs\walltaker.log```

**Linux Path:** ```~/.cache/.walltaker/logs/walltaker.log```

**Mac OSX Path:** ```~/Library/Caches/.walltaker/logs/walltaker.log```

## Thanks
Special thanks to Gray over at joi.how for putting together the Walltaker project!
