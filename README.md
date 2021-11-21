-- Gui to Lua
-- Version: 3.2

-- Instances:

local Frame1 = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local ODHC = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local ODHC_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local UIGradient_2 = Instance.new("UIGradient")
local UIGradient_3 = Instance.new("UIGradient")
local TextBoxes = Instance.new("TextBox")
local UICorner_4 = Instance.new("UICorner")
local HelpButton = Instance.new("TextButton")
local UIGradient_4 = Instance.new("UIGradient")
local UICorner_5 = Instance.new("UICorner")
local StartButton = Instance.new("TextButton")
local UIGradient_5 = Instance.new("UIGradient")
local UICorner_6 = Instance.new("UICorner")
local CreditsLabel = Instance.new("TextLabel")
local UICorner_7 = Instance.new("UICorner")
local CreditsLabel_2 = Instance.new("TextLabel")
local UICorner_8 = Instance.new("UICorner")
local ODHC_3 = Instance.new("TextLabel")
local UICorner_9 = Instance.new("UICorner")
local UIGradient_6 = Instance.new("UIGradient")

--Properties:

Frame1.Name = "Frame1"
Frame1.Parent = game.StarterGui.ODHC Crash
Frame1.BackgroundColor3 = Color3.fromRGB(34, 34, 34)
Frame1.Position = UDim2.new(0.0214564204, 0, 0.0392637998, 0)
Frame1.Size = UDim2.new(0, 285, 0, 464)

UICorner.Parent = Frame1

ODHC.Name = "ODHC"
ODHC.Parent = Frame1
ODHC.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
ODHC.BackgroundTransparency = 1.000
ODHC.Size = UDim2.new(0, 122, 0, 50)
ODHC.Font = Enum.Font.SourceSansBold
ODHC.Text = "ODHC"
ODHC.TextColor3 = Color3.fromRGB(255, 255, 255)
ODHC.TextScaled = true
ODHC.TextSize = 14.000
ODHC.TextWrapped = true

UICorner_2.Parent = ODHC

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(56, 56, 56)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(171, 171, 171))}
UIGradient.Parent = ODHC

ODHC_2.Name = "ODHC"
ODHC_2.Parent = Frame1
ODHC_2.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
ODHC_2.BackgroundTransparency = 1.000
ODHC_2.Position = UDim2.new(0.0282658618, 0, 0.0668103471, 0)
ODHC_2.Size = UDim2.new(0, 107, 0, 42)
ODHC_2.Font = Enum.Font.SourceSansBold
ODHC_2.Text = "▬▬▬▬"
ODHC_2.TextColor3 = Color3.fromRGB(255, 255, 255)
ODHC_2.TextScaled = true
ODHC_2.TextSize = 14.000
ODHC_2.TextWrapped = true

UICorner_3.Parent = ODHC_2

UIGradient_2.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(56, 56, 56)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(171, 171, 171))}
UIGradient_2.Parent = ODHC_2

UIGradient_3.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(255, 255, 255)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(98, 98, 98))}
UIGradient_3.Parent = Frame1

TextBoxes.Name = "TextBoxes"
TextBoxes.Parent = Frame1
TextBoxes.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
TextBoxes.Position = UDim2.new(0.0736842155, 0, 0.267780155, 0)
TextBoxes.Size = UDim2.new(0, 243, 0, 60)
TextBoxes.Font = Enum.Font.SourceSansBold
TextBoxes.PlaceholderText = "Flowers - NIL"
TextBoxes.Text = ""
TextBoxes.TextColor3 = Color3.fromRGB(255, 255, 255)
TextBoxes.TextScaled = true
TextBoxes.TextSize = 14.000
TextBoxes.TextWrapped = true

UICorner_4.Parent = TextBoxes

HelpButton.Name = "HelpButton"
HelpButton.Parent = Frame1
HelpButton.BackgroundColor3 = Color3.fromRGB(195, 0, 0)
HelpButton.Position = UDim2.new(0.491228074, 0, 0.0172413457, 0)
HelpButton.Size = UDim2.new(0, 139, 0, 50)
HelpButton.Font = Enum.Font.SourceSansBold
HelpButton.Text = "HELP"
HelpButton.TextColor3 = Color3.fromRGB(0, 0, 0)
HelpButton.TextScaled = true
HelpButton.TextSize = 14.000
HelpButton.TextWrapped = true

