print("AEGONA STORE!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!")


local selecting = nil

local AegonaStore = Instance.new("ScreenGui")
local Background = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local TitleName = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Noclip = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Walk = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local TextBox = Instance.new("TextBox")
local UICorner_6 = Instance.new("UICorner")
local Walk_2 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local TitleTime = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local Toggle = Instance.new("ImageButton")
local SelectFrame = Instance.new("Frame")
local UIGradient = Instance.new("UIGradient")
local Title_2 = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local UICorner_10 = Instance.new("UICorner")
local Title_3 = Instance.new("TextLabel")
local UICorner_11 = Instance.new("UICorner")
local B = Instance.new("Frame")
local UICorner_12 = Instance.new("UICorner")
local Button1 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local Button2 = Instance.new("TextButton")
local UICorner_14 = Instance.new("UICorner")
local ImageLabel_2 = Instance.new("ImageLabel")
local Background2 = Instance.new("Frame")
local UICorner_15 = Instance.new("UICorner")

--Properties:

AegonaStore.Name = "AegonaStore"
AegonaStore.Parent = game.CoreGui
AegonaStore.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Background.Name = "Background"
Background.Parent = AegonaStore
Background.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Background.BorderColor3 = Color3.fromRGB(0, 0, 0)
Background.BorderSizePixel = 0
Background.Position = UDim2.new(0.381126165, 0, 0.242592588, 0)
Background.Size = UDim2.new(0.237102658, 0, 0.515291929, 0)
Background.Visible = false

UICorner.Parent = Background

Title.Name = "Title"
Title.Parent = Background
Title.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.0285714287, 0, 0.0161870494, 0)
Title.Size = UDim2.new(0.945054948, 0, 0.124100722, 0)
Title.Font = Enum.Font.SourceSansBold
Title.Text = "Noclip โปรทะลุ"
Title.TextColor3 = Color3.fromRGB(255, 255, 255)
Title.TextScaled = true
Title.TextSize = 14.000
Title.TextWrapped = true

UICorner_2.Parent = Title

TitleName.Name = "TitleName"
TitleName.Parent = Background
TitleName.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
TitleName.BorderColor3 = Color3.fromRGB(0, 0, 0)
TitleName.BorderSizePixel = 0
TitleName.Position = UDim2.new(0.0285714287, 0, 0.169064745, 0)
TitleName.Size = UDim2.new(0.945054948, 0, 0.0809352547, 0)
TitleName.Font = Enum.Font.SourceSansItalic
TitleName.Text = "Name (@name)"
TitleName.TextColor3 = Color3.fromRGB(255, 255, 255)
TitleName.TextScaled = true
TitleName.TextSize = 14.000
TitleName.TextWrapped = true

UICorner_3.Parent = TitleName

Noclip.Name = "Noclip"
Noclip.Parent = Background
Noclip.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Noclip.BorderColor3 = Color3.fromRGB(0, 0, 0)
Noclip.BorderSizePixel = 0
Noclip.Position = UDim2.new(0.0285714287, 0, 0.320143878, 0)
Noclip.Size = UDim2.new(0.942857146, 0, 0.152877703, 0)
Noclip.Font = Enum.Font.SourceSansBold
Noclip.Text = "ทะลุ : ปิด"
Noclip.TextColor3 = Color3.fromRGB(255, 255, 255)
Noclip.TextScaled = true
Noclip.TextSize = 14.000
Noclip.TextWrapped = true

UICorner_4.Parent = Noclip

Walk.Name = "Walk"
Walk.Parent = Background
Walk.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Walk.BorderColor3 = Color3.fromRGB(0, 0, 0)
Walk.BorderSizePixel = 0
Walk.Position = UDim2.new(0.0307692308, 0, 0.528777003, 0)
Walk.Size = UDim2.new(0.942857146, 0, 0.0953237414, 0)
Walk.Font = Enum.Font.SourceSansBold
Walk.Text = "วิงไว"
Walk.TextColor3 = Color3.fromRGB(255, 255, 255)
Walk.TextScaled = true
Walk.TextSize = 14.000
Walk.TextWrapped = true

UICorner_5.Parent = Walk

