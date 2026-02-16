# Climbing Timer

A professional competition timer for climbing events with synchronized multi-display support.

## Features

- ⏱️ **Flexible Timer Modes**: Preparation, climbing, and transition phases with customizable durations
- 📊 **Live Scoring**: Track attempts, tops, and zones in real-time
- 📺 **Multi-Display Sync**: Control the timer from one device and display it on unlimited screens
- 🎨 **Customizable Appearance**: Adjust colors, fonts, sizes, and layouts
- 🔊 **Audio & Voice Announcements**: Countdown beeps and voice announcements
- 📱 **Responsive Design**: Works on phones, tablets, computers, and large displays
- 🏆 **Leaderboard Integration**: Connect to Griptonic for live results
- ⌨️ **Keyboard Shortcuts**: Fast control for competition judges
- 🎬 **Video Overlay Support**: Crop mode for streaming/recording

## Quick Start

1. **Open the timer**: Simply open `index.html` in any modern web browser
2. **Configure settings**: Click the ⚙️ Settings button to adjust timer durations, colors, and features
3. **Start timing**: Press the **Start** button or hit **Space** to begin

## Multi-Display Sync Setup

Control the timer from your main computer while displaying it on TVs, projectors, or other screens:

### On the Controller (Main Computer):

1. Open the timer in your browser
2. Click **"🎮 Create Control Room"** button
3. A 6-character room code will be generated (e.g., `ABC123`)
4. Click the **QR code icon** (📱) in the top-right to share the connection details
5. You'll see a **"🎮 CONTROLLER"** badge indicating this device controls the timer

### On Display Devices (TVs, Tablets, etc.):

**Option A - Scan QR Code:**
- On the display device, scan the QR code shown on the controller
- The display will automatically connect

**Option B - Manual Join:**
1. Open the timer on the display device
2. Click **"📺 Join as Display"**
3. Enter the 6-character room code from the controller
4. You'll see a **"📺 DISPLAY ONLY"** badge

### What Syncs?

When connected, **everything** syncs in real-time from the controller to all displays:
- ✅ Timer state (play, pause, reset)
- ✅ Time remaining and phase changes
- ✅ Scoring (attempts, tops, zones)
- ✅ Climber information
- ✅ Settings and appearance
- ✅ Leaderboard overlays
- ✅ Intermission messages

### Display Behavior

- **Controller**: Full control buttons visible, all settings accessible
- **Displays**: Read-only view, controls hidden, syncs automatically
- **Connection Status**: Both show connected status and number of displays

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Space` | Start / Pause timer |
| `S` | Skip to next phase |
| `R` | Reset timer |
| `M` | Toggle sound |
| `F` | Toggle fullscreen |
| `N` | Next climber from queue |
| `A` | Add attempt (+1) |
| `T` | Add top (+1) |
| `Z` | Add zone (+1) |
| `B` | Next boulder |
| `I` | Start intermission |
| `L` | Toggle leaderboard overlay |
| `↑/↓` | Add/subtract 5 seconds |
| `?` | Show shortcuts |

## Timer Phases

1. **Preparation Phase** (Optional): Climber observes the route
2. **Climbing Phase**: Main climbing time
3. **Transition Phase** (Optional): Rest period between rounds

Configure durations in Settings → Timer tab.

## Customization

Access Settings (⚙️) to customize:
- **Timer**: Phase durations, auto-transitions, round count
- **Display**: Colors, fonts, sizes, clock visibility, scoring display
- **Appearance**: Competition name, category, layout modes
- **Advanced**: Video crop mode, leaderboard settings

## Technology

- Pure HTML/CSS/JavaScript (no build required)
- React 18 (loaded via CDN)
- PeerJS for real-time synchronization
- Works offline after initial load

## Browser Support

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari

## Tips

- Use **fullscreen mode** (F key) on displays for a professional look
- Enable **wake lock** by starting the timer to prevent screen dimming
- For streaming, use **Crop Controls** to position timer in OBS/recording software
- Test your sync setup before competition day
- Keep controller and displays on the same network for best performance

## License

MIT License - feel free to use for your climbing competitions!