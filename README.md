A Spotlight-like rofi. Supports file and web search[WIP]. 

| File Browsing | Context Menu |
| --- | --- |
| ![screenshot](screenshots/main.png) | ![screenshot](screenshots/menu.png) |

This rofi will supposed to replace the web search in my awesome-wm setups.

#### Dependencies
+ `rofi git master branch`
+ `python3`
+ `bash`
+ `an icon theme (optional)`

#### Icon themes used:
+ Papirus
+ Tela Blue

#### Run it by:

```bash
$ rofi -modi "Global Search":"rofi-spotlight/rofi-spotlight.sh" -show "Global Search" \
-config rofi-spotlight/rofi.rasi
```

#### Configuration:
You can change the following variables in the `rofi-spotlight.sh`
+ Terminal Emulator
+ File Manager
+ Bluetooth sender

#### TODOs:
- [x] Web search support
- [ ] Cleaner bash script


I'm fairly new on scripting something like this big, so pardon me if my code is kinda ugly, boilerplate and obscure. I will improve this from time to time, for sure.