TextBox.Parent = Walk
TextBox.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
TextBox.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextBox.BorderSizePixel = 0
TextBox.Position = UDim2.new(0, 0, 1.33962262, 0)
TextBox.Size = UDim2.new(0.538461566, 0, 0.943396211, 0)
TextBox.Font = Enum.Font.SourceSansItalic
TextBox.PlaceholderText = "ใส่ความไว"
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBox.TextScaled = true
TextBox.TextSize = 14.000
TextBox.TextWrapped = true

UICorner_6.Parent = TextBox

Walk_2.Name = "Walk"
Walk_2.Parent = Walk
Walk_2.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
Walk_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Walk_2.BorderSizePixel = 0
Walk_2.Position = UDim2.new(0.566899657, 0, 1.32123029, 0)
Walk_2.Size = UDim2.new(0.431235433, 0, 1, 0)
Walk_2.Font = Enum.Font.SourceSansBold
Walk_2.Text = "รีเซ็ท"
Walk_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Walk_2.TextScaled = true
Walk_2.TextSize = 14.000
Walk_2.TextWrapped = true

UICorner_7.Parent = Walk_2

TitleTime.Name = "TitleTime"
TitleTime.Parent = Background
TitleTime.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
TitleTime.BorderColor3 = Color3.fromRGB(0, 0, 0)
TitleTime.BorderSizePixel = 0
TitleTime.Position = UDim2.new(0.0285714287, 0, 0.828519106, 0)
TitleTime.Size = UDim2.new(0.945054948, 0, 0.0737410039, 0)
TitleTime.Font = Enum.Font.SourceSansBold
TitleTime.Text = "เวลาที่ใช้ 0:00"
TitleTime.TextColor3 = Color3.fromRGB(255, 255, 255)
TitleTime.TextScaled = true
TitleTime.TextSize = 14.000
TitleTime.TextWrapped = true
TitleTime.TextXAlignment = Enum.TextXAlignment.Left

UICorner_8.Parent = TitleTime

Toggle.Name = "Toggle"
Toggle.Parent = AegonaStore
Toggle.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Toggle.BackgroundTransparency = 1.000
Toggle.BorderColor3 = Color3.fromRGB(0, 0, 0)
Toggle.BorderSizePixel = 0
Toggle.Position = UDim2.new(0.0745179802, 0, 0.400370717, 0)
Toggle.Size = UDim2.new(0.0521104746, 0, 0.0926784053, 0)
Toggle.Visible = false
Toggle.Image = "rbxassetid://102792000981621"

SelectFrame.Name = "SelectFrame"
SelectFrame.Parent = AegonaStore
SelectFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
SelectFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
SelectFrame.BorderSizePixel = 0
SelectFrame.Position = UDim2.new(0.261000007, 0, -0.5, 0)
SelectFrame.Size = UDim2.new(0.477331936, 0, 0.351251155, 0)

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(0, 0, 0)), ColorSequenceKeypoint.new(0.50, Color3.fromRGB(44, 44, 44)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(0, 0, 0))}
UIGradient.Parent = SelectFrame

Title_2.Name = "Title"
Title_2.Parent = SelectFrame
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 0.650
Title_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title_2.BorderSizePixel = 0
Title_2.Position = UDim2.new(0.0174672492, 0, 0.0369393155, 0)
Title_2.Size = UDim2.new(0.966157198, 0, 0.19525066, 0)
Title_2.Font = Enum.Font.SourceSansBold
Title_2.Text = "เลือกโปร"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextScaled = true
Title_2.TextSize = 14.000
Title_2.TextWrapped = true

UICorner_9.Parent = Title_2

UICorner_10.Parent = SelectFrame

Title_3.Name = "Title"
Title_3.Parent = SelectFrame
Title_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_3.BackgroundTransparency = 0.650
Title_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title_3.BorderSizePixel = 0
Title_3.Position = UDim2.new(0.0163755454, 0, 0.2823219, 0)
Title_3.Size = UDim2.new(0.966157198, 0, 0.0976253301, 0)
Title_3.Font = Enum.Font.SourceSansBold
Title_3.Text = "Script ออนไลน์ 1 จาก 2 "
Title_3.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_3.TextScaled = true
Title_3.TextSize = 14.000
Title_3.TextWrapped = true

