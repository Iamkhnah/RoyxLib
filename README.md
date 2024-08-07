# Royx Library Ui leak by Khanhdz
___________________________________________________________________________________<3

- Loadstring:
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/Iamkhnah/RoyxLib/main/Library.lua"))()
```

_____________________________________________________________________________________<3

- Create Window:
```lua
local Lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/Iamkhnah/RoyxLib/main/Library.lua"))()
local Main = Lib:royxstart("Royx Hub")
```

- Create Tabs

```lua
local Tab = Main:royxtab("Tab 1")
local Tab2 = Main:royxtab("Tab 2")
```

- Create Page
```lua
local Page = Tab:royxpage("Auto Farm")
```

- Create Button
```lua
Page:Button("Button",function()
   print("Sex that tuyet khi co Hutao")
end)
```
- Create Notification
```lua
Lib:Notification("Notification","Royx",5)
```
Exam: 
```lua
Page:Button("Notification",function()
   Lib:Notification("Notification","Royx",5)
end)
```
Function:
```lua
function Alert(cac, bu, dur)
   Lib:Notification(cac,bu,dur)
end
Alert("Notification", "You are Gay (legit)", 5)
```

- Create Toggle
```lua
local Toggle = Page:Toggle("Toggle",17634661789,false,function(V)
   succac = V
end)
```
<h4>Can change 17634661789 to every decal in roblox</h4>
