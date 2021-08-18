-- Gui to Lua
-- Version: 3.2

-- Instances:

local Gui = Instance.new("ScreenGui")
local TextButton = Instance.new("TextButton")
local UICorner = Instance.new("UICorner")
local Frame = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Label = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Bloxfruit = Instance.new("TextButton")
local UICorner_4 = Instance.new("UICorner")
local Arsenal = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local Murder = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local RobloxUno = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local FunkyFriday = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local FleetheFacility = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local RoBeats = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")

--Properties:

Gui.Name = "Gui"
Gui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Gui.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

TextButton.Parent = Gui
TextButton.BackgroundColor3 = Color3.fromRGB(239, 53, 255)
TextButton.Position = UDim2.new(0, 0, 0.355389029, 0)
TextButton.Size = UDim2.new(0, 118, 0, 32)
TextButton.Font = Enum.Font.Bodoni
TextButton.Text = "Abrir/Fecha"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextScaled = true
TextButton.TextSize = 14.000
TextButton.TextWrapped = true

UICorner.Parent = TextButton

Frame.Parent = Gui
Frame.BackgroundColor3 = Color3.fromRGB(70, 0, 1)
Frame.Position = UDim2.new(0.262379915, 0, 0.273722708, 0)
Frame.Size = UDim2.new(0, 784, 0, 339)

UICorner_2.Parent = Frame

Label.Name = "Label"
Label.Parent = Frame
Label.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Label.Size = UDim2.new(0, 784, 0, 50)
Label.Font = Enum.Font.SourceSans
Label.Text = "Criador: Kaudrango"
Label.TextColor3 = Color3.fromRGB(16, 255, 24)
Label.TextScaled = true
Label.TextSize = 14.000
Label.TextWrapped = true

UICorner_3.Parent = Label

Bloxfruit.Name = "Blox fruit"
Bloxfruit.Parent = Frame
Bloxfruit.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
Bloxfruit.BorderColor3 = Color3.fromRGB(167, 44, 255)
Bloxfruit.Position = UDim2.new(0, 0, 0.238938063, 0)
Bloxfruit.Size = UDim2.new(0, 200, 0, 50)
Bloxfruit.Font = Enum.Font.SciFi
Bloxfruit.Text = "Blox  fruit"
Bloxfruit.TextColor3 = Color3.fromRGB(0, 0, 0)
Bloxfruit.TextScaled = true
Bloxfruit.TextSize = 14.000
Bloxfruit.TextWrapped = true

UICorner_4.Parent = Bloxfruit
Bloxfruit.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://gist.githubusercontent.com/noob1ee1/5607f21c9874e3724f13a88109916896/raw/5a44dc988657f4eb23294b60aa64b874bc13253b"))()
end)

Arsenal.Name = "Arsenal"
Arsenal.Parent = Frame
Arsenal.BackgroundColor3 = Color3.fromRGB(62, 49, 255)
Arsenal.Position = UDim2.new(0.372448981, 0, 0.238938063, 0)
Arsenal.Size = UDim2.new(0, 200, 0, 50)
Arsenal.Font = Enum.Font.SciFi
Arsenal.Text = "Arsenal"
Arsenal.TextColor3 = Color3.fromRGB(0, 0, 0)
Arsenal.TextScaled = true
Arsenal.TextSize = 14.000
Arsenal.TextWrapped = true

UICorner_5.Parent = Arsenal
Arsenal.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://athoi21.xyz/owlhub"))();
end)

Murder.Name = "Murder"
Murder.Parent = Frame
Murder.BackgroundColor3 = Color3.fromRGB(226, 255, 34)
Murder.Position = UDim2.new(0.743622422, 0, 0.238938063, 0)
Murder.Size = UDim2.new(0, 200, 0, 50)
Murder.Font = Enum.Font.SciFi
Murder.Text = "Murder"
Murder.TextColor3 = Color3.fromRGB(0, 0, 0)
Murder.TextScaled = true
Murder.TextSize = 14.000
Murder.TextWrapped = true

UICorner_6.Parent = Murder
Murder.MouseButton1Down:connect(function()
	loadstring(game:GetObjects("rbxassetid://4001118261")[1].Source)()
end)