UICorner_11.Parent = Title_3

B.Name = "B"
B.Parent = SelectFrame
B.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
B.BackgroundTransparency = 0.650
B.BorderColor3 = Color3.fromRGB(0, 0, 0)
B.BorderSizePixel = 0
B.Position = UDim2.new(0.0174672492, 0, 0.416886538, 0)
B.Size = UDim2.new(0.965065479, 0, 0.52242744, 0)

UICorner_12.Parent = B

Button1.Name = "Button1"
Button1.Parent = B
Button1.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Button1.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button1.BorderSizePixel = 0
Button1.Position = UDim2.new(0.0203619916, 0, 0.0656565651, 0)
Button1.Size = UDim2.new(0.960407257, 0, 0.25252524, 0)
Button1.Font = Enum.Font.SourceSansBold
Button1.Text = "SCRIPT : โชค"
Button1.TextColor3 = Color3.fromRGB(255, 255, 255)
Button1.TextScaled = true
Button1.TextSize = 14.000
Button1.TextWrapped = true

UICorner_13.Parent = Button1

ImageLabel.Parent = Button1
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.944333613, 0, 0.234785154, 0)
ImageLabel.Size = UDim2.new(0.030624263, 0, 0.520000041, 0)
ImageLabel.Image = "rbxassetid://103785069"

Button2.Name = "Button2"
Button2.Parent = B
Button2.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Button2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Button2.BorderSizePixel = 0
Button2.Position = UDim2.new(0.0203619916, 0, 0.373737365, 0)
Button2.Size = UDim2.new(0.960407257, 0, 0.25252524, 0)
Button2.Font = Enum.Font.SourceSansBold
Button2.Text = "SCRIPT : นั่ง"
Button2.TextColor3 = Color3.fromRGB(255, 255, 255)
Button2.TextScaled = true
Button2.TextSize = 14.000
Button2.TextWrapped = true

UICorner_14.Parent = Button2

ImageLabel_2.Parent = Button2
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Position = UDim2.new(0.944333613, 0, 0.234785154, 0)
ImageLabel_2.Size = UDim2.new(0.030624263, 0, 0.520000041, 0)
ImageLabel_2.Image = "rbxassetid://103785069"
ImageLabel_2.ImageColor3 = Color3.fromRGB(255, 0, 0)

Background2.Name = "Background2"
Background2.Parent = AegonaStore
Background2.BackgroundColor3 = Color3.fromRGB(56, 56, 56)
Background2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Background2.BorderSizePixel = 0
Background2.Position = UDim2.new(0.381126165, 0, 0.242592588, 0)
Background2.Size = UDim2.new(0.237102658, 0, 0.515291929, 0)
Background2.Visible = false

UICorner_15.Parent = Background2

-- Scripts:

local function YTZVT_fake_script() -- TitleTime.LocalScript 
	local script = Instance.new('LocalScript', TitleTime)

	local textLabel = script.Parent
	
	while true do
	
		local currentTime = os.date("%H:%M:%S")
		textLabel.Text = "เวลาที่ใช้ : " .. currentTime
	
		task.wait(1) 
	end
	
