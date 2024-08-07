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

- Create Line
```lua
Page:Line()
```

- Create Label
```lua
Page:Label("Using App SayGex69 now")
```

- Create Textbox
```lua
Page:Textbox("TextBox","PlaceFolder",function(v)
	_G.Textbox = v
	print(_G.Textbox)
end)
```

- Create DropDown
```lua
local dropno = Page:Dropdown("DropDown",{"1","2","3"},"3",function (v)
	_G.dropno = v
end)
```
- Clear DropDown
```lua
dropno:Clear()
```

Exam:
```lua
Page:Button("Clear Dropdown",function()
	dropno:Clear()
end)
```

- Add DropDown
```lua
dropno:Add("Test")
```
Exam:
```lua
Page:Button("Add Dropdown",function()
	dropno:Add("Test")
end)
```

- Add slider
```lua
Page:Slider("Slider",true,0,100,10,10,function(v)
	print(v)
end)
```

- Multi DropDown
```lua
local test ={
	a = false;
	b = false;
	c = false;
}

Page:MultiDropdown("Multi DropDown",true,{
	location = test;
	list = {
		{
			Name = "one";
			flag = "a";
		};
		{
			Name = "two";
			flag = "b";
		};
		{
			Name = "thee";
			flag = "c";
		};
	};
	default = "test";
}, function(v)
	_G.dropno = v
end)
```

_________________________________________________________________________________<3

not my Ui library
dms khnahnopro165626 (ItOnltz) to buy source 🤑 or join sever: https://discord.gg/r4dh9McSj7  to get free Source =))
