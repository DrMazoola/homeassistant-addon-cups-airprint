# homeassistant addon cups airprint, forked and modified by DrMazoola
## Modifications:
* Added Canon MF8380cdw drivers and requried packages for amd64. (Hacky, did not build out file path options for other processors.)   
* Added localization to get US standard papaer sizes (ex. letter & legal) to show up in AirPrint (it defaulted to A4 & A5)
* CUPs Admin page at <home_assistant_ip>:631

Many thanks to Zajac!

Original Text...

# homeassistant addon cups airprint
CUPS addon with working Avahi in reflector mode 

Tested with Home Assistant version **2025.2.3**

CUPS administrator login: **print**, password: **print** (can be changed in the Dockerfile)

Configuration data is stored in **/addon_configs/<slug>_cups** folder

[![Open your Home Assistant instance and show the add add-on repository dialog with a specific repository URL pre-filled.](https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg)](https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A%2F%2Fgithub.com%2Fzajac-grzegorz%2Fhomeassistant-addon-cups-airprint)
