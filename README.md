local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Title of the library", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})


local Tab = Window:MakeTab({
	Name = "Tab 1",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "Section"
})


Tab:AddButton({
	Name = "AUTOFARM 1 MONEY NEED",
	Callback = function()
      		print("button pressed")
      		 while true do
wait(0.1)
local args = {
    [1] = "Bet",
    [2] = "1",
    [3] = "1.02"
}

game:GetService("ReplicatedStorage").Events.CrashAction:FireServer(unpack(args))
end
  	end    
})


Tab:AddButton({
	Name = "autofarm 100 money need",
	Callback = function()
      		print("button pressed")
      		 while true do
wait(0.1)
local args = {
    [1] = "Bet",
    [2] = "50",
    [3] = "1.02"
}

game:GetService("ReplicatedStorage").Events.CrashAction:FireServer(unpack(args))
end
  	end    
})

Tab:AddButton({
	Name = "autofarm need 1000 money",
	Callback = function()
      		print("button pressed")
		      		 while true do
wait(0.1)
local args = {
    [1] = "Bet",
    [2] = "50",
    [3] = "1.02"
}

game:GetService("ReplicatedStorage").Events.CrashAction:FireServer(unpack(args))
end
  	end    
})

Tab:AddButton({
	Name = "autofarm need 1000 money",
	Callback = function()
      		print("button pressed")
				      		 while true do
wait(0.1)
local args = {
    [1] = "Bet",
    [2] = "100",
    [3] = "1.02"
}

game:GetService("ReplicatedStorage").Events.CrashAction:FireServer(unpack(args))
end
  	end    
})


OrionLib:Init()
