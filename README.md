# OmniCore

OmniCore is the ultimate events and commands manager for Omnicraft server.

## Description

OmniCore is a plugin for Pocketmine MP that merges various features into one plugin. It includes the following:

- `/tpall` command: teleports all players to the user who executed the command
- `/timer` command: allows users to manage time on their server, such as adding a timer for a specific duration
- `/coords` command: turns on or off the coordinates indicator
- `InfinitSlotsEvent`: changes the player's slots to infinite, allowing them to get infinite slots on the server. Note that adding a large user limit is recommended as slots are visual only.
- `AutoInvEvent`: gives players the items they mined or gathered, along with any experience points.
- `KeepInvEvent`: ensures players don't lose their inventory or experience points upon death.

## Files/Folders

- `resources/Config.yml`: stores plugin configuration settings
- `src/OmniCore/command/TPALLCommand.php`: contains the `TPALLCommand` class that handles the `/tpall` command
- `src/OmniCore/command/TimerCommand.php`: contains the `TimerCommand` class that handles the `/timer` command
- `src/OmniCore/command/CoordinateCommand.php`: contains the `CoordinateCommand` class that handles the `/coords` command
- `src/OmniCore/events/InfinitSlotsEvent.php`: contains the `InfinitSlotsEvent` class that handles the infinite slots event
- `src/OmniCore/events/AutoInvEvent.php`: contains the `AutoInvEvent` class that handles the auto inventory event
- `src/OmniCore/events/KeepInvEvent.php`: contains the `KeepInvEvent` class that handles the keep inventory event
- `src/OmniCore/utils/Configuration.php`: contains the `Configuration` class that manages the plugin's configuration settings
- `src/OmniCore/OmniCoreManager.php`: contains the `OmniCoreManager` class that manages the plugin's commands and events
- `src/OmniCore/OCCore.php`: contains the `OCCore` class that serves as the plugin's core

Note that the files `TPALLCommand.php`, `TimerCommand.php`, `CoordinateCommand.php`, `InfinitSlotsEvent.php`, `AutoInvEvent.php`, and `KeepInvEvent.php` contain the string `#TODO` as an example code. You may modify or remove this code as needed.

## Installation *Unavailable..

1. Download the latest release of OmniCore from the [releases page](https://github.com/yourusername/OmniCore/releases).
2. Upload the downloaded `.phar` file to your Pocketmine MP server's `plugins` folder.
3. Restart your server.

## Usage

Once installed, users can execute the `/tpall`, `/timer`, and `/coords` commands. The events `InfinitSlotsEvent`, `AutoInvEvent`, and `KeepInvEvent` will automatically trigger when certain conditions are met.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
