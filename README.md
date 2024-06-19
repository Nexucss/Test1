if not game:IsLoaded() then
	wait(game.Loaded)	
end

local Bip = Instance.new("Sound")
local SomeThingNew = Instance.new("ScreenGui")
local Menu = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local List = Instance.new("ScrollingFrame")
local UIListLayout = Instance.new("UIListLayout")
local Logo = Instance.new("ImageButton")
local Pages = Instance.new("ImageLabel")
local UICorner_2 = Instance.new("UICorner")
local Money = Instance.new("Frame")
local Earn = Instance.new("Frame")
local Reward = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Amount = Instance.new("TextBox")
local UICorner_4 = Instance.new("UICorner")
local UICorner_5 = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local Back = Instance.new("Frame")
local UICorner_6 = Instance.new("UICorner")
local Home = Instance.new("Frame")
local Lobby = Instance.new("Frame")
local UICorner_7 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local Title_2 = Instance.new("TextLabel")
local Back_2 = Instance.new("Frame")
local UICorner_8 = Instance.new("UICorner")
local Unlock = Instance.new("Frame")
local Tags = Instance.new("Frame")
local UICorner_9 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UnlockT = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local Title_3 = Instance.new("TextLabel")
local Back_3 = Instance.new("Frame")
local UICorner_11 = Instance.new("UICorner")
local Banners = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local UnlockB = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local Cars = Instance.new("Frame")
local UICorner_14 = Instance.new("UICorner")
local TextLabel_4 = Instance.new("TextLabel")
local UnlockC = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local Btn = Instance.new("ImageButton")
local AnnonceFrame = Instance.new("Frame")
local Annonce = Instance.new("TextLabel")

SomeThingNew.Name = "SomeThingNew"
SomeThingNew.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
SomeThingNew.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Bip.Name = "Bip"
Bip.SoundId = "rbxassetid://464049227"
Bip.Volume = 0.3
Bip.Parent = SomeThingNew

Menu.Name = "Menu"
Menu.Parent = SomeThingNew
Menu.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Menu.BorderColor3 = Color3.fromRGB(0, 0, 0)
Menu.BorderSizePixel = 0
Menu.Position = UDim2.new(0.086965993, 0, 0.0907667279, 0)
Menu.Size = UDim2.new(0.0459041856, 0, 0.816901505, 0)
Menu.Visible = false
Menu.Image = "http://www.roblox.com/asset/?id=4987182376"
Menu.ScaleType = Enum.ScaleType.Crop

UICorner.CornerRadius = UDim.new(1, 0)
UICorner.Parent = Menu

List.Name = "List"
List.Parent = Menu
List.Active = true
List.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
List.BackgroundTransparency = 1.000
List.BorderColor3 = Color3.fromRGB(0, 0, 0)
List.BorderSizePixel = 0
List.Position = UDim2.new(0, 0, 0.0999999717, 0)
List.Size = UDim2.new(0.999999881, 0, 0.865517259, 0)
List.CanvasSize = UDim2.new(0, 0, 0, 0)
List.ScrollBarThickness = 0

UIListLayout.Parent = List
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.Padding = UDim.new(0.00999999978, 0)

Logo.Name = "Logo"
Logo.Parent = Menu
Logo.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Logo.BackgroundTransparency = 1.000
Logo.BorderColor3 = Color3.fromRGB(0, 0, 0)
Logo.BorderSizePixel = 0
Logo.Position = UDim2.new(0, 0, 0.0125624174, 0)
Logo.Size = UDim2.new(1, 0, 0.0874375924, 0)
Logo.Image = "rbxassetid://13511963939"
Logo.ScaleType = Enum.ScaleType.Fit

Pages.Name = "Pages"
Pages.Parent = SomeThingNew
Pages.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Pages.BorderColor3 = Color3.fromRGB(0, 0, 0)
Pages.BorderSizePixel = 0
Pages.Position = UDim2.new(0.140289024, 0, 0.0907667279, 0)
Pages.Size = UDim2.new(0.268933535, 0, 0.816901505, 0)
Pages.Visible = false
Pages.Image = "http://www.roblox.com/asset/?id=4987182376"
Pages.ScaleType = Enum.ScaleType.Crop

