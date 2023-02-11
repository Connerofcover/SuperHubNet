local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()
local Window = OrionLib:MakeWindow({IntroText = "Super Dupe",Name = "Super Dupe[1.0v]✔️", HidePremium = false, SaveConfig = true, ConfigFolder = "ProjectScam"})

-- Tabs
local MainTab = Window:MakeTab({
	Name = "Dupe",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

OrionLib:MakeNotification({ 	Name = "Hey!", 	Content = "Welcome to Super Dupe", 	Image = "rbxassetid://4483345998", 	Time = 20 })

OrionLib:MakeNotification({ 	Name = "Super Hub✔️", 	Content = "Made by Super Hub✔", 	Image = "rbxassetid://4483345998", 	Time = 19 })

-- Button
MainTab:AddButton({
	Name = "Dupe",
	Callback = function() loadstring(game:HttpGet("https://raw.githubusercontent.com/SuperHubTeam/SuperHubNet/main/SuperDupe", true))() 
	 end
}) 

CreditsTab:AddParagraph("Credits to","NooBed And The Other Creator Of The Hub")

coroutine.resume(NotificationCoroutine)

OrionLib:Init()