UIGradient_4.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(162, 0, 0)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(255, 0, 0))}
UIGradient_4.Parent = HelpButton

UICorner_5.Parent = HelpButton

StartButton.Name = "StartButton"
StartButton.Parent = Frame1
StartButton.BackgroundColor3 = Color3.fromRGB(65, 195, 0)
StartButton.Position = UDim2.new(0.0736842081, 0, 0.853448272, 0)
StartButton.Size = UDim2.new(0, 243, 0, 50)
StartButton.Font = Enum.Font.SourceSansBold
StartButton.Text = "START"
StartButton.TextColor3 = Color3.fromRGB(0, 0, 0)
StartButton.TextScaled = true
StartButton.TextSize = 14.000
StartButton.TextWrapped = true

UIGradient_5.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(34, 91, 10)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(145, 255, 0))}
UIGradient_5.Parent = StartButton

UICorner_6.Parent = StartButton

CreditsLabel.Name = "CreditsLabel"
CreditsLabel.Parent = Frame1
CreditsLabel.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
CreditsLabel.Position = UDim2.new(0.0736842081, 0, 0.581896544, 0)
CreditsLabel.Size = UDim2.new(0, 243, 0, 39)
CreditsLabel.Font = Enum.Font.SourceSansBold
CreditsLabel.Text = "CREDITS:"
CreditsLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsLabel.TextScaled = true
CreditsLabel.TextSize = 14.000
CreditsLabel.TextWrapped = true

UICorner_7.Parent = CreditsLabel

CreditsLabel_2.Name = "CreditsLabel"
CreditsLabel_2.Parent = Frame1
CreditsLabel_2.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
CreditsLabel_2.Position = UDim2.new(0.0736842081, 0, 0.685344815, 0)
CreditsLabel_2.Size = UDim2.new(0, 243, 0, 67)
CreditsLabel_2.Font = Enum.Font.SourceSansBold
CreditsLabel_2.Text = "oscar#0002 OscarDosk1YT"
CreditsLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
CreditsLabel_2.TextScaled = true
CreditsLabel_2.TextSize = 14.000
CreditsLabel_2.TextWrapped = true

UICorner_8.Parent = CreditsLabel_2

ODHC_3.Name = "ODHC"
ODHC_3.Parent = Frame1
ODHC_3.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
ODHC_3.BackgroundTransparency = 1.000
ODHC_3.Position = UDim2.new(0.196686924, 0, 0.157327592, 0)
ODHC_3.Size = UDim2.new(0, 172, 0, 67)
ODHC_3.Font = Enum.Font.SourceSansBold
ODHC_3.Text = "▬ INPUT ▬"
ODHC_3.TextColor3 = Color3.fromRGB(255, 255, 255)
ODHC_3.TextScaled = true
ODHC_3.TextSize = 14.000
ODHC_3.TextWrapped = true

UICorner_9.Parent = ODHC_3

UIGradient_6.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(56, 56, 56)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(171, 171, 171))}
UIGradient_6.Parent = ODHC_3

-- Scripts:

local function MXMHJ_fake_script() -- HelpButton.LocalScript 
	local script = Instance.new('LocalScript', HelpButton)

	local frame2 = game.StarterGui["ODHC Crash"].Frame2
	local frame1 = game.StarterGui["ODHC Crash"].Frame1
	local helpButton = game.StarterGui["ODHC Crash"].Frame1.HelpButton
	local plr = game.Players.LocalPlayer
	
	local function(player(open)
		if plr.HelpButton == true then
	)
end
coroutine.wrap(MXMHJ_fake_script)()
local function CWLRM_fake_script() -- Frame1.Movement 
	local script = Instance.new('LocalScript', Frame1)

	local UIS = game:GetService('UserInputService')
	local frame = script.Parent
	local dragToggle = nil
	local dragSpeed = 0.25
	local dragStart = nil
	local startPos = nil
	
	local function updateInput(input)
		local delta = input.Position - dragStart
		local position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X,
			startPos.Y.Scale, startPos.Y.Offset + delta.Y)
		game:GetService('TweenService'):Create(frame, TweenInfo.new(dragSpeed), {Position = position}):Play()
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
coroutine.wrap(CWLRM_fake_script)()
