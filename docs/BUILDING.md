# Building AUTOPULSE on Windows

This guide describes the intended Windows build process. The exact commands depend on the source files included in the repository.

## Requirements

- Windows 10 or Windows 11
- Python (use the version supported by the project dependencies)
- PyInstaller
- Inno Setup 6 (for the Setup Wizard)

## Build the application

1. Clone or download the repository.
2. Open the project folder.
3. Install the Python packages listed in the project's requirements file, if provided.
4. Run the project's Windows build script.
5. Check the `dist` folder for the packaged application.

## Build the Setup Wizard

1. Install Inno Setup 6.
2. Open the AUTOPULSE installer `.iss` script in Inno Setup.
3. Compile the script.
4. Find the generated installer in the configured output folder.

The final installer should be named `AUTOPULSE-Setup.exe`.

## Important

The application source, icon, build script, and Inno Setup script must be present before these steps can produce a working build. The GitHub Releases page should contain only installer files that have actually been built and tested.
