# UPDATED NOTE
This is a fork from bpennypacker/SenseME-Indigo-Plugin version 0.7.0

This only works with the old firmware (Haiku by BAF app)

This plugin has been updated to Python 3 for Indigo 2023.1

After upgrading, if you see any errors, you need to reconfigure each fan device.  Edit Device Settings for each device and click Save.  That should fix it.  You only need to do this the first time after upgrading.

I have done some refactoring of how commands are sent, and have added some eatra error checking.  I have done some minimal testing and it seems to work.

You can report bugs here and I will attempt to fix them, but I do not intend to maintain this plugin indefinitely.  Hopefully someone can write a new plugin for the new firmware.

# ORIGINAL NOTE

This project is no longer supported, in part because Big Ass Solutions has completely rewritten their firmware and this plug-in is not compatible with it, and in part because I no longer use Indigo. This project will remain on Github for historical purposes.

# SenseME-Indigo-Plugin
[Indigo](http://www.indigodomo.com)  Plugin for [Big Ass Solutions](http://www.bigasssolutions.com/) residential line of [Haiku ceiling fans](https://www.haikuhome.com) with [SenseME Technology](https://www.haikuhome.com/senseme).

If you have a Haiku fan with the optional SenseME add-on then this plug-in will allow you to interact with the fan from Indigo, both by directly adjusting settings and by reacting to triggers. The following is a partial list of features:

### Triggers

* Fan (On/Off)
* Light (On/Off)
* Fan Speed
* Light Brightness
* Smart Mode (Cooling/Heating/Off)
* Whoosh Mode (On/Off)
* Sleep Mode (On/Off)
* Beep (On/Off)
* Indicators (On/Off)
* Cooling Temperature Changed
* Sleep Temperature Changed
* Direction (Forward/Reverse)

### Actions

* Turn Fan On/Off
* Turn Light On/Off
* Adjust Fan Speed
* Adjust Light Brightness
* Turn Fan motion sensor On/Off
* Turn Light motion sensor On/Off
* Enable Smart Mode
* Turn Whoosh Mode On/Off
* Set Fan Direction Forward/Reverse
* Set Fan Indicators On/Off
* Set Fan Beep On/Off
* Set Sleep Mode On/Off
* Adjust Sleep Temperature
* Adjust Smart Cooling Temperature

For more detailed information on this plugin please see [this documentation](http://bruce.pennypacker.org/tag/senseme-plugin/).

The plugin can be found [on GitHub](https://github.com/bpennypacker/SenseME-Indigo-Plugin/releases) or in the [Indigo Plugin Store](http://www.indigodomo.com/pluginstore/).
