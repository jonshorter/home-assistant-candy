# Candy Home Assistant component

[![hacs_badge](https://img.shields.io/badge/HACS-Custom-orange.svg)](https://github.com/custom-components/hacs)

Custom component for [Home Assistant](https://homeassistant.io) that integrates Candy/Haier Wi-Fi washing machines (also known as Simply-Fi).

This is still work-in-progress, it only supports washing machines and may not work with all models. Open a PR or issue if you have a model that's not supported.


## Features

- Uses the local API and its status endpoint
- Displays the machine status, wash cycle status, remaining time and some other attributes

## Installation

1. Install [HACS](https://hacs.xyz/)
2. Add this as a custom repository to HACS (`https://github.com/ofalvai/home-assistant-candy`)
3. Go to the integrations list in HACS and install this custom repo
4. Restart Home Assistant
5. Go to the Integrations page, click Add integrations and select Candy
6. Complete the config flow

## Configuration

You need the IP address of the machine and the encryption key. This can be guessed with [CandySimplyFi-tool](https://github.com/MelvinGr/CandySimplyFi-tool).

