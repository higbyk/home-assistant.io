---
title: SwitchBee
description: Instructions for how to integrate SwitchBee accessories within Home Assistant.
ha_category:
  - Button
  - Light
  - Switch
ha_release: '2022.10'
ha_iot_class: Local Polling
ha_config_flow: true
ha_codeowners:
  - '@jafar-atili'
ha_domain: switchbee
ha_platforms:
  - button
  - light
  - switch
ha_integration_type: integration
---

[SwitchBee](https://www.switchbee.com), is an innovation company making smart homes more accessible and affordable to any household environment.

There is currently support for the following device types:

- Switch 
- Timed Power Switch (Boiler)
- Group Switch
- Timed Switch
- Light (Dimmer)
- Scenario

Supported devices will be discovered after the SwitchBee integration is configured.

{% include integrations/config_flow.md %}
