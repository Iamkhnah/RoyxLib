# Royx Library Ui leak by Khanhdz
___________________________________________________________________________________<3

Loadstring:
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Iamkhnah/RoyxLib/main/Library.lua"))()```

_____________________________________________________________________________________<3

- Create Window:
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Iamkhnah/RoyxLib/main/Library.lua"))()
local Main = Lib:royxstart("Royx Hub")```

- Create Tabs

```lua
local Tab = Main:royxtab("Tab 1")
local Tab2 = Main:royxtab("Tab 2")```