end
coroutine.wrap(YTZVT_fake_script)()
local function VMSCHZA_fake_script() -- Background.Script 
	local script = Instance.new('Script', Background)

	local UIS = game:GetService("UserInputService")
	local frame = script.Parent
	
	local dragToggle = nil
	local dragSpeed = 0.1
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale,startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService("TweenService"):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
end
coroutine.wrap(VMSCHZA_fake_script)()
local function IZUCIJ_fake_script() -- Background.Main 
	local script = Instance.new('LocalScript', Background)

	script.Parent.TitleName.Text = game.Players.LocalPlayer.Name.." @"..game.Players.LocalPlayer.DisplayName
	
	script.Parent.Walk.MouseButton1Click:Connect(function()
		if script.Parent.Walk.TextBox.Text ~= "" or script.Parent.Walk.TextBox.Text ~= 0 then
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = script.Parent.Walk.TextBox.Text
		else
			game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
		end
	end)
	
	script.Parent.Walk.Walk.MouseButton1Click:Connect(function()
		script.Parent.Walk.TextBox.Text = "16"
		game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = 16
	end)
	
	
	
	
	
	local player = game.Players.LocalPlayer
	local character = player.Character or player.CharacterAdded:Wait()
	local noclip = false
	local connection
	
	
	local function enableNoclip()
		connection = game:GetService("RunService").Stepped:Connect(function()
			for _, part in pairs(character:GetDescendants()) do
				if part:IsA("BasePart") then
					part.CanCollide = false
				end
			end
		end)
	end
	
	
	local function disableNoclip()
		if connection then
			connection:Disconnect()
			connection = nil
		end
	end
	
	
	game:GetService("UserInputService").InputBegan:Connect(function(input, gpe)
		if gpe then return end
		if input.KeyCode == Enum.KeyCode.N then
			noclip = not noclip
			if noclip then
				enableNoclip()
				print("Noclip: ON")
			else
				disableNoclip()
				print("Noclip: OFF")
			end
		end
	end)
	
	script.Parent.Noclip.MouseButton1Click:Connect(function()
		noclip = not noclip
		if noclip then
			script.Parent.Noclip.Text = "ทะลุ : เปิด"
			enableNoclip()
		else
			
			script.Parent.Noclip.Text = "ทะลุ : ปิด"
			disableNoclip()
		end
	end)
end
coroutine.wrap(IZUCIJ_fake_script)()
local function DLQVS_fake_script() -- Toggle.LocalScript 
	local script = Instance.new('LocalScript', Toggle)

	
	
	script.Parent.MouseButton1Click:Connect(function()
		if selecting == 1 then
			script.Parent.Parent.Background.Visible = not script.Parent.Parent.Background.Visible
		elseif selecting == 2 then
			script.Parent.Parent.Background2.Visible = not script.Parent.Parent.Background2.Visible
		end
	end)
end
coroutine.wrap(DLQVS_fake_script)()
local function JTXH_fake_script() -- SelectFrame.Main 
	local script = Instance.new('LocalScript', SelectFrame)

	local Blur = Instance.new("BlurEffect")
	Blur.Parent = game.Lighting
	
	local Background = script.Parent
	local BackgroundScript1 = script.Parent.Parent.Background
	local BackgroundScript2 = script.Parent.Parent.Background2
	
	
	
	Background:TweenPosition(UDim2.new(0.261, 0,0.324, 0),Enum.EasingDirection.In,Enum.EasingStyle.Back,0.4)
	
	wait(1)
	
	script.Parent.B.Button1.MouseButton1Click:Connect(function()
		selecting = 1
		script.Parent.Parent.Toggle.Visible = true
		Background.Visible = false
		wait(3)
		Blur:Destroy()
		BackgroundScript1.Visible = true
		BackgroundScript2:Destroy()
		Background:Destroy()
	end)
	
	script.Parent.B.Button2.MouseButton1Click:Connect(function()
		script.Parent.Parent.Toggle.Visible = true
		selecting = 2
		Background.Visible = false
		wait(3)
		Blur:Destroy()
		BackgroundScript2.Visible = true
		BackgroundScript1:Destroy()
		Background:Destroy()
		
		game.Players.LocalPlayer:Kick("script ยังไม่เสร็จ รอก่อนนน!!")
	end)
end
coroutine.wrap(JTXH_fake_script)()
local function THMZCBG_fake_script() -- Background2.Script 
	local script = Instance.new('Script', Background2)

	local UIS = game:GetService("UserInputService")
	local frame = script.Parent
	
	local dragToggle = nil
	local dragSpeed = 0.1
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale,startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService("TweenService"):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
	end
	
	frame.InputBegan:Connect(function(input)
		if (input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch) then
			dragToggle = true
			dragStart = input.Position
			startPos = frame.Position
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragToggle = false
				end
			end)
		end
	end)
	
	UIS.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			if dragToggle then
				updateInput(input)
			end
		end
	end)
	
end
coroutine.wrap(THMZCBG_fake_script)()
