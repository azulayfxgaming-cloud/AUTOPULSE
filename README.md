# ⚡ AUTOPULSE

**A futuristic Windows automation app with a neon-purple interface.**

AUTOPULSE can open a selected file, application, or website automatically using a countdown timer or a scheduled clock time. It also includes experimental Fortnite match-finished detection.

> **Project status:** Windows project. The Fortnite log-detection feature is experimental and may need configuration for different Fortnite versions.

## Features

- ⏱️ Countdown timer with minutes and seconds
- 🕒 Schedule an action for a specific time
- 📁 Browse and select a file or application
- 🌐 Open websites automatically
- 🎮 Experimental Fortnite match-finished detection
- 💜 Dark, neon-purple user interface
- 🧙 Windows Setup Wizard with an option to launch AUTOPULSE after installation

## Getting started

### Download

When a Windows installer is published, download **AUTOPULSE-Setup.exe** from the [AUTOPULSE VERSIONS]([(https://www.mediafire.com/file/wqi31bpyfqijyop/AUTOPULSE.exe/file)]).

### Build from source

1. Install Python and the project dependencies.
2. Download or clone this repository.
3. Run the Windows build script included with the source project.
4. To create the Setup Wizard, install **Inno Setup 6** and compile the included `.iss` installer script.

See [BUILDING.md](docs/BUILDING.md) for more details.

## Project structure

```text
AUTOPULSE/
├── assets/          # App icon and artwork
├── docs/            # Build and project documentation
├── src/             # Application source code
├── installer/       # Windows installer configuration
├── README.md
└── LICENSE
```

*The folders will be populated as the corresponding source files are added.*

## Notes

- AUTOPULSE is intended for Windows.
- Fortnite match detection is experimental and is not guaranteed to detect every match.
- Windows may display a security warning for an unsigned installer. Only download builds from a source you trust.

## License

No license has been added yet. Until a license is included, the repository's code is not automatically granted permission for reuse or redistribution.
