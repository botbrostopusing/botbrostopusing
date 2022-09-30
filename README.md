local OrionLib = loadstring(game:HttpGet(('https://raw.githubusercontent.com/shlexware/Orion/main/source')))()

local Window = OrionLib:MakeWindow({Name = "Street Simulator free script ", HidePremium = false, SaveConfig = true, ConfigFolder = "OrionTest"})

local Tab = Window:MakeTab({
	Name = "autofarm",
	Icon = "rbxassetid://4483345998",
	PremiumOnly = false
})

local Section = Tab:AddSection({
	Name = "autofarm crash paid more button"
})

Tab:AddButton({
	Name = "autofarm crash need 100 money",
	Callback = function()
      		print("button pressed")
      		while true do
wait(1)
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
	Name = "autofarm crash only need 10 money or 1 money sorry my bad ",
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
	Name = "AutoFarm crash need 500 money",
	Callback = function()
      		print("button pressed")
      		while true do
wait(1)
local args = {
    [1] = "Bet",
    [2] = "250",
    [3] = "1.02"
}

game:GetService("ReplicatedStorage").Events.CrashAction:FireServer(unpack(args))
end
      		
  	end    
})
