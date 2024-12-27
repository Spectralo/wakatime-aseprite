![image](https://github.com/user-attachments/assets/91b614e6-9e19-4d31-a38d-603608e3034e)

# Wakatime-Aseprite

A simple Aseprite plugin to track your time in Wakatime.
This implementation is basic (Don't hesitate to contribute!) and thus doesn't do a few things you'd expect from an official wakatime-plugin:
- It doesn't automatically download and update your wakatime-cli (Another editor will probably do this for you, I hope at least)
- Doesn't ask you to add your api key (You can add it manually in your .wakatime.cfg)

## Installation

1. Download the latest release from the [releases page](https://github.com/spectralo/hackatime-aseprite/releases)
2. Open Aseprite
3. Go to settings (Ctrl+, or Cmd+,)
4. Go to extensions
5. Click on "Add extension"
6. Select the downloaded file
8. Enjoy!

## Usage

The plugin should automatically start tracking your time after you installed it.

## Building

You don't really build an aseprite plugin, you just need to zip the whole folder and rename the extension to `.aseprite-extension`.
Step-by step:

1. Clone the repo
2. Cd into the repo
    ```bash
    cd wakatime-Aseprite
    ```
2. Zip & rename the folder:
    ```bash
    zip -r wakatime-aseprite.aseprite-extension src
    ```

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
