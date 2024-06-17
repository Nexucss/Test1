if not game:IsLoaded() then
	wait(game.Loaded)	
end

local Btns = {"DarkMatterCar", "DarkMatterUser", "PurpleGuyUser"}
local DarkTest1 = 1

local Gui = Instance.new("ScreenGui")
Gui.Name = "SomethingNew"
Gui.Parent =  game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

local Frame = Instance.new("ImageLabel")
Frame.Size = UDim2.new(0.1, 0, 0.252, 0)
Frame.Position = UDim2.new(0.167, 0, 0.128, 0)
Frame.Image = "http://www.roblox.com/asset/?id=4987182376"
Instance.new("UICorner").Parent = Frame
Frame.Parent = Gui

local List = Instance.new("ScrollingFrame")
List.Size = UDim2.new(1, 0, 1, 0)
List.Position = UDim2.new(0, 0, 0, 0)
Instance.new("UIListLayout").Parent = List
List.Transparency = 1
List.Parent = Frame

for i, v in ipairs(Btns) do
	local Btn = Instance.new("TextButton")
	Btn.Name = v
	Btn.Text = v
	Btn.Size = UDim2.new(1, 0, 0.1, 0)
	Btn.Position = UDim2.new(0, 0, 0, 0)
	Instance.new("UICorner").Parent = Btn
	local UiS = Instance.new("UIStroke")
	UiS.ApplyStrokeMode = "Border"
	UiS.Parent = Btn
	Btn.Parent = List
end

List:FindFirstChild("DarkMatterCar").MouseButton1Click:Connect(function()
	if DarkTest1 == 1 then
		DarkTest1 = 2
	elseif DarkTest1 == 2 then
		DarkTest1 = 1
	end
	while DarkTest1 == 2 do
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=5840351987")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=17296428221")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=9808795941")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=16457043130")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=1307573593")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=16601233770")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "rbxassetid://13910645715")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=5498732628")
		wait(0.3)
		game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Texture_Server_001", "http://www.roblox.com/asset/?id=4987182376")
		wait(0.3)
	end
end)
