<!-- LTeX: enabled=false -->
# atop
<!-- LTeX: enabled=true -->
![Download count](https://img.shields.io/github/downloads/chrisgrieser/alfred-atop/total?label=Total%20Downloads&style=plastic)
![Latest release](https://img.shields.io/github/v/release/chrisgrieser/alfred-atop?label=Latest%20Release&style=plastic)

System Monitoring and Process Management via Alfred.

<img alt="atop overview showcase" width="70%" src="https://github.com/chrisgrieser/alfred-atop/assets/73286100/688059a7-7878-4928-9164-ee6f8eb43381">

## Features
- Process Management: CPU & Memory, kill processes, restart apps
- Bluetooth Devices: Battery Information (if available), Connection
- Network Connections
- Removable Volumes
- Uptime & Reboots
- Speed-test
- DNS Switching
- Live refreshing

## Installation
[➡️ Download the latest release.](https://github.com/chrisgrieser/alfred-atop/releases/latest)

## Usage
List all available tools via `atop` and select one. Alternatively, you can also
directly access the more frequently used tools via a configurable keyword.

<img width="60%" alt="showcase overview" src="https://github.com/alfredapp/gallery-edits/assets/73286100/0ee2329e-45f8-4364-af47-70c06690932f">

### Process Management
<img width="60%" alt="showcase processes" src="https://github.com/alfredapp/gallery-edits/assets/73286100/70304f1f-2856-4329-8d69-65c179bb3378">

Display processes directly via `top`. Append "parent" to the query to display
only processes that have child processes.
- <kbd>⏎</kbd>: Kill the process. 
- <kbd>⌘</kbd><kbd>⏎</kbd>: Force kill the process. 
- <kbd>⌃</kbd><kbd>⏎</kbd>: Kill all processes with the same name. 
- <kbd>⇧</kbd><kbd>⏎</kbd>: If the process belongs to a regular app, restart the
  app. 
- <kbd>⌥</kbd><kbd>⏎</kbd>: Copy the Process Identifier (PID).

### Bluetooth Devices
<img width="60%" alt="showcase Bluetooth Devices" src="https://github.com/alfredapp/gallery-edits/assets/73286100/823a6e8d-0d89-43fe-bde7-20547841ca27">

Display paired Bluetooth devices directly via `blue`. 
- <kbd>⏎</kbd>: If `blueutil` is installed, toggle the connection state.
  Otherwise, open the Bluetooth preferences. 
- <kbd>⌥</kbd><kbd>⏎</kbd>: Copy the device address. 

### Removable Volumes
<img width="60%" alt="showcase  Ejectable Volumes" src="https://github.com/alfredapp/gallery-edits/assets/73286100/8b115799-d02d-4116-8b4b-520db63ba454">

Display mounted volumes directly via `vol`. 
- <kbd>⏎</kbd>: Open the Volume in Finder. 
- <kbd>⌘</kbd><kbd>⏎</kbd>: Browse the Volume in the Terminal, [using the
  Terminal app you have configured in your Alfred
  preferences](https://www.alfredapp.com/help/features/terminal/).  
- <kbd>⌃</kbd><kbd>⏎</kbd>: Eject the Volume. 

### DNS Switching
<img width="60%" alt="showcase DNS Switching" src="https://github.com/chrisgrieser/alfred-atop/assets/73286100/b4ba04bc-4f30-4e09-8eb9-081af24d6f84">

## Credits
<!-- vale Google.FirstPerson = NO -->
In my day job, I am a sociologist studying the social mechanisms underlying the
digital economy. For my PhD project, I investigate the governance of the app
economy and how software ecosystems manage the tension between innovation and
compatibility. If you are interested in this subject, feel free to get in touch.

__Profiles__  
- [reddit](https://www.reddit.com/user/pseudometapseudo)
- [Discord](https://discordapp.com/users/462774483044794368/)
- [Academic Website](https://chris-grieser.de/)
- [Twitter](https://twitter.com/pseudo_meta)
- [ResearchGate](https://www.researchgate.net/profile/Christopher-Grieser)
- [LinkedIn](https://www.linkedin.com/in/christopher-grieser-ba693b17a/)

<a href='https://ko-fi.com/Y8Y86SQ91' target='_blank'><img height='36'
style='border:0px;height:36px;' src='https://cdn.ko-fi.com/cdn/kofi1.png?v=3'
border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
