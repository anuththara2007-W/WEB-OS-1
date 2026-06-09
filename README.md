# AstraOS — Web-Based Desktop Operating System

AstraOS is a browser-based operating system simulation inspired by macOS. It runs entirely in the web environment and provides a fully interactive desktop experience with windows, applications, persistent state, and system-like behavior.

Built by **Anuththara Wickramasekara**  
GitHub: https://github.com/anuththara2007-W
Demo: https://astraoperatingsystem.netlify.app/


---

## Overview

AstraOS simulates a modern desktop operating system inside the browser. It includes draggable windows, a dock-based application launcher, system UI elements, and modular applications such as a terminal, calculator, browser, and file manager.

The goal is to replicate real OS-like interaction patterns using web technologies while maintaining performance and modular architecture.

---

## Features

### Desktop Environment
- Draggable desktop icons and folders
- Persistent icon positioning using localStorage
- Smooth hover animations and UI transitions
- macOS-style dock system with app launching

### Window Management System
- Draggable application windows
- Centered window launching
- Minimize, maximize, and close controls
- Z-index focus system
- Smooth open/close animations

### System UI
- Top menu bar with clock display
- System indicators (battery, network simulation)
- Lock screen with unlock interactions
- Sleep, restart, and shutdown simulation

### Applications
- Terminal (command-line simulation with system commands)
- Calculator (fully functional arithmetic engine)
- Notes (persistent text storage)
- File Manager (basic virtual file system)
- Photos (image gallery with upload support)
- Music Player (audio playback with playlist support)
- Browser (internal navigation + simulated pages fallback)
- App Store (install/uninstall simulation system)
- Settings (system configuration panel)

### Persistence
- Uses localStorage for:
  - App data
  - Desktop layout
  - Settings
  - Installed applications

### Multimedia
- Image upload and gallery system
- Audio playback support (MP3, WAV, OGG)
- Wallpaper customization (image-based)

---

## Tech Stack

- HTML5
- CSS3 (custom UI system)
- Vanilla JavaScript
- localStorage API
- Web APIs (Battery, Network, Geolocation where applicable)

---

## System Behavior

AstraOS behaves like a lightweight operating system inside the browser:

- Apps open in centered windows
- Only one active focus window at a time (z-index management)
- UI state persists across refresh
- System interactions mimic desktop OS workflows

---

## Project Structure (Example)
