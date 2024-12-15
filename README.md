
## Home Assistant Custom Component: Hemglass

[![GitHub Release][releases-shield]][releases]
[![downloads-shield]][release-link]
![Project Stage][project-stage-shield]
[![issues-shield]](issues)
[![License][license-shield]](LICENSE.md)
[![hacs_badge][hacs-shield]][hacs]
[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

A sensor for getting information about the next time Hemglass comes to visit. You give it coordinates and it will pick the closest stop, if you want a specific stop, use the coordinates for that stop.

After installing the integration using HACS and restarting your server you simply add a Hemglass stop by clicking the button below or by going to Devices & Services and adding it from there.

[![add-integration-shield]][add-integration]


|Parameter| What to put |
|--|--|
| Name | This is the name you want for the sensor in Home Assistant |
| Latitude | Latitude coordinate close to the stop you want |
| Longitude | Longitude coordinate close to the stop you want |


**Attributes:**
```
date (state)
latitude
longitude
streetAddress
city
time
ETA
salesman
depot
email
comment
canceled
canceledMessage 
truckIsActiveToday
truckLocationUpdated
truckLatitude
truckLongitude
truckIsOffTrack
routeID
```


[downloads-shield]: https://img.shields.io/github/downloads/popeen/Home-Assistant-Addon-Hemglass/total
[release-link]: https://github.com/popeen/Home-Assistant-Addon-Hemglass/releases
[releases-shield]: https://img.shields.io/github/release/popeen/Home-Assistant-Addon-Hemglass.svg
[releases]: https://github.com/popeen/Home-Assistant-Addon-Hemglass/releases
[project-stage-shield]: https://img.shields.io/badge/project%20stage-ready%20for%20use-green.svg
[issues-shield]: https://img.shields.io/github/issues-raw/popeen/Home-Assistant-Addon-Hemglass.svg
[license-shield]: https://img.shields.io/github/license/popeen/Home-Assistant-Addon-Hemglass.svg
[hacs-shield]: https://img.shields.io/badge/HACS-Default-41BDF5.svg
[hacs]: https://github.com/custom-components/hacs
[buymeacoffee-shield]: https://img.shields.io/badge/donation-Buy%20me%20a%20coffee-orange
[buymeacoffee]: https://www.buymeacoffee.com/popeen
[add-integration-shield]: https://my.home-assistant.io/badges/config_flow_start.svg
[add-integration]: https://my.home-assistant.io/redirect/config_flow_start/?domain=hemglass
