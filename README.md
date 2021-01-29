# home-assistant-config

## Integrations not enabled via configuration:

* [Meteorologisk institutt (Met.no)](https://www.home-assistant.io/integrations/met/)
    * weather.*


* [Brother Printer](https://www.home-assistant.io/integrations/brother/)
    * sensor.<printer>_*

  
* [Broadlink](https://www.home-assistant.io/integrations/broadlink/)
    * Devices are configured, but you may rename them within HA since there are no 
      name/friendly_name options defined within the new integration.
      

* Mobile Device Tracking and Sensors
    * Install [App](https://play.google.com/store/apps/details?id=io.homeassistant.companion.android&hl=de&gl=US) on device.
    * Grant app privileges regarding location.
    * Choose sensors to expose within app configuration.
    
* Maxcube
    * Device names configured in hub will be used as climate entity_id.