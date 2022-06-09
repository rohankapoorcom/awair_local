# Awair Local
![Project Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitHub Actions][actions-shield]][actions]
[![GitHub Activity][commits-shield]][commits]
[![GitHub Last Commit][last-commit-shield]][commits]


The Awair Local integration allows for pulling sensor data from an Awair Sensor that supports the [Local API](https://support.getawair.com/hc/en-us/articles/360049221014-Awair-Element-Local-API-Feature#h_01F40FK1R9A5GJ86Z3N6PGWCWS) into Home Assistant.

# Installation

The easiest way to install is through HACS. The Awair Local integration is **not** included in the HACS default repositories so it will have to be added manually.

1. In Home Assistant, select HACS -> Integrations -> Custom repositories. Add `https://github.com/rohankapoorcom/awair_local` in the `Integration` category.
2. In Home Assistant, select HACS -> Integrations -> + Explore and Download Repositories. Search for Awair Local in the list and add it.
3. Restart Home Assistant
4. Set up and configure the integration: [![Add Integration](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start/?domain=awair_local)

You will need your sensor's IP address / Hostname to set up the integration.

## Manual Installation

Copy the `custom_components/awair_local` directory to your `custom_components` folder. Restart Home Assistant, and add the integration from the integrations page.

# Contributing
Contributions are welcome! Please open a Pull Request with your changes.

***

[commits-shield]: https://img.shields.io/github/commit-activity/y/rohankapoorcom/awair_local.svg
[commits]: https://github.com/rohankapoorcom/awair_local/commits/master
[actions-shield]: https://github.com/rohankapoorcom/awair_local/actions/workflows/push.yml/badge.svg
[actions]: https://github.com/rohankapoorcom/awair_local/actions
[home-assistant]: https://home-assistant.io
[issue]: https://github.com/rohankapoorcom/awair_local/issues
[license-shield]: https://img.shields.io/github/license/rohankapoorcom/awair_local.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2022.svg
[last-commit-shield]: https://img.shields.io/github/last-commit/rohankapoorcom/awair_local.svg