UICorner_2.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_2.Parent = Pages

Money.Name = "Money"
Money.Parent = Pages
Money.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Money.BackgroundTransparency = 1.000
Money.BorderColor3 = Color3.fromRGB(0, 0, 0)
Money.BorderSizePixel = 0
Money.Size = UDim2.new(1, 0, 1, 0)
Money.Visible = false

Earn.Name = "Earn"
Earn.Parent = Money
Earn.BackgroundColor3 = Color3.fromRGB(226, 82, 255)
Earn.BorderColor3 = Color3.fromRGB(0, 0, 0)
Earn.BorderSizePixel = 0
Earn.Position = UDim2.new(0.0566100702, 0, 0.120689638, 0)
Earn.Size = UDim2.new(0.848046601, 0, 0.2892721, 0)

Reward.Name = "Reward"
Reward.Parent = Earn
Reward.BackgroundColor3 = Color3.fromRGB(212, 0, 255)
Reward.BorderColor3 = Color3.fromRGB(0, 0, 0)
Reward.BorderSizePixel = 0
Reward.Position = UDim2.new(0.0582117438, 0, 0.52390182, 0)
Reward.Size = UDim2.new(0.883476079, 0, 0.338410497, 0)
Reward.Font = Enum.Font.Unknown
Reward.Text = "Reward"
Reward.TextColor3 = Color3.fromRGB(255, 255, 255)
Reward.TextScaled = true
Reward.TextSize = 14.000
Reward.TextWrapped = true

UICorner_3.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_3.Parent = Reward

Amount.Name = "Amount"
Amount.Parent = Earn
Amount.BackgroundColor3 = Color3.fromRGB(105, 25, 170)
Amount.BorderColor3 = Color3.fromRGB(0, 0, 0)
Amount.BorderSizePixel = 0
Amount.Position = UDim2.new(0.0582117997, 0, 0.0957854465, 0)
Amount.Size = UDim2.new(0.88347584, 0, 0.345695317, 0)
Amount.Font = Enum.Font.Michroma
Amount.Text = "100"
Amount.TextColor3 = Color3.fromRGB(255, 255, 255)
Amount.TextScaled = true
Amount.TextSize = 14.000
Amount.TextWrapped = true

UICorner_4.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_4.Parent = Amount

UICorner_5.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_5.Parent = Earn

Title.Name = "Title"
Title.Parent = Money
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.134076357, 0, 0, 0)
Title.Size = UDim2.new(0.689937234, 0, 0.100000009, 0)
Title.Font = Enum.Font.Unknown
Title.Text = "MONEY"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

Back.Name = "Back"
Back.Parent = Title
Back.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Back.BorderColor3 = Color3.fromRGB(0, 0, 0)
Back.BorderSizePixel = 0
Back.Position = UDim2.new(0.120917425, 0, 0.865900397, 0)
Back.Size = UDim2.new(0.758165181, 0, 0.134099588, 0)

UICorner_6.CornerRadius = UDim.new(1, 0)
UICorner_6.Parent = Back

Home.Name = "Home"
Home.Parent = Pages
Home.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Home.BackgroundTransparency = 1.000
Home.BorderColor3 = Color3.fromRGB(0, 0, 0)
Home.BorderSizePixel = 0
Home.Size = UDim2.new(1, 0, 1, 0)
Home.Visible = false

Lobby.Name = "Lobby"
Lobby.Parent = Home
Lobby.BackgroundColor3 = Color3.fromRGB(226, 82, 255)
Lobby.BorderColor3 = Color3.fromRGB(0, 0, 0)
Lobby.BorderSizePixel = 0
Lobby.Position = UDim2.new(0.0566100702, 0, 0.120689638, 0)
Lobby.Size = UDim2.new(0.848046601, 0, 0.2892721, 0)

