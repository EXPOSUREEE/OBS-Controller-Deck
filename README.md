# OBS-Controller-Deck

OBS Controller Deck -

A customizable stream deck alternative for OBS Studio with web-based controls, perfect for streamers and content creators.

Features:

🎚️ Scene switching with customizable buttons

🔊 Audio control for mic and desktop audio

🔴 Stream start/stop controls

⏺️ Recording start/stop controls

🌐 Web-based interface accessible from any device

🔄 Automatic update checks

🎨 Modern, responsive UI

Prerequisites:

OBS Studio installed

OBS WebSocket plugin (v5.x or newer)

Node.js v16+ (included in the executable version)

Installation:
Just Run OBS-Controller-Deck Setup.exe



Open OBS Studio

Go to Tools > WebSocket Server Settings

Enable WebSocket server (default port: 4455)

Set a password if desired

Controller Deck:

Launch the application

Access the interface at http://localhost:3000

Select your preferred scenes from the initial setup

Usage -
Scene Controls:

Click any scene button to switch instantly

Re-select scenes anytime using the "Re-select Scenes" button

Audio Controls:

Click the microphone/audio icons to mute/unmute

Use sliders to adjust volume levels

Stream/Recording Controls:

Start/Stop streaming with dedicated buttons

Start/Stop recording with one click

# Output will be in the dist/ folder

Troubleshooting
Issue	Solution
Can't connect to OBS	Verify WebSocket server is running in OBS
Buttons not working	Check OBS logs for WebSocket errors
Blank screen	Ensure you're accessing http://localhost:3000
Missing scenes	Re-select scenes from the configuration panel
Release Notes
v1.0.0 - Initial Release
Basic scene switching functionality

Audio controls for mic and desktop audio

Stream/recording controls

Automatic update checking

Roadmap:

Add customizable hotkeys

Support for multiple OBS instances

Mobile app version

Plugin system for additional functionality
