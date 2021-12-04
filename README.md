-- Gui to Lua
-- Version: 3.2

-- Instances:

local Password = Instance.new("ScreenGui")
local Title = Instance.new("Frame")
local elements = Instance.new("Frame")
local title = Instance.new("TextBox")
local UICorner = Instance.new("UICorner")
local underline = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local button = Instance.new("TextButton")
local underline_2 = Instance.new("Frame")
local nameTXT = Instance.new("TextLabel")

--Properties:

Password.Name = "Password"
Password.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
Password.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Title.Name = "Title"
Title.Parent = Password
Title.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.378299862, 0, 0.358461797, 0)
Title.Size = UDim2.new(0.24248302, 0, 0.0368188508, 0)

elements.Name = "elements"
elements.Parent = Title
elements.BackgroundColor3 = Color3.fromRGB(34, 32, 34)
elements.BorderSizePixel = 0
elements.Position = UDim2.new(0, 0, 1.08000004, 0)
elements.Size = UDim2.new(1, 0, 5.62417746, 0)

title.Name = "title"
title.Parent = elements
title.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
title.BorderSizePixel = 0
title.Position = UDim2.new(0.0480000004, 0, 0.177803785, 0)
title.Size = UDim2.new(0.899999976, 0, 0.355607569, 0)
title.Font = Enum.Font.SourceSans
title.PlaceholderColor3 = Color3.fromRGB(34, 32, 34)
title.PlaceholderText = "Insert password..."
title.Text = ""
title.TextColor3 = Color3.fromRGB(255, 255, 255)
title.TextScaled = true
title.TextSize = 14.000
title.TextWrapped = true

UICorner.Parent = title

underline.Name = "underline"
underline.Parent = elements
underline.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
underline.BorderSizePixel = 0
underline.Position = UDim2.new(0.25999999, 0, 0.665728867, 0)
underline.Size = UDim2.new(0.479343265, 0, 0.257803798, 0)

UICorner_2.Parent = underline

button.Name = "button"
button.Parent = underline
button.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
button.BackgroundTransparency = 1.000
button.Position = UDim2.new(-2.98023224e-08, 0, 0, 0)
button.Size = UDim2.new(1, 0, 1, 0)
button.Font = Enum.Font.GothamSemibold
button.Text = "ENTER"
button.TextColor3 = Color3.fromRGB(53, 49, 49)
button.TextSize = 20.000

underline_2.Name = "underline"
underline_2.Parent = Title
underline_2.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
underline_2.BorderSizePixel = 0
underline_2.Position = UDim2.new(0, 0, 1, 0)
underline_2.Size = UDim2.new(1, 0, 0.0799999982, 0)

nameTXT.Name = "nameTXT"
nameTXT.Parent = Title
nameTXT.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT.BackgroundTransparency = 1.000
nameTXT.Selectable = true
nameTXT.Size = UDim2.new(1, 0, 1, 0)
nameTXT.Font = Enum.Font.GothamSemibold
nameTXT.Text = "ALF EXPLOITS"
nameTXT.TextColor3 = Color3.fromRGB(255, 255, 255)
nameTXT.TextSize = 20.000

-- Scripts:

local function PLUAFS_fake_script() -- Title.LocalScript 
	local script = Instance.new('LocalScript', Title)

	local amongus = script.Parent.elements.title
	local enter = script.Parent.elements.underline.button
	
	enter.MouseButton1Click:Connect(function()
		if amongus.Text == "passypassword" then
			loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua", true))()
		end
	end)
end
coroutine.wrap(PLUAFS_fake_script)()
