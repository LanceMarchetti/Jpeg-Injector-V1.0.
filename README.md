# Jpeg-Injector-V1.0 (2025 - in development)
An unconventional Steganographic tool created for Jpeg text embedding. A nostalgic Windows 95-themed version sets the mood.
 [Demo Available:](https://lancemarchetti.github.io/Jpeg-Injector-V1.0./Jpeg-Injector-V1.0.html)

## Features

- Complete Windows 95 UI including:
  - Classic teal desktop background pattern
  - Authentic Windows 95 window styling with 3D borders
  - Start button and taskbar with working clock
  - Desktop icon and window controls
  - Classic Windows 95 error dialog boxes with sound
  - Draggable windows
  - MS Sans Serif and Fixedsys fonts
  - Authentic Windows 95 sound effects
  - Custom sound support for the "Start Over" button
  - Fully functional form-based "Start Over" button that completely resets the page

- Original Jpeg-Injector functionality with enhancements:
  - Drag & drop or browse to select JPEG files
  - Insert text at any byte position in the JPEG file
  - Modify images without corrupting them
  - Download button for saving the modified image (appends '_modified.jpg' to original filename)

## Usage

1. Click on the desktop icon to open the application
2. Drag and drop a JPEG file onto the drop area or click to browse
3. Enter the text you want to inject
4. Use the slider or input box to set the byte position
5. Click "Insert" to inject your text
6. The modified image will appear at the bottom of the window
7. Click "Download Modified Image" to save the result (uses original filename with '_modified.jpg' appended)
8. If no image is generated, then you have chosen an invalid byte position for insertion.

## Customizing Sounds

The application includes Windows 95 sound effects for various actions:
- Error dialogs play the classic Windows 95 error sound
- The "Insert" button plays a success sound
- The "Start Over" button is prepared to play your custom sound

To replace the "Start Over" sound with your own:
1. Open the `Jpeg-Injector-V1.0-Win95.html` file in a text editor
2. Locate the Sound Effects section (search for "Sound Effects")
3. Replace the `BASE64` with your base64-encoded WAV sound data

## Files

- `Jpeg-Injector-V1.0-Win95.html` - The Windows 95 themed application
- `win95_logo.png` - Windows 95 logo icon
- `win95_error.png` - Windows 95 error dialog image
- `audio` - sound effects
- `images` - Windows 95 logos % icons


## Credits

- Original Jpeg-Injector by Complex_Echo_5845
- Windows 95 theme implementation using CSS and JavaScript
- Fonts from [95-font](https://unpkg.com/95-font/) and [fixedsys-css](https://unpkg.com/fixedsys-css/)
