# Escea Fireplace HASS integration

![Lint](https://github.com/funtastix/escea/workflows/Lint/badge.svg) ![Pylint](https://github.com/funtastix/escea/workflows/Pylint/badge.svg)

## :information_source: [Original Source](https://github.com/lazdavila/core/tree/escea_integration/homeassistant/components/escea)

This code was converted into a custom component from a pull request for a core component which is currently still in review and not moving forward so far.

## :blue_heart: Thanks

Thank you [@lazdavila](https://github.com/lazdavila) for building this!

## :flight_departure: Dependencies

This component has a dependency on `pescea` which will be installed automatically by Home Assistant.

## Installation

1. Logon to your HA or HASS with SSH
2. Go to the HA 'custom_components' directory within the HA installation path (The directory is in the folder where the 'configuration.yaml' file is located. If this is not available - create this directory).
3. Run `cd custom_components`
4. Run `git clone https://github.com/funtastix/escea` within the `custom_components` directory
5. Restart your HA/HASS service in the UI with `<your-URL>/config/server_control`
8. Add your fireplace either by: HA UI by navigating to "Integrations" -> "Add Integration" -> "Escea" (If it is not available, clear your web browser cache to renew the integrations list.)