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
local incorrect = Instance.new("Frame")
local elements_2 = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local underline_3 = Instance.new("Frame")
local nameTXT_2 = Instance.new("TextLabel")
local correct = Instance.new("Frame")
local elements_3 = Instance.new("Frame")
local TextLabel_2 = Instance.new("TextLabel")
local underline_4 = Instance.new("Frame")
local nameTXT_3 = Instance.new("TextLabel")

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

incorrect.Name = "incorrect"
incorrect.Parent = Password
incorrect.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
incorrect.BorderSizePixel = 0
incorrect.Position = UDim2.new(-0.25, 0, 0.84447068, 0)
incorrect.Size = UDim2.new(0.24248302, 0, 0.0368188508, 0)
incorrect.ZIndex = 2

elements_2.Name = "elements"
elements_2.Parent = incorrect
elements_2.BackgroundColor3 = Color3.fromRGB(34, 32, 34)
elements_2.BorderSizePixel = 0
elements_2.Position = UDim2.new(0, 0, 1.08000124, 0)
elements_2.Size = UDim2.new(1, 0, 2.34417725, 0)

TextLabel.Parent = elements_2
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Size = UDim2.new(1, 0, 1, 0)
TextLabel.Font = Enum.Font.GothamSemibold
TextLabel.Text = "Password is incorrect."
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 20.000

underline_3.Name = "underline"
underline_3.Parent = incorrect
underline_3.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
underline_3.BorderSizePixel = 0
underline_3.Position = UDim2.new(0, 0, 1, 0)
underline_3.Size = UDim2.new(1, 0, 0.0799999982, 0)

nameTXT_2.Name = "nameTXT"
nameTXT_2.Parent = incorrect
nameTXT_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_2.BackgroundTransparency = 1.000
nameTXT_2.Selectable = true
nameTXT_2.Size = UDim2.new(1, 0, 1, 0)
nameTXT_2.Font = Enum.Font.GothamSemibold
nameTXT_2.Text = "INCORRECT PASSWORD"
nameTXT_2.TextColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_2.TextSize = 20.000

correct.Name = "correct"
correct.Parent = Password
correct.BackgroundColor3 = Color3.fromRGB(53, 49, 49)
correct.BorderSizePixel = 0
correct.Position = UDim2.new(-0.25, 0, 0.84447068, 0)
correct.Size = UDim2.new(0.24248302, 0, 0.0368188508, 0)
correct.ZIndex = 2

elements_3.Name = "elements"
elements_3.Parent = correct
elements_3.BackgroundColor3 = Color3.fromRGB(34, 32, 34)
elements_3.BorderSizePixel = 0
elements_3.Position = UDim2.new(0, 0, 1.08000124, 0)
elements_3.Size = UDim2.new(1, 0, 2.34417725, 0)

TextLabel_2.Parent = elements_3
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.Size = UDim2.new(1, 0, 1, 0)
TextLabel_2.Font = Enum.Font.GothamSemibold
TextLabel_2.Text = "Password is correct."
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 20.000

underline_4.Name = "underline"
underline_4.Parent = correct
underline_4.BackgroundColor3 = Color3.fromRGB(0, 255, 140)
underline_4.BorderSizePixel = 0
underline_4.Position = UDim2.new(0, 0, 1, 0)
underline_4.Size = UDim2.new(1, 0, 0.0799999982, 0)

nameTXT_3.Name = "nameTXT"
nameTXT_3.Parent = correct
nameTXT_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_3.BackgroundTransparency = 1.000
nameTXT_3.Selectable = true
nameTXT_3.Size = UDim2.new(1, 0, 1, 0)
nameTXT_3.Font = Enum.Font.GothamSemibold
nameTXT_3.Text = "CORRECT PASSWORD"
nameTXT_3.TextColor3 = Color3.fromRGB(255, 255, 255)
nameTXT_3.TextSize = 20.000

-- Scripts:

local function EAQOI_fake_script() -- Title.LocalScript 
	local script = Instance.new('LocalScript', Title)

	local amongus = script.Parent.elements.title
	local enter = script.Parent.elements.underline.button
	local incorrect = script.Parent.Parent.incorrect
	local correct = script.Parent.Parent.correct
	
	enter.MouseButton1Click:Connect(function()
		if amongus.Text == "passypassword" then
			correct:TweenPosition(UDim2.new(0.024, 0,0.844, 0), "Out", "Back", 1, true)
			wait(2)
			correct:TweenPosition(UDim2.new(-0.25, 0,0.844, 0), "In", "Back", 1, true)
			loadstring(game:HttpGet("https://raw.githubusercontent.com/fatesc/fates-admin/main/main.lua", true))()
			wait(1)
			script.Parent.Parent:Destroy()
		else
			incorrect:TweenPosition(UDim2.new(0.024, 0,0.844, 0), "Out", "Back", 1, true)
			wait(2)
			incorrect:TweenPosition(UDim2.new(-0.25, 0,0.844, 0), "In", "Back", 1, true)
		end
	end)
end
coroutine.wrap(EAQOI_fake_script)()