UICorner_7.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_7.Parent = Lobby

TextLabel.Parent = Lobby
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.Font = Enum.Font.Unknown
TextLabel.Text = "This Script made by Nexucss"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Title_2.Name = "Title"
Title_2.Parent = Home
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title_2.BorderSizePixel = 0
Title_2.Position = UDim2.new(0.134076357, 0, 0, 0)
Title_2.Size = UDim2.new(0.689937234, 0, 0.100000009, 0)
Title_2.Font = Enum.Font.Unknown
Title_2.Text = "HOME"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

Back_2.Name = "Back"
Back_2.Parent = Title_2
Back_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Back_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Back_2.BorderSizePixel = 0
Back_2.Position = UDim2.new(0.120917425, 0, 0.865900397, 0)
Back_2.Size = UDim2.new(0.758165181, 0, 0.134099588, 0)

UICorner_8.CornerRadius = UDim.new(1, 0)
UICorner_8.Parent = Back_2

Unlock.Name = "Unlock"
Unlock.Parent = Pages
Unlock.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Unlock.BackgroundTransparency = 1.000
Unlock.BorderColor3 = Color3.fromRGB(0, 0, 0)
Unlock.BorderSizePixel = 0
Unlock.Size = UDim2.new(1, 0, 1, 0)

Tags.Name = "Tags"
Tags.Parent = Unlock
Tags.BackgroundColor3 = Color3.fromRGB(226, 82, 255)
Tags.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tags.BorderSizePixel = 0
Tags.Position = UDim2.new(0.0566100404, 0, 0.120689638, 0)
Tags.Size = UDim2.new(0.848046482, 0, 0.188772783, 0)

UICorner_9.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_9.Parent = Tags

TextLabel_2.Parent = Tags
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Size = UDim2.new(0.99999994, 0, 0.401663095, 0)
TextLabel_2.Font = Enum.Font.Unknown
TextLabel_2.Text = "Unlock All Tags"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextScaled = true
TextLabel_2.TextSize = 14.000
TextLabel_2.TextWrapped = true

UnlockT.Name = "UnlockT"
UnlockT.Parent = Tags
UnlockT.BackgroundColor3 = Color3.fromRGB(212, 0, 255)
UnlockT.BorderColor3 = Color3.fromRGB(0, 0, 0)
UnlockT.BorderSizePixel = 0
UnlockT.Position = UDim2.new(0.0582117438, 0, 0.52390182, 0)
UnlockT.Size = UDim2.new(0.883476079, 0, 0.338410497, 0)
UnlockT.Font = Enum.Font.Unknown
UnlockT.Text = "Unlock"
UnlockT.TextColor3 = Color3.fromRGB(255, 255, 255)
UnlockT.TextScaled = true
UnlockT.TextSize = 14.000
UnlockT.TextWrapped = true

UICorner_10.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_10.Parent = UnlockT

Title_3.Name = "Title"
Title_3.Parent = Unlock
Title_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_3.BackgroundTransparency = 1.000
Title_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title_3.BorderSizePixel = 0
Title_3.Position = UDim2.new(0.134076357, 0, 0, 0)
Title_3.Size = UDim2.new(0.689937234, 0, 0.100000009, 0)
Title_3.Font = Enum.Font.Unknown
Title_3.Text = "UNLOCK"
Title_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_3.TextScaled = true
Title_3.TextSize = 14.000
Title_3.TextWrapped = true

Back_3.Name = "Back"
Back_3.Parent = Title_3
Back_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Back_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Back_3.BorderSizePixel = 0
Back_3.Position = UDim2.new(0.120917425, 0, 0.865900397, 0)
Back_3.Size = UDim2.new(0.758165181, 0, 0.134099588, 0)

UICorner_11.CornerRadius = UDim.new(1, 0)
UICorner_11.Parent = Back_3

