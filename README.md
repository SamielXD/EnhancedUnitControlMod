# Enhanced Unit Control

A Mindustry mod that lets you give tactical commands to your units.

## What it does

Tap any friendly unit and give it commands like patrol, guard, attack move, follow, and more. Your units will actually listen and do useful things instead of wandering around randomly.

## Features

- **11 different commands** including patrol, guard, attack move, follow, hold, circle, retreat, formation, assist, auto mine, and kamikaze
- **Mobile optimized** with touch-friendly UI
- **Command persistence** - orders stay active even when UI is disabled
- **Smart AI** - units still fight enemies and avoid obstacles while following commands
- **Control up to 50 units** at once
- **Customizable distances** for most commands
- **Auto-cleanup** of dead/invalid units

## Installation

1. Download the latest release from [Releases](https://github.com/SamielXD/UnitControlMod/releases)
2. Place the `.zip` file in your Mindustry `mods` folder
3. Restart Mindustry
4. Enable the mod in the mods menu

## How to Use

1. Tap any friendly unit
2. A command menu appears
3. Select a command
4. The unit executes it

That's it!

## Commands

### Basic Commands

- **🔄 Patrol** - Unit patrols back and forth (50-600 tiles)
- **🛡️ Guard** - Guards a position and attacks nearby enemies (220 tile range)
- **⚔️ Attack Move** - Advances while attacking hostiles (100-700 tiles)
- **👤 Follow** - Follows your player unit (65 tile distance)
- **⏸️ Hold** - Stays in position with minimal movement

### Advanced Commands

- **⭕ Circle** - Moves in circles around a point (30-300 tile radius)
- **🏃 Retreat** - Runs away from danger (250 tiles)
- **📐 Formation** - Follows in organized formation (50 tile spacing)
- **🤝 Assist** - Helps the nearest ally unit (350 tile range)
- **⛏️ Auto Mine** - Automatically mines resources (requires mining unit)
- **💥 Kamikaze** - Suicide attack on nearest enemy (one-time use)
- **❌ Stop** - Cancels all commands

## Settings

Access settings through: **Settings → Unit Control**

- **UI Popup Control** - Enable/disable command dialogs (commands still work when off)
- **Debug Mode** - Shows extra info in console for troubleshooting
- **Command Guide** - View all commands and their details
- **Status Info** - See active commands and unit breakdown
- **Clear All Commands** - Remove all active commands from units

## Requirements

- Mindustry v153 or higher
- No dependencies required

## Known Issues

- Units might occasionally get stuck on complex terrain
- Mining command doesn't work perfectly with all ore types
- Formation spacing looks odd with very large units
- Rapid tapping can cause UI glitches

## Compatibility

Works with:
- ✅ Mobile (Android/iOS)
- ✅ Desktop (Windows/Mac/Linux)
- ✅ Campaign mode
- ✅ Custom maps
- ✅ Multiplayer (client-side only)

## Development

Want to contribute or report bugs?

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Changelog

### v1.0 (Initial Release)
- 11 unit commands
- Mobile-optimized UI
- Command persistence system
- Settings menu integration
- Auto-cleanup system
- Support for up to 50 units

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support

If you encounter bugs or have suggestions:
- Open an issue on [GitHub](https://github.com/SamielXD/UnitControlMod/issues)
- Contact me on Discord: smaielkun

---

If you enjoy the mod, a star would mean a lot to me! 🌟
