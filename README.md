## blueprints

1. IKEA STYRBAR (E2001/E2002) Controller
- ZHA
- deCONZ
- Zigbee2MQTT  

Controller automation for executing any kind of action triggered by the provided IKEA E2001/E2002 STYRBAR Remote control. Allows to optionally loop an action on a button long press.


> 📕 Full documentation regarding this blueprint is available [here](https://epmatt.github.io/awesome-ha-blueprints/docs/blueprints/controllers/ikea_e2001_e2002).  
> 🚀 This blueprint is part of the **[Awesome HA Blueprints](https://epmatt.github.io/awesome-ha-blueprints) project**.


Changelog:  
+added support for Z2M Direct Triggers (direct MQTT topic integration)  
~changed regex for `trigger_delta` and `last_controller_event` (double press fix)  
-removed condition to check for the last value in the `input_text` helper (release hook fix)