Banners.Name = "Banners"
Banners.Parent = Unlock
Banners.BackgroundColor3 = Color3.fromRGB(226, 82, 255)
Banners.BorderColor3 = Color3.fromRGB(0, 0, 0)
Banners.BorderSizePixel = 0
Banners.Position = UDim2.new(0.0566100404, 0, 0.328667432, 0)
Banners.Size = UDim2.new(0.848046482, 0, 0.188772783, 0)

UICorner_12.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_12.Parent = Banners

TextLabel_3.Parent = Banners
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Size = UDim2.new(0.99999994, 0, 0.401663095, 0)
TextLabel_3.Font = Enum.Font.Unknown
TextLabel_3.Text = "Unlock All Banners"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextScaled = true
TextLabel_3.TextSize = 14.000
TextLabel_3.TextWrapped = true

UnlockB.Name = "UnlockB"
UnlockB.Parent = Banners
UnlockB.BackgroundColor3 = Color3.fromRGB(212, 0, 255)
UnlockB.BorderColor3 = Color3.fromRGB(0, 0, 0)
UnlockB.BorderSizePixel = 0
UnlockB.Position = UDim2.new(0.0582117438, 0, 0.52390182, 0)
UnlockB.Size = UDim2.new(0.883476079, 0, 0.338410497, 0)
UnlockB.Font = Enum.Font.Unknown
UnlockB.Text = "Unlock"
UnlockB.TextColor3 = Color3.fromRGB(255, 255, 255)
UnlockB.TextScaled = true
UnlockB.TextSize = 14.000
UnlockB.TextWrapped = true

UICorner_13.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_13.Parent = UnlockB

Cars.Name = "Cars"
Cars.Parent = Unlock
Cars.BackgroundColor3 = Color3.fromRGB(226, 82, 255)
Cars.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cars.BorderSizePixel = 0
Cars.Position = UDim2.new(0.0544852465, 0, 0.538041055, 0)
Cars.Size = UDim2.new(0.848046482, 0, 0.188772783, 0)

UICorner_14.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_14.Parent = Cars

TextLabel_4.Parent = Cars
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Size = UDim2.new(0.99999994, 0, 0.401663095, 0)
TextLabel_4.Font = Enum.Font.Unknown
TextLabel_4.Text = "Unlock All Cars"
TextLabel_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.TextScaled = true
TextLabel_4.TextSize = 14.000
TextLabel_4.TextWrapped = true

UnlockC.Name = "UnlockC"
UnlockC.Parent = Cars
UnlockC.BackgroundColor3 = Color3.fromRGB(212, 0, 255)
UnlockC.BorderColor3 = Color3.fromRGB(0, 0, 0)
UnlockC.BorderSizePixel = 0
UnlockC.Position = UDim2.new(0.0582117438, 0, 0.52390182, 0)
UnlockC.Size = UDim2.new(0.883476079, 0, 0.338410497, 0)
UnlockC.Font = Enum.Font.Unknown
UnlockC.Text = "Unlock"
UnlockC.TextColor3 = Color3.fromRGB(255, 255, 255)
UnlockC.TextScaled = true
UnlockC.TextSize = 14.000
UnlockC.TextWrapped = true

UICorner_15.CornerRadius = UDim.new(0.0799999982, 0)
UICorner_15.Parent = UnlockC

Btn.Name = "Btn"
Btn.Parent = script
Btn.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Btn.BackgroundTransparency = 1.000
Btn.BorderColor3 = Color3.fromRGB(0, 0, 0)
Btn.BorderSizePixel = 0
Btn.Size = UDim2.new(1, 0, 0.100000001, 0)
Btn.Image = "http://www.roblox.com/asset/?id=16639247784"
Btn.ScaleType = Enum.ScaleType.Fit

AnnonceFrame.Name = "AnnonceFrame"
AnnonceFrame.Parent = SomeThingNew
AnnonceFrame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
AnnonceFrame.BackgroundTransparency = 1.000
AnnonceFrame.Position = UDim2.new(-0.5, 0, -0.5, 0)
AnnonceFrame.Size = UDim2.new(2, 0, 2, 0)
AnnonceFrame.ZIndex = 99

