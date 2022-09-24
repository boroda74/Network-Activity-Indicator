# Network Activity Indicator
Network Activity Indicator is a handy swiss-knife tool for network administration and statistics.
Featuring an old-school but very missed blinking network status icon in the system tray, network traffic graph, and advanced network statistics.

It's the fork of GabNetStats application by GabSoftware (https://github.com/gabsoftware)

## Features
* Adds an icon in the statusbar that reflects network traffic
* Detailed statistics about network connections
* Context menu for easy access to network configuration
* Real-time network graph

## Notes
* .Net Framework 4.8 required
* It's portable application. Unzip it to any folder and run "Network Activity Indicator.exe"
* Use one of "color" icon sets for "Only send/receive detection (blue icon)" visual effects
* Use any icon set for "bandwidth" visual effects

## Dependencies
GabTracker : https://github.com/gabsoftware/GabTracker

## Building
* Clone this repository in one directory
* Clone the GabTracker repository in the same directory, so that both repo are located in the same directory
* Open the Network Activity Indicator solution in Visual Studio 2022
* If it cannot find the GabTracker project, in the solution, add an existing project and choose the GabTracker project
* Generate the solution
* Network Activity Indicator should build without errors.

## Many thanks to :
- GabSoftware for original application GabNetStats: https://github.com/gabsoftware/GabNetStats
- Igor Tolmachev (www.itsamples.com) for the original idea
- Valerij Romanovskij (alias ext5 on GitHub) for the Russian translation