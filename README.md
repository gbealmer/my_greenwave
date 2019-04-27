# my_greenwave
Updated home assistant custom component for TCP Connected hub/light bulbs
GreenwaveLighting
Greenwave Lighting for Home Assistant.

This is a lighting component for the popular Home Assistant home automation software

Copy directory and contents of custom_components/my_greenwave/ to homeassistant config directory

add this to your configuration.yaml:

light:
  - platform: my_greenwave
    host: XXX.XXX.XXX.XXX
    version: 3
The version option is the major revision of your firmware, which should be 2 or 3. If you are running Version 2, there are no extra steps. If you are running Version 3, you must press the Sync button on the gateway prior to the first launch of Home Assistant, so a token can be grabbed. Once home assistant has started, you can either press the Sync button again or wait for it to time out manually.