RobloxUno.Name = "Roblox Uno"
RobloxUno.Parent = Frame
RobloxUno.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
RobloxUno.Position = UDim2.new(0, 0, 0.386430681, 0)
RobloxUno.Size = UDim2.new(0, 200, 0, 50)
RobloxUno.Font = Enum.Font.SciFi
RobloxUno.Text = "Roblox uno"
RobloxUno.TextColor3 = Color3.fromRGB(0, 0, 0)
RobloxUno.TextScaled = true
RobloxUno.TextSize = 14.000
RobloxUno.TextWrapped = true

UICorner_7.Parent = RobloxUno
RobloxUno.MouseButton1Down:connect(function()
	plus4Cards = true
	wildCards = true
	actionCards = true
	autoJoinMatch = false
	autoCreateAI = false
	autoCreateMatch = false
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Skribb11es/Random-Releases/main/UNOBOT", true))()
end)

FunkyFriday.Name = "Funky Friday"
FunkyFriday.Parent = Frame
FunkyFriday.BackgroundColor3 = Color3.fromRGB(218, 70, 255)
FunkyFriday.Position = UDim2.new(0.744897962, 0, 0.386430681, 0)
FunkyFriday.Size = UDim2.new(0, 200, 0, 50)
FunkyFriday.Font = Enum.Font.SciFi
FunkyFriday.Text = "Funky Friday"
FunkyFriday.TextColor3 = Color3.fromRGB(0, 0, 0)
FunkyFriday.TextScaled = true
FunkyFriday.TextSize = 14.000
FunkyFriday.TextWrapped = true

UICorner_8.Parent = FunkyFriday
FunkyFriday.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/wally-rblx/funky-friday-autoplay/main/main.lua",true))()
end)

FleetheFacility.Name = "Flee the Facility"
FleetheFacility.Parent = Frame
FleetheFacility.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
FleetheFacility.Position = UDim2.new(0.372448981, 0, 0.386430681, 0)
FleetheFacility.Size = UDim2.new(0, 200, 0, 50)
FleetheFacility.Font = Enum.Font.SciFi
FleetheFacility.Text = "Flee the Facility"
FleetheFacility.TextColor3 = Color3.fromRGB(255, 255, 255)
FleetheFacility.TextScaled = true
FleetheFacility.TextSize = 14.000
FleetheFacility.TextWrapped = true

UICorner_9.Parent = FleetheFacility
FleetheFacility.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/khoaScript/scripts/master/flee-the-facility.lua"))()
end)

RoBeats.Name = "RoBeats!"
RoBeats.Parent = Frame
RoBeats.BackgroundColor3 = Color3.fromRGB(83, 83, 83)
RoBeats.Position = UDim2.new(0.372448981, 0, 0.530973494, 0)
RoBeats.Size = UDim2.new(0, 200, 0, 50)
RoBeats.Font = Enum.Font.SciFi
RoBeats.Text = "RoBeats!"
RoBeats.TextColor3 = Color3.fromRGB(255, 255, 255)
RoBeats.TextScaled = true
RoBeats.TextSize = 14.000
RoBeats.TextWrapped = true

UICorner_10.Parent = RoBeats
RoBeats.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/notclosure/new-years/main/happ.lua"))()
end)

-- Scripts:

local function DPKILH_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Click:Connect(function()
		if script.Parent.Parent.Frame.Visible == false then
			script.Parent.Parent.Frame.Visible = true
		else
			script.Parent.Parent.Frame.Visible = false
		end
	end)
end
coroutine.wrap(DPKILH_fake_script)()
local function CEIK_fake_script() -- Gui.Script 
	local script = Instance.new('Script', Gui)

	frame = script.Parent.Frame -- Take out {}s, and put name of frame
	frame.Draggable = true
	frame.Active = true
	frame.Selectable = true
end
coroutine.wrap(CEIK_fake_script)()
local function PEIAOLZ_fake_script() -- Gui.Script 
	local script = Instance.new('Script', Gui)

	TextButton = script.Parent.TextButton -- Take out {}s, and put name of frame
	TextButton.Draggable = true
	TextButton.Active = true
	TextButton.Selectable = true
end
coroutine.wrap(PEIAOLZ_fake_script)()
