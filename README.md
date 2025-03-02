local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local ESPButton = Instance.new("TextButton")
local AimbotButton = Instance.new("TextButton")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
Frame.Size = UDim2.new(0, 200, 0, 100)
Frame.Position = UDim2.new(0.5, -100, 0.5, -50)

ESPButton.Parent = Frame
ESPButton.BackgroundColor3 = Color3.fromRGB(255, 0, 0)
ESPButton.Size = UDim2.new(1, 0, 0, 50)
ESPButton.Text = "ESP"
ESPButton.TextColor3 = Color3.fromRGB(255, 255, 255)

AimbotButton.Parent = Frame
AimbotButton.BackgroundColor3 = Color3.fromRGB(0, 0, 255)
AimbotButton.Size = UDim2.new(1, 0, 0, 50)
AimbotButton.Position = UDim2.new(0, 0, 0, 50)
AimbotButton.Text = "Aimbot"
AimbotButton.TextColor3 = Color3.fromRGB(255, 255, 255)

local function toggleESP()
    -- Lógica para ativar/desativar ESP
end

local function toggleAimbot()
    -- Lógica para ativar/desativar Aimbot
end

ESPButton.MouseButton1Click:Connect(toggleESP)
AimbotButton.MouseButton1Click:Connect(toggleAimbot)