Annonce.Name = "Annonce"
Annonce.Parent = AnnonceFrame
Annonce.BackgroundTransparency = 1.000
Annonce.Position = UDim2.new(0.216227204, 0, 0.456957787, 0)
Annonce.Size = UDim2.new(0.566999972, 0, 0.0853989795, 0)
Annonce.ZIndex = 100
Annonce.Text = ""
Annonce.TextColor3 = Color3.fromRGB(255, 255, 255)
Annonce.TextScaled = true
Annonce.TextWrapped = true

-- Scripts:

local TweenService = game:GetService("TweenService")
local UIS = game:GetService("UserInputService")
local Key = Enum.KeyCode.F4
local ReplicatedStorage = game:GetService("ReplicatedStorage")
local event = ReplicatedStorage:WaitForChild("Tags").TagSet
local Cooldown = false
local BtnsVal = {"Home", "Money", "Unlock",}

function createAnnouncement(Text, announcement, message)
	Text.Text = ""
	Text.TextTransparency = 0
	announcement.Transparency = 1
	announcement.Visible = true
	local fadeTweenInfo = TweenInfo.new(0.4, Enum.EasingStyle.Quad, Enum.EasingDirection.InOut)
	local fadeInTween = TweenService:Create(announcement, fadeTweenInfo, {Transparency = 0.5})
	fadeInTween:Play()
	task.wait(0.3)
	for i = 1, string.len(message) do
		Text.Text = string.sub(message, 1, i)
		local currentChar = string.sub(message, i, i)
		task.wait(currentChar == "\n" and 0.03 or currentChar == " " and 0.03 or 0.04)
		Bip:Play()
	end
	local announcementTime = string.len(message) / 70
	task.wait(announcementTime)
	local fadeOutTween = TweenService:Create(announcement, fadeTweenInfo, {Transparency = 1})
	fadeOutTween:Play()
	local fadeTextTween = TweenService:Create(Text, fadeTweenInfo, {TextTransparency = 1})
	fadeTextTween:Play()
	fadeTextTween.Completed:Wait()
	announcement.Visible = false
end

function SmoothChangeProperty(object, property, endValue, duration,Style)
	local initialValue = object[property]
	local tweenInfo = TweenInfo.new(duration,Style)
	local tween = TweenService:Create(object, tweenInfo, {[property] = endValue})
	tween:Play()
end

function SendNotifTitre()
	shared:SendNotification({
		Title = "TITRE",
		Text = "Vous avez obtenu TOUS les Titres",
		Duration = 15,
	})
end

function SendNotifMoney()
	shared:SendNotification({
		Title = "ARGENT",
		Text = "Vous avez obtenu " .. Pages.Money.Earn.Amount.Text .. " de VoiceCoins",
		Duration = 15,
	})
end

createAnnouncement(Annonce, AnnonceFrame, "The Script is injected into the game,\nin order to avoid bugs it is advisable not to spam the execute button of your injector,\nPress F4 to open the exploit,\n{Script V1.4} (By : Nexucss)")
AnnonceFrame:Destroy()
Annonce:Destroy()

