# HomeControl
The following Node-Red flows switch on/off the various Hive devices in my home.
* Bedroom - switches the Hive plug called "Bedroom" on if it's off, off if it's on, and tweets that it's done so.
* Cloakroom - switches the Hive light called "Cloakroom" on if it's off, off if it's on, and tweets that it's done so.
* Lounge - switches the Hive plug called "Lounge" on if it's off, off if it's on, and tweets that it's done so.
* Study - switches the Hive light called "Study" on if it's off, off if it's on, and tweets that it's done so.
* Temperature - tweets the current temperature, which it gets by interrogating the Hive thermostat.
* Switch on Temperature - switches the Hive plug called "Lounge" on or off depending on what the current temperature is, which it gets by interrogating the Hive thermostat. Tweets if it has toggled the device.

Currently these flows are triggered manually.
