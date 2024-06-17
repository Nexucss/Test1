if not game:IsLoaded() then
	wait(game.Loaded)	
end
local UIS = game:GetService("UserInputService")
local input_Key = Enum.KeyCode.F4
local Btns = {"DarkMatterCar", "DarkMatterUser", "PurpleGuyUser", "NameMatter", "RainBowCar"}
local DarkTest1 = 1
local DarkTest2 = 1
local RainBow1 = 1

local Gui = Instance.new("ScreenGui")
Gui.Name = "SomethingNew"
Gui.ResetOnSpawn = false
Gui.Parent =  game:GetService("Players").LocalPlayer:WaitForChild("PlayerGui")

local Black = Instance.new("Frame")
local IntroText = Instance.new("TextLabel")
IntroText.Name = "IntroText"
Black.Size = UDim2.new(2, 0, 2, 0)
Black.Position = UDim2.new(-0.5, 0, -0.5, 0)
Black.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Black.BackgroundTransparency = 0.5
IntroText.Size = UDim2.new(0.567, 0, 0.07, 0)
IntroText.Position = UDim2.new(0.217, 0, 0.464, 0)
IntroText.BackgroundTransparency = 1
IntroText.TextScaled = true
IntroText.TextColor3 = Color3.fromRGB(255, 255, 255)
IntroText.Text = "The Script is injected into the game, in order to avoid bugs it is advisable not to spam the execute button of your injector, Press F4 to open the exploit, {Script V1.0} (By : Nexucss)"
IntroText.ZIndex = 100
Black.ZIndex = 99
Black.Parent = Gui
IntroText.Parent = Gui
wait(5)
Black:Destroy()
IntroText:Destroy()


local Frame = Instance.new("ImageLabel")
Frame.Size = UDim2.new(0.1, 0, 0.252, 0)
Frame.Position = UDim2.new(0.167, 0, 0.128, 0)
Frame.Image = "http://www.roblox.com/asset/?id=4987182376"
Instance.new("UICorner").Parent = Frame
Frame.Visible = false
Frame.Parent = Gui

local Bord = Instance.new("Frame")
Bord.Size = UDim2.new(1, 0, 0.2, 0)
Bord.Position = UDim2.new(0, 0, 0, 0)
Bord.BackgroundColor3 = Color3.fromRGB(119, 0, 216)
Instance.new("UICorner").Parent = Bord
Bord.Parent = Frame

local List = Instance.new("ScrollingFrame")
List.Size = UDim2.new(1, 0, 0.8, 0)
List.Position = UDim2.new(0, 0, 0.2, 0)
Instance.new("UIListLayout").Parent = List
List.CanvasSize = UDim2.new(0, 0, 0, 0)
List.Transparency = 1
List.Parent = Frame

for i, v in ipairs(Btns) do
	local Btn = Instance.new("TextButton")
	Btn.Name = v
	Btn.Text = v
	Btn.TextScaled = true
	Btn.BackgroundColor3 = Color3.fromRGB(194, 38, 255)
	Btn.TextColor3 = Color3.fromRGB(255, 255, 255)
	Btn.Size = UDim2.new(1, 0, 0.15, 0)
	Btn.Position = UDim2.new(0, 0, 0, 0)
	Instance.new("UICorner").Parent = Btn
	local UiS = Instance.new("UIStroke")
	UiS.ApplyStrokeMode = "Border"
	UiS.Parent = Btn
	Btn.Parent = List
end

UIS.InputBegan:Connect(function(input)
	if input.KeyCode == input_Key then
		Frame.Visible = not Frame.Visible
	end
end)

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

List:FindFirstChild("NameMatter").MouseButton1Click:Connect(function()
	if DarkTest2 == 1 then
		DarkTest2 = 2
	elseif DarkTest2 == 2 then
		DarkTest2 = 1
		game.ReplicatedStorage:WaitForChild("Tags").Equip:FireServer("TAG-SERVER-001", true, "event")
		game.ReplicatedStorage.OverheadRS.EquiperJoin:FireServer("rbxassetid://13910645715")
	end
	while DarkTest2 == 2 do
		game.ReplicatedStorage:WaitForChild("Tags").Equip:FireServer("TAG-SERVER-001", true, "npc")
		game.ReplicatedStorage.OverheadRS.EquiperJoin:FireServer("http://www.roblox.com/asset/?id=4987182376")
		wait(1)
		game.ReplicatedStorage:WaitForChild("Tags").Equip:FireServer("TAG-SERVER-001", true, "event")
		game.ReplicatedStorage.OverheadRS.EquiperJoin:FireServer("http://www.roblox.com/asset/?id=13337537906")
		wait(1)
	end
end)

List:FindFirstChild("PurpleGuyUser").MouseButton1Click:Connect(function()
	DarkTest2 = 1
	game.ReplicatedStorage.OverheadRS.EquiperJoin:FireServer("http://www.roblox.com/asset/?id=13337537906")
end)

List:FindFirstChild("DarkMatterUser").MouseButton1Click:Connect(function()
	DarkTest2 = 1
	game.ReplicatedStorage.OverheadRS.EquiperJoin:FireServer("http://www.roblox.com/asset/?id=4987182376")
end)

List:FindFirstChild("RainBowCar").MouseButton1Click:Connect(function()
	local R, G, B = 255, 0, 0
	if RainBow1 == 1 then
		RainBow1 = 2
	elseif RainBow1 == 2 then
		RainBow1 = 1
	end
	while RainBow1 == 2 do
		for Value = 1, 255 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			G += 1
		end
		for Value = 1, 255 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			R -= 1
		end
		for Value = 1, 255 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			B += 1
		end
		for Value = 1, 25 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			G -= 1
		end
		for Value = 1, 255 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			R += 1
		end
		for Value = 1, 255 do
			task.wait()
			game.ReplicatedStorage.Voiture.Car_Color:FireServer("Car_Color_Server_001", Color3.fromRGB(R, G, B))
			B -= 1
		end
	end
end)
