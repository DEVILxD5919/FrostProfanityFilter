# FrostProfanityFilter Plugin for PocketMine-MP

## Overview

**FrostProfanityFilter** is a plugin designed for PocketMine-MP that filters out bad words and profanities from the chat. The plugin allows server administrators to configure a list of words that should be blocked, ensuring a cleaner and more respectful chat environment for all players.

## Features

- Blocks predefined bad words and profanities in the chat.
- Allows server administrators to configure and customize the list of blocked words.
- Prevents messages containing bad words from being sent.
- Easy to install and configure.

## Requirements

- PocketMine-MP 5.0.0 or higher.

## Installation

1. Download the FrostProfanityFilter plugin from the [Poggit releases page](https://poggit.pmmp.io/p/FrostProfanityFilter/1.0.0).
2. Place the downloaded `FrostProfanityFilter.phar` file into the `plugins` folder of your PocketMine-MP server.
3. Restart your PocketMine-MP server.

## Configuration

1. After installing the plugin and restarting the server, a configuration file named `config.yml` will be created in the `plugin_data/FrostProfanityFilter` directory.
2. Open the `config.yml` file with a text editor to customize the list of blocked words.
3. Add or remove words from the `blocked-words` list as needed. Each word should be on a new line and enclosed in quotes.

Example `config.yml`:
```yaml
profanities:
  - abortion
  - abuser
  - ahole
  - alabama hotpocket
  - alligatorbait
```

4. Save the `config.yml` file and restart the server for changes to take effect.

## Usage

- The plugin automatically filters and blocks messages containing any words from the `profanities` list.
- Players attempting to send messages with blocked words will receive a notification that their message contains inappropriate language and was not sent.

## Support

For support, bug reports, and feature requests, please Join Our Discord Server the [discord](https://discord.gg/YfcDdK5mSF).
or Email me at [support@frostnetwork.xyz](mailto:support@frostnetwork.xyz)

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](https://github.com/DEVILxD5919/FrostProfanityFilter/blob/main/LICENSE) file for details.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

---

Thank you for using FrostProfanityFilter! We hope it helps maintain a positive and respectful environment on your PocketMine-MP server.
