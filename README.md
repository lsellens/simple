# The Simple WiFi Thermostat Home Assistant integration.
[![HACS](https://img.shields.io/badge/HACS-Default-orange.svg?style=for-the-badge)](https://hacs.xyz)
[![Download Count](https://img.shields.io/github/downloads/lsellens/thesimple-thermostat/total?style=for-the-badge)](https://github.com/lsellens/thesimple-thermostat/releases)
[![Latest Release Number](https://img.shields.io/github/release/lsellens/thesimple-thermostat/all?style=for-the-badge)](https://github.com/lsellens/thesimple-thermostat/releases/latest)
[![Latest Release Download Count](https://img.shields.io/github/downloads/lsellens/thesimple-thermostat/latest/total?style=for-the-badge)](https://github.com/lsellens/thesimple-thermostat/releases/latest)
[![Open Issues](https://img.shields.io/github/issues/lsellens/thesimple-thermostat?style=for-the-badge)](https://github.com/lsellens/thesimple-thermostat/issues)
[![Validation Status](https://img.shields.io/github/actions/workflow/status/lsellens/thesimple-thermostat/validate.yml?style=for-the-badge)](https://github.com/lsellens/thesimple-thermostat/actions)
[![License](https://img.shields.io/github/license/lsellens/thesimple-thermostat?style=for-the-badge)](LICENSE)

This integration is for users of Simple WiFi thermostat made by "[TheSimple](https://thesimple.com/)" which is accessed through [ecofactor.com](https://www.ecofactor.com).

<img src="images/s100_black.png" alt="Simple Thermostat Black" width="25%"> <img src="images/s100_white.png" alt="Simple Thermostat White" width="25%">

## Installation via HACS


[![Open your Home Assistant instance and open a repository inside the Home Assistant Community Store.](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?repository=thesimple-thermostat&owner=lsellens)

or
1. In Home Assistant, navigate to [**HACS**](https://www.hacs.xyz/docs/use/download/download/)
2. Search for and **install** `The Simple WiFi Thermostat`

## Manual Installation

1. Using your tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
2. If you do not have a `custom_components` directory (folder) there, you need to create it.
3. In the `custom_components` directory (folder) create a new folder called `simple`.
4. Download _all_ the files from the `custom_components/simple/` directory (folder) in this repository.
5. Place the files you downloaded in the new directory (folder) you created.
6. Restart Home Assistant

## Setup


[![Open your Home Assistant instance and start setting up a new integration.](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=simple)

or
1. Once installed, navigate to **Settings**/**Devices & services**.
2. Click **+ ADD INTEGRATION**
3. Search for "`The Simple WiFi Thermostat`"
4. Enter **UserName**/**Password** for [thesimple.com](https://thesimple.com/)

All thermostats associated with your account should appear in Home Assistant
