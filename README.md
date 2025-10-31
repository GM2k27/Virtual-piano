# Virtual Piano

A web-based virtual piano simulator that allows users to play piano notes using mouse clicks or keyboard inputs. Experience the joy of playing music with realistic sound effects and an intuitive interface.

## Features

- **Interactive Piano Keys**: 12 piano keys (7 white, 5 black) arranged in a standard piano layout.
- **Mouse and Keyboard Support**: Play notes by clicking keys with the mouse or pressing corresponding keyboard keys.
- **Volume Control**: Adjustable volume slider to control the sound level.
- **Visual Feedback**: Keys change appearance when pressed or hovered over for better user experience.
- **Realistic Sounds**: High-quality audio samples for authentic piano sound.
- **Responsive Design**: Centered layout that works on different screen sizes.

## Controls

### Mouse Controls
- Click on any piano key to play the corresponding note.

### Keyboard Controls
- **a**: C note
- **v**: C# note
- **b**: D note
- **w**: D# note
- **c**: E note
- **x**: F note
- **d**: F# note
- **f**: G note
- **y**: G# note
- **g**: A note
- **z**: A# note
- **e**: B note

### Volume Control
- Use the volume slider to adjust the sound level from 0% to 100%.

## Technologies Used

- **HTML5**: Structure of the piano interface.
- **CSS3**: Styling for piano keys, layout, and visual effects.
- **JavaScript**: Logic for sound playback, event handling, and volume control.
- **Web Audio API**: For playing audio files in the browser.

## How to Run

1. Clone or download the project files.
2. Open `piano.html` in a web browser.
3. Start playing by clicking the keys or using keyboard shortcuts!

No additional setup or server is required.

## File Structure

```
3virtual_piano/
├── piano.html       # Main HTML file
├── piano.css        # Stylesheet
├── piano.js         # JavaScript logic
├── sounds/          # Audio files
│   ├── piano-c_C#_major.wav
│   ├── piano-d_D_major.wav
│   ├── piano-e_E_major.wav
│   ├── piano-g_G_major.wav
│   ├── piano-g_G#_major.wav
│   └── piano-g-6200.mp3
└── README.md        # This file
```

## Browser Compatibility

- Chrome (recommended for best audio support)
- Firefox
- Safari
- Edge

## Notes

- Audio files are in WAV and MP3 formats for broad compatibility.
- The piano layout follows a simplified 12-key pattern.
- Volume control affects all played notes.
- Clicking the title changes its color temporarily as a fun Easter egg.

Enjoy creating music with this virtual piano!
