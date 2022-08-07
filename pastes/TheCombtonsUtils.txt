-- loadstring(game:HttpGet(('https://https://darkwoid.github.io/pastes/TheCombtonsUtils'),true))()

-- TheCombton's utilities
-- Made by TheCombton

-- Instances:

local TheCombtonsutilities = Instance.new("ScreenGui")
local MainFrame = Instance.new("Frame")
local TopBar = Instance.new("TextLabel")
local ResetButton = Instance.new("TextButton")
local IYButton = Instance.new("TextButton")
local UESPButton = Instance.new("TextButton")
local CloseButton = Instance.new("ImageButton")
local QuandaleESPButton = Instance.new("TextButton")
local ESPLine = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local OpenButton = Instance.new("TextButton")

--Properties:

TheCombtonsutilities.Name = "TheCombton's utilities"
TheCombtonsutilities.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
TheCombtonsutilities.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
TheCombtonsutilities.ResetOnSpawn = false

MainFrame.Name = "MainFrame"
MainFrame.Parent = TheCombtonsutilities
MainFrame.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
MainFrame.Position = UDim2.new(0.565280795, 0, 0.623312891, 0)
MainFrame.Size = UDim2.new(0, 569, 0, 293)
MainFrame.Visible = false

TopBar.Name = "TopBar"
TopBar.Parent = MainFrame
TopBar.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
TopBar.Size = UDim2.new(0, 569, 0, 42)
TopBar.Font = Enum.Font.Roboto
TopBar.Text = "TheCombton's utilities"
TopBar.TextColor3 = Color3.fromRGB(255, 255, 255)
TopBar.TextScaled = true
TopBar.TextSize = 14.000
TopBar.TextWrapped = true

ResetButton.Name = "ResetButton"
ResetButton.Parent = MainFrame
ResetButton.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
ResetButton.Position = UDim2.new(0.0389424711, 0, 0.259301305, 0)
ResetButton.Size = UDim2.new(0, 148, 0, 141)
ResetButton.Font = Enum.Font.SourceSans
ResetButton.Text = "Reset Character"
ResetButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ResetButton.TextScaled = true
ResetButton.TextSize = 14.000
ResetButton.TextWrapped = true

IYButton.Name = "IYButton"
IYButton.Parent = MainFrame
IYButton.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
IYButton.Position = UDim2.new(0.369346678, 0, 0.259301305, 0)
IYButton.Size = UDim2.new(0, 148, 0, 141)
IYButton.Font = Enum.Font.SourceSans
IYButton.Text = "Infinite Yield"
IYButton.TextColor3 = Color3.fromRGB(255, 255, 255)
IYButton.TextScaled = true
IYButton.TextSize = 14.000
IYButton.TextWrapped = true

UESPButton.Name = "UESPButton"
UESPButton.Parent = MainFrame
UESPButton.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
UESPButton.Position = UDim2.new(0.705023229, 0, 0.259301305, 0)
UESPButton.Size = UDim2.new(0, 148, 0, 46)
UESPButton.Font = Enum.Font.SourceSans
UESPButton.Text = "Unnamed ESP"
UESPButton.TextColor3 = Color3.fromRGB(255, 255, 255)
UESPButton.TextScaled = true
UESPButton.TextSize = 14.000
UESPButton.TextWrapped = true

CloseButton.Name = "CloseButton"
CloseButton.Parent = MainFrame
CloseButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
CloseButton.BorderSizePixel = 0
CloseButton.Position = UDim2.new(0.919156432, 0, 0, 0)
CloseButton.Size = UDim2.new(0, 46, 0, 42)
CloseButton.Image = "rbxassetid://8039204542"

QuandaleESPButton.Name = "QuandaleESPButton"
QuandaleESPButton.Parent = MainFrame
QuandaleESPButton.BackgroundColor3 = Color3.fromRGB(48, 48, 48)
QuandaleESPButton.Position = UDim2.new(0.705023229, 0, 0.583533406, 0)
QuandaleESPButton.Size = UDim2.new(0, 148, 0, 46)
QuandaleESPButton.Font = Enum.Font.SourceSans
QuandaleESPButton.Text = "Quandale ESP"
QuandaleESPButton.TextColor3 = Color3.fromRGB(255, 255, 255)
QuandaleESPButton.TextScaled = true
QuandaleESPButton.TextSize = 14.000
QuandaleESPButton.TextWrapped = true

