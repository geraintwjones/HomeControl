# HomeControl
Node-Red applications to control devices connected to Hive in my home.

The folowing flows are used to toggle the devices connected to the relevant Hive nodes.
* Bedroom - switches the device connected to the Hive plug called "Bedroom" on if it's off, off if it's on, and tweets that it's done so.
* Cloakroom - switches the Hive light called "Cloakroom" on if it's off, off if it's on, and tweets that it's done so.
* Lounge - switches the device connected to the Hive plug called "Lounge" on if it's off, off if it's on, and tweets that it's done so.
* Study - switches the Hive light called "Study" on if it's off, off if it's on, and tweets that it's done so.
* Temperature - tweets the current temperature, which it gets by interrogating the Hive thermostat.

Currently these are only triggered manually via the Node-Red applications.
