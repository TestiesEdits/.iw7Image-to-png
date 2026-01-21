# 7Imagexpng (IW7 Image Converter)

A powerful tool for converting images between **Call of Duty: Infinite Warfare (.iw7Image)** format and standard **PNG** files.

## Features
- **Convert PNG to IW7**: Import your custom images into the game format.
- **Convert IW7 to PNG**: Extract game images to PNG for editing.
- **Automatic Template Handling**: 
  - Uses an embedded header template (based on `aar_deaths_icon.iw7Image`) so you don't need any external files.
  - Can also use existing `.iw7Image` files in the folder as templates if available.
- **BC7 Support**: Automatically detects BC7 formatted images and exports them as `.dds` for external conversion.
- **Batch Processing**: Scans the selected folder and processes all matching files.
- **Modern UI**: Built with CustomTkinter for a clean, dark-mode friendly interface.

## How to Use
1. Run `7Imagexpng.exe`.
2. Select the folder containing your images.
3. Click **PNG > IW7** to convert all PNG files in the folder to IW7 format.
4. Click **IW7 > PNG** to convert all IW7 files in the folder to PNG format.

## Requirements
- Windows 10/11
- No external dependencies required (standalone executable).

## Credits
Tool created for the Infinite Warfare modding community.
