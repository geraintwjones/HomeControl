# HomeControl
Node-Red applications to control devices connected to Hive in my home.

The following flows are used to switch the devices connected to Hive nodes.
* Bedroom - switches the device connected to the Hive plug called "Bedroom" on if it's off, off if it's on, and tweets that it's done so.
* Cloakroom - switches the Hive light called "Cloakroom" on if it's off, off if it's on, and tweets that it's done so.
* Lounge - switches the device connected to the Hive plug called "Lounge" on if it's off, off if it's on, and tweets that it's done so.
* Study - switches the Hive light called "Study" on if it's off, off if it's on, and tweets that it's done so.
* Temperature - tweets the current temperature, which it gets by interrogating the Hive thermostat.
* Switch on Temperature - switches the device connected to the Hive plug called "Lounge" on or off depending on what the current temperature is, which it gets by interrogating the Hive thermostat. Tweets if it has toggled the device.

Currently these are only triggered manually via the Node-Red applications.
