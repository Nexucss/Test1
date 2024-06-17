if not game:IsLoaded() then
	wait(game.Loaded)	
end

local Gui = Instance.new("ScreenGui")
Gui.Name = "SomethingNew"
Gui.Parent =  game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

local Frame = Instance.new("Frame")
Frame.Size = UDim2.new(0.1, 0, 0.252, 0)
Frame.Position = UDim2.new(0.167, 0, 0.128, 0)
Frame.Parent = Gui
