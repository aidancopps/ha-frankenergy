# Frank Energy integration for Home Assistant

View your energy usage from Frank Energy (NZ) in Home Assistant.

## Data

Imports the last four days of hourly energy data & costs from Frank Energy.

![Energy Usage PNG](/homeassistant-energy-graph.png "Energy Dashboard Reporting")

## Getting started

You will need to have an existing Frank Energy account.

## Installation

Once installed, simply set-up from the `Devices and services` area.
The first field is the username and the next field is the password for your Frank Energy account.

Add "energy_consumption_daily" into Energy Dashboard for energy reporting.
Then choose "Use an entity tracking the total costs" and select "frankenergy.energy_cost_daily" to add the cost statistic.

### Manually

Copy all files in the *custom_components/frankenergy* folder to your Home Assistant folder */config/custom_components/frankenergy*.

## Known issues

None

## Acknowledgements

This integration is not supported / endorsed by, nor affiliated with, Frank Energy.
