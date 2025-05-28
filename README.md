# The Simple WiFi Thermostat Home Assistant integration.
[![](https://img.shields.io/github/release/lsellens/simple/all.svg?style=for-the-badge)](https://github.com/lsellens/simple/releases)
[![](https://img.shields.io/github/license/lsellens/simple?style=for-the-badge)](LICENSE)
[![](https://img.shields.io/badge/MAINTAINER-%40lsellens-red?style=for-the-badge)](https://github.com/lsellens)

This integration is for users of Simple WiFi thermostat made by "[TheSimple](https://thesimple.com/)" which is accessed through [ecofactor.com](https://www.ecofactor.com).

![Simple Thermostat White](images/s100_white.png)

The interface for this thermostat looks like:

![Example of simple Thermostat interface](images/interface-example.png)

## Installation via HACS

1. In Home Assistant, navigate to [**HACS**](https://www.hacs.xyz/docs/use/download/download/).
2. Click the three dots in the top right corner and select **Custom repositories**.
3. Enter the repository URL: `https://github.com/lsellens/simple` and select **Integration** as the category.
4. Click **Add**.
5. The integration will now be available for installation in HACS.

## Manual Installation

1. Using your tool of choice open the directory (folder) for your HA configuration (where you find `configuration.yaml`).
2. If you do not have a `custom_components` directory (folder) there, you need to create it.
3. In the `custom_components` directory (folder) create a new folder called `simple`.
4. Download _all_ the files from the `custom_components/simple/` directory (folder) in this repository.
5. Place the files you downloaded in the new directory (folder) you created.
6. Restart Home Assistant

## Limitations

1. Supports multiple thermostats but only a single location.
