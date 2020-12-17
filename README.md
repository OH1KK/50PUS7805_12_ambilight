# 50PUS7805_12_ambilight
Shell script for Philips 50PUS7805/12 TV ambilight. Minimal bash script that allows you change TV's ambilight color and brightness

## Usage
````
ambilight {+|-|white|yellow|fuchsia|red|silver|gray|olive|purple|maroon|aqua|lime|teal|green|blue|navy|black}
````
Where
````
color keyword = preset values for rgb
+ = lighter color, current rgb values + 5
- = darker color, current rgb values -5
````

## Before installation
TV's IP-address is hardcoded to script. Change it to match your tv's IP address. Use your favourite text editor.

## Installation
````
sudo apt install curl jq
sudo cp ambilight /usr/local/bin
chmod a+rx /usr/local/bin/ambilight
````
## Uninstall
`
rm /usr/local/bin/ambilight
`
## See also

http://jointspace.sourceforge.net/projectdata/documentation/jasonApi/1/doc/API.html