UIS.InputBegan:Connect(function(input)
	if input.KeyCode == Key then
		if Cooldown == false then
			Cooldown = true
			if Menu.Visible == false then
				Menu.Visible = true
				SmoothChangeProperty(Menu,"Size",UDim2.new(0.046, 0, 0.817, 0),0.5,Enum.EasingStyle.Back)
				wait(0.5)
				Cooldown = false
			else
				SmoothChangeProperty(Menu,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
				SmoothChangeProperty(Pages,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
				wait(0.3)
				Menu.Visible = false
				Pages.Visible = false
				Cooldown = false
			end
		end
	end
end)

for i, v in ipairs(List:GetChildren()) do
	if v:IsA("ImageButton") then
		v.MouseButton1Click:Connect(function()
			if Cooldown == false then
				Cooldown = true
				if Pages.Visible == false then
					Pages.Visible = true
					SmoothChangeProperty(Pages,"Size",UDim2.new(0.269, 0,0.817, 0),0.5,Enum.EasingStyle.Back)
					wait(0.5)
					Cooldown = false
				else
					SmoothChangeProperty(Pages,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
					wait(0.3)
					Pages.Visible = false
					Cooldown = false
				end
			end
		end)
	end
end

for i, v in ipairs(BtnsVal) do
	local New = script.Btn:Clone()
	New.Name = v
	if v == "Money" then
		New.Image = "http://www.roblox.com/asset/?id=17033973836"
	elseif v == "Unlock" then
		New.Image = "http://www.roblox.com/asset/?id=10695825676"
	end
	New.Parent = List
end


List:FindFirstChild("Home").MouseButton1Click:Connect(function()
	if Cooldown == false then
		Cooldown = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
		wait(0.3)
		Pages.Visible = true
		for i, v in ipairs(Pages:GetChildren()) do
			if v:IsA("Frame") then
				v.Visible = false
			end
		end
		Pages:FindFirstChild("Home").Visible = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.269, 0,0.817, 0),0.5,Enum.EasingStyle.Back)
		wait(0.5)
		Cooldown = false
	end
end)

List:FindFirstChild("Money").MouseButton1Click:Connect(function()
	if Cooldown == false then
		Cooldown = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
		wait(0.3)
		Pages.Visible = true
		for i, v in ipairs(Pages:GetChildren()) do
			if v:IsA("Frame") then
				v.Visible = false
			end
		end
		Pages:FindFirstChild("Money").Visible = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.269, 0,0.817, 0),0.5,Enum.EasingStyle.Back)
		wait(0.5)
		Cooldown = false
	end
end)

List:FindFirstChild("Unlock").MouseButton1Click:Connect(function()
	if Cooldown == false then
		Cooldown = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.046, 0, 0.085, 0),0.3,Enum.EasingStyle.Back)
		wait(0.3)
		Pages.Visible = true
		for i, v in ipairs(Pages:GetChildren()) do
			if v:IsA("Frame") then
				v.Visible = false
			end
		end
		Pages:FindFirstChild("Unlock").Visible = true
		SmoothChangeProperty(Pages,"Size",UDim2.new(0.269, 0,0.817, 0),0.5,Enum.EasingStyle.Back)
		wait(0.5)
		Cooldown = false
	end
end)


Pages:FindFirstChild("Unlock").Tags.UnlockT.MouseButton1Click:Connect(function()
	local TagsFolder = game.Players.LocalPlayer:WaitForChild("TagsFolder")
	for i, v in ipairs(TagsFolder:GetChildren()) do
		event:FireServer("Tag_Set-122", v.Name, true)
	end
	SendNotifTitre()
end)

Pages:FindFirstChild("Unlock").Tags.UnlockT.MouseButton1Click:Connect(function()
	local TagsFolder = game.Players.LocalPlayer:WaitForChild("TagsFolder")
	for i, v in ipairs(TagsFolder:GetChildren()) do
		event:FireServer("Tag_Set-122", v.Name, true)
	end
	SendNotifTitre()
end)

Pages:FindFirstChild("Unlock").Cars.UnlockC.MouseButton1Click:Connect(function()
	local VoitureFolder = game.Players.LocalPlayer:WaitForChild("VoitureFolder")
	for i, v in ipairs(VoitureFolder:GetChildren()) do
		if v:IsA("BoolValue") then
			game.ReplicatedStorage.Voiture.Buy:FireServer("vip_set_one", v.Name, 0)
		end
	end
end)

Pages:FindFirstChild("Money").Earn.Reward.MouseButton1Click:Connect(function()
	local rs = game:GetService("ReplicatedStorage")
	local AddReward = rs:WaitForChild("Tags").AddReward
	AddReward:FireServer("REWARD-99938-2222", Pages.Money.Earn.Amount.Text)
	SendNotifMoney()
end)
