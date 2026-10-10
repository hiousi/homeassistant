# Home Assistant Blueprints

This repository contains blueprints for automating tasks in [Home Assistant](https://www.home-assistant.io/). Blueprints are reusable automation templates that simplify the process of creating and sharing automations.

## Automation Blueprints

### Moes/Tuya TS0044 – Event Entity

A blueprint for the Moes/Tuya TS0044 four-button scene switch using the Home Assistant event entity exposed by Zigbee2MQTT. Supports single, double and hold actions for all four buttons, including compatibility with the previous event format.

[![Open your Home Assistant instance and import the blueprint](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhiousi%2Fhomeassistant%2Fblob%2F059505c77699748416ef63232ee76efb267a1a68%2Fblueprints%2Fautomation%2Fwall_remote_ts0044.yaml)

[View source](blueprints/automation/wall_remote_ts0044.yaml)

## Script Blueprints

### Scene Toggle

Toggle between off and on states using scenes. Repeated executions cycle through the configured scenes in order, remembering the last activated scene. After the reset time, the script toggles between off and the last active scene.

Based on [Simple Scene Toggle](https://community.home-assistant.io/t/simple-scene-toggle) by panhans.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fmy.home-assistant.io%2Fredirect%2Fscripts%2F)


[View source](blueprints/script/scene_toggle.yaml)

### Step Dimmer

Cycle through configurable brightness levels for one or more lights. Repeated executions step through the brightness values; after the reset time, the script toggles between off and the first brightness step.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fhiousi%2Fhomeassistant%2Fblob%2Fmain%2Fblueprints%2Fscript%2Fstep_dimmer.yaml)

[View source](blueprints/script/step_dimmer.yaml)

## License

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the blueprints.
