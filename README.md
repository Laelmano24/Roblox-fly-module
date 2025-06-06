# Roblox Fly Module

This module is an adaptation of a popular script, refactored into a module format to allow seamless integration into your own Roblox scripts.

**Credits**:  
Special thanks to **MaksBloxX**, from whom I obtained this version. He may not be the original creator, but he is the one who shared this version publicly.

---

## 📦 How to Use

### 🧩 Import the Module

```lua
local flyFunction = loadstring(game:HttpGet("aindavoucolocar"))()
```

### ✈️ Toggle Fly Mode
```lua
local flyFunction = loadstring(game:HttpGet("aindavoucolocar"))()
local speed = 1
flyFunction(speed) -- Call the function to toggle fly mode on or off
```

### ⚙️ Configurable Settings
```lua
getgenv().flyModeSpeed = 1 -- Fly speed (modifiable, but usually unnecessary)
getgenv().PressKeyToFly = Enum.KeyCode.R -- Change the key used to toggle fly mode
```

## ⚠️ Disclaimer
I have only modified certain parts of the original script. I initially considered rewriting the entire codebase for better understanding but eventually decided not to.

