# SmartThings-RandomHue
Random Hue app for SmartThings (abandoned!)

There were other apps but none quite worked the way I wanted ... so I wrote my own.

## Features

This is an app for SmartThings that can change the color of lights on a schedule.

Color can change every:
 * 1 minute
 * 5 minutes
 * 10 minutes 
 * 15 minutes 
 * 30 minutes 
 * 1 hour 
 * 3 hours

**Note:** It seems like recent changes to the SmartThings cloud may have made 1 minute actually run every 5 minutes.

It has 3 color changing modes:
1. Random 
1. From list (select from built-in list of colors that can be used)
1. Incremental (walk the H portion of the HSV scale)

Lights can be controlled individually, or as a group (all change at the same time).

Start/Stop times can be absolute or relative to Sunrise/Sunset (with optional offset).

## Screenshots

See the `screenshots/` directory:

 * [Main Config 1/2](screenshots/1-Main-Config.png)
 * [Main Config 2/2](screenshots/2-Main-Config.png)
 * [Start and Stop times](screenshots/3-Start-and-Stop.png)
 * [Color change modes](screenshots/4-Color-Mode.png)
 
## Abandoned

I have since moved on to [Home Assistant (HA)](https://home-assistant.io/) because it is local only and written in Python, a language I have significantly more familiarity with.

Rather than let the code just die, I figured I would put it out, just in case someone wants to use it. The code is licensed under the GPL 3, please feel free to fork and continue development.