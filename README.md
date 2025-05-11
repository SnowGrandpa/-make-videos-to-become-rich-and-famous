# -make-videos-to-become-rich-and-famous
# Roblox Auto Teleport Script

This Lua script is designed for use in Roblox and automatically teleports the local player to a specific in-game location on a loop. It includes a cooldown timer to match in-game reward cooldowns and a keybind to stop the loop manually.

## 📜 Description

The script:

- Teleports the player slightly above a money pad or reward zone.
- Waits 5.3 seconds before repeating (to match a UI or reward cooldown).
- Allows manual stopping of the loop by pressing the `L` key.

Useful for games where you want to repeatedly return to a specific spot without walking, such as obbies or farming zones.

## 📦 Features

- Automatic looping teleport
- Jump-state trigger to avoid getting stuck
- Manual stop with `L` key
- Clean structure using Roblox's `UserInputService`

## 🧠 Requirements

- Must be run in a LocalScript context (client-side)
- Player character must be loaded before execution
- Works only in environments where `LocalPlayer` and `CFrame` manipulation is allowed

## 🧪 Example Location

```lua
local location = CFrame.new(-558.864868, 74.3, -2.64647651)
⌨️ Controls
L — Stop teleport loop

📝 Disclaimer
This script is intended for educational and prototyping purposes in Roblox Studio or games that allow client scripting. Use responsibly and respect game rules and terms of service.
