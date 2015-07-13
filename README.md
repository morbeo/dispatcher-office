# dispatcher-office
A simple NetworkManager dispatcher script that acts depending on the wireless network you're on.

Based on [@justintime](https://github.com/justintime)'s [2008 script](http://sysadminsjourney.com/content/2008/12/18/use-networkmanager-launch-scripts-based-network-location/), the purpose of this dispatcher script is to run specific tasks depending on the ESSID of the wireless network that you are currently connected to. This can automate regular location-based activities at the office or at school.

The script depends on NetworkManager and its dispatcher daemon. **NOTE** Scripts in /etc/NetworkManager/dispatcher.d/ have to be owned by root and writable by owner only in order to be executable. Refer to the [ArchWiki entry on NetworkManager](https://wiki.archlinux.org/index.php/NetworkManager#Network_services_with_NetworkManager_dispatcher) for more information.
