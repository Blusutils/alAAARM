# alAAARM <img src="./ALAAARM.png" align="center" width="50">
"An Alarm ~clock in~ Action". Simple app build with WPF. Helps you to create and manage alarms/timers/schedules.

| |This project is in Blusutils EEE Projects list| |
-|-|-
| |[Check it out here](https://github.com/Blusutils/projEEECTS)| |

## Features
* Alarms
* Timers
* Schedules (classic/cron-inspired)

* Preferences for each object
* Custom sounds
* [Addons](#addons) (e. g. [cendify](https://github.com/EgorBron/alaaarm-cendify))
* Minimization to tray (WIP)

## Addons
Want to create addon for alAAARM? Okay! Follow this guide:
1. Create .NET 6.0 `ClassLibrary` project.
2. Add references to:
  * alAAARM.alAAARM (from executable)
  * System.Windows (if not added yet)
3. Create class named `Addon` (be sure to call it exactly that) and derived from alAAARM.Addon.
4. Do what you want.
5. Build project.
6. Put output DLL file to `addons` folder in alAAARM directory, or directly add it (for now it won't remember DLL path).
