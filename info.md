# Home Assistant Electrolux Care Integration (Not Official - Community Integration)

[![Validate with HACS](https://github.com/andersdreyer/homeassistant_electrolux/.github/workflows/hacs.yml/badge.svg)](https://github.com/andersdreyer/homeassistant_electrolux/.github/workflows/hacs.yml)
[![Validate with hassfest](https://github.com/andersdreyer/homeassistant_electrolux/.github/workflows/hassfest.yml/badge.svg)](https://github.com/andersdreyer/homeassistant_electrolux/.github/workflows/hassfest.yml)


## ⚠️ PLEASE NOTE: 
This is a fork of the original integration made by Mauro Midolo. The original integration was taken down due to fear of financial repercussions.

## Details
This is an integration to Home Assistant to communicate with the Electrolux Connectivity Platform (ECP), Electrolux owned brands, like: Electrolux, AEG, Frigidaire, Husqvarna.

Tested with Electrolux and AEG washer-dryer, but probably could be used with some internet connected ovens, diswashers, fridges, airconditioners.

### Supported and tested devices

- ELECTROLUX EDH803BEWA - UltimateCare 800
- ELECTROLUX EW9H283BY - PerfectCare 900
- ELECTROLUX EWF1041ZDWA - UltimateCare 900 AutoDose
- ELECTROLUX EEM69410W - MaxiFlex 700
- ELECTROLUX EOD6P77WZ - SteamBake 600
- ELECTROLUX KODDP77WX - SteamBake 600
- ELECTROLUX EHE6799SA - 609L UltimateTaste 900
- ELECTROLUX EW9H869E9 - PerfectCare 900 Dryer
- ELECTROLUX EW9H188SPC - PerfectCare 900 Dryer
- ELECTROLUX EW8F8669Q8 - PerfectCare 800 Washer
- ELECTROLUX EW9F149SP - PerfectCare 900 Washer
- ELECTROLUX KEGB9300W - Dishwasher
- ELECTROLUX EEG69410W - Dishwasher 
- AEG L6FBG841CA - 6000 Series Autodose
- AEG L7FENQ96 - 7000 Series ProSteam Autodose
- AEG L7FBE941Q - 7000 Series Prosense Autodose
- AEG L8FEC96QS - 8000 Series Ökomix Autodose
- AEG L9WBA61BC - 9000 Series ÖKOKombi DualSense SensiDry
- AEG BPE558370M - SteamBake 6000
- AEG FSE76738P - 7000 GlassCare

## Prerequisites
All devices need configured and Alias set (otherwise the home assistant integration raises the authentication error) into following applications (depends on device type and region):
- My Electrolux Care/My AEG Care (EMEA region)
- Electrolux Kitchen/AEG Kitchen (EMEA region)
- Electrolux Life (APAC region)
- Electrolux Home+ (LATAM region)
- Electrolux Oven/Frigidaire 2.0 (NA region)

## Installation
1. Click install.
2. In the HA UI go to "Configuration" -> "Integrations" click "+" and search for "Electrolux status".
3. Insert the Electrolux Care Application credentials

## Disclaimer
This Home Assistant integration was not made by Electrolux. It is not official, not developed, and not supported by Electrolux.

[hacs]: https://hacs.xyz
[releases]: https://github.com/andersdreyer/homeassistant_electrolux/releases
[releases-shield]: https://img.shields.io/github/v/release/andersdreyer/homeassistant_electrolux?style=for-the-badge
[license-shield]: https://img.shields.io/github/license/andersdreyer/homeassistant_electrolux.svg?style=for-the-badge
[hacsbadge]: https://img.shields.io/badge/HACS-Custom-orange.svg?style=for-the-badge
[maintenance-shield]:   badge/maintainer-%40andersdreyer-blue.svg?style=for-the-badge
[user_profile]: https://github.com/andersdreyer