ESPLine.Name = "ESPLine"
ESPLine.Parent = MainFrame
ESPLine.BackgroundColor3 = Color3.fromRGB(36, 36, 36)
ESPLine.BorderSizePixel = 0
ESPLine.Position = UDim2.new(0.690685391, 0, 0.487970263, 0)
ESPLine.Size = UDim2.new(0, 163, 0, 7)

UICorner.Parent = ESPLine

OpenButton.Name = "OpenButton"
OpenButton.Parent = TheCombtonsutilities
OpenButton.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
OpenButton.Position = UDim2.new(0, 0, 0.969325185, 0)
OpenButton.Size = UDim2.new(0, 265, 0, 25)
OpenButton.Font = Enum.Font.RobotoMono
OpenButton.Text = "TheCombton's utilities"
OpenButton.TextColor3 = Color3.fromRGB(238, 238, 238)
OpenButton.TextScaled = true
OpenButton.TextSize = 14.000
OpenButton.TextWrapped = true

-- Scripts:

local function SHLYCY_fake_script() -- ResetButton.ResetButtonScript 
	local script = Instance.new('LocalScript', ResetButton)

	script.Parent.MouseButton1Click:Connect(function()
		game.Players.LocalPlayer.Character.Humanoid.Health = 0
	end)
end
coroutine.wrap(SHLYCY_fake_script)()
local function BWUIJU_fake_script() -- IYButton.IYButtonScript 
	local script = Instance.new('LocalScript', IYButton)

	IYButton.MouseButton1Down:connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
	end)
end
coroutine.wrap(BWUIJU_fake_script)()
local function CILHFY_fake_script() -- UESPButton.LocalScript 
	local script = Instance.new('LocalScript', UESPButton)

	UESPButton.MouseButton1Down:connect(function()
		loadstring(game:HttpGet('https://raw.githubusercontent.com/ic3w0lf22/Unnamed-ESP/master/UnnamedESP.lua'))()
	end)
end
coroutine.wrap(CILHFY_fake_script)()
local function KQBLUPA_fake_script() -- MainFrame.Dragify 
	local script = Instance.new('LocalScript', MainFrame)

	local UserInputService = game:GetService("UserInputService")
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	local function update(input)
		local delta = input.Position - dragStart
		gui.Position = UDim2.new(startPos.X.Scale, startPos.X.Offset + delta.X, startPos.Y.Scale, startPos.Y.Offset + delta.Y)
	end
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	UserInputService.InputChanged:Connect(function(input)
		if input == dragInput and dragging then
			update(input)
		end
	end)
end
coroutine.wrap(KQBLUPA_fake_script)()
local function CNZQXK_fake_script() -- CloseButton.CloseButtonScript 
	local script = Instance.new('LocalScript', CloseButton)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui["TheCombton's utilities"].MainFrame.Visible = false
		player.PlayerGui["TheCombton's utilities"].OpenButton.Visible = true
	end)
	
end
coroutine.wrap(CNZQXK_fake_script)()
local function JAJG_fake_script() -- QuandaleESPButton.LocalScript 
	local script = Instance.new('LocalScript', QuandaleESPButton)

	QuandaleESPButton.MouseButton1Down:connect(function()
		loadstring(game:HttpGet("https://raw.githubusercontent.com/cueshut/saves/main/quandale", true))()
	end)
end
coroutine.wrap(JAJG_fake_script)()
local function JBPI_fake_script() -- OpenButton.OpenButtonScript 
	local script = Instance.new('LocalScript', OpenButton)

	local player = game.Players.LocalPlayer
	
	script.Parent.MouseButton1Click:Connect(function()
		player.PlayerGui["TheCombton's utilities"].MainFrame.Visible = true
		player.PlayerGui["TheCombton's utilities"].OpenButton.Visible = false
	end)
	
end
coroutine.wrap(JBPI_fake_script)()
