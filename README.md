# WBar Control Center

WBar is a compact, feature-rich control dashboard designed to interface with custom hardware (WBar Device) and provide essential Windows shortcuts and utilities.

![WBar](logo.png)

## Features

### 🖥️ Display Controls
- **Brightness**: One-click cycle through brightness levels.
- **Rotation**: Quickly rotate your primary display (0° / 90° / 180° / 270°).

### ⌨️ Hardware Integration & Remapping
The dashboard mirrors the physical layout of the WBar hardware device.
- **Mechanical Keys (K1, K2)**: Fully remappable.
- **Touch Keys (T1-T4)**: Supports individual taps or grouped swipe gestures.
  - **Swipe Mode**: Toggle `Swipe T1/T2` or `Swipe T3/T4` to combine two touch keys into a directional swipe controller.
- **Remapping**: Right-click any key (K1, T1, etc.) to configure:
  - **Short Press**: Standard action.
  - **Long Press**: Secondary action.
  - **Actions**: Launch applications, trigger keyboard macros/shortcuts (e.g., `Ctrl+C`).

### 📊 OLED Customization
- **Clock/Date**: Displays current time and date.
- **Visualizer**: Switch to "Alt Display" mode to show visualizers (e.g., Audio Visualizer) or custom GIF/Images on the device screen.

### ⚡ Power Management
- **Wake Timer**: Schedule a PC wake-up time (Once or Daily).
- **Shutdown Timer**: Schedule a Shutdown or Sleep after a set duration (15m - 4h).
- **Control**: Dedicated `Wake` and `Shut` buttons for quick access.

### ℹ️ About
- Accessible via the `?` icon in the title bar.
- Project info and email support.

## Installation & Usage
1. **Launch**: Run `Widget.exe`.
2. **System Tray**: The app minimizes to the system tray. Click the icon to restore.
3. **Hardware Connection**: The app automatically attempts to connect to the WBar device over Serial (COM).

## Requirements
- Windows 10/11
- .NET 8.0 Runtime (packaged with the application)
