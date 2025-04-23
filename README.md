
local player = game.Players.LocalPlayer
local screenGui = Instance.new("ScreenGui")
screenGui.Parent = player.PlayerGui
screenGui.Name = "7maestroGUI"

local frame = Instance.new("Frame")
frame.Parent = screenGui
frame.Size = UDim2.new(0, 500, 0, 500)  -- Ajustando o tamanho do frame para ficar mais compacto
frame.Position = UDim2.new(0.5, -250, 0.5, -250)
frame.BackgroundColor3 = Color3.fromRGB(20, 20, 20)
frame.BorderSizePixel = 0
frame.AnchorPoint = Vector2.new(0.5, 0.5)
frame.BackgroundTransparency = 0.2

local title = Instance.new("TextLabel")
title.Parent = frame
title.Size = UDim2.new(1, 0, 0, 50)
title.BackgroundTransparency = 1
title.Text = "7maestro - Blox Fruits"
title.TextColor3 = Color3.fromRGB(255, 0, 0)  -- Cor do título (vermelho)
title.TextSize = 30
title.TextAlign = Enum.TextXAlignment.Center
title.Font = Enum.Font.GothamBold
title.TextStrokeTransparency = 0.8
title.TextStrokeColor3 = Color3.fromRGB(255, 255, 255)
