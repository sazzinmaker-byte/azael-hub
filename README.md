-- Menu Base - Exemplo GUI para Roblox (Krnl)
-- Criado apenas como exemplo educativo

-- Criando a ScreenGui
local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")

-- Botões
local AimbotButton = Instance.new("TextButton")
local ESPButton = Instance.new("TextButton")

-- Ativar GUI
ScreenGui.Parent = game.CoreGui

-- Configuração do Frame (menu)
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(0, 0, 0) -- Preto
Frame.BackgroundTransparency = 0.4 -- Transparente
Frame.Position = UDim2.new(0.35, 0, 0.25, 0)
Frame.Size = UDim2.new(0, 300, 0, 200)
Frame.Active = true
Frame.Draggable = true -- Menu pode ser arrastado

-- Botão Aimbot
AimbotButton.Parent = Frame
AimbotButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
AimbotButton.Size = UDim2.new(0, 250, 0, 40)
AimbotButton.Position = UDim2.new(0.08, 0, 0.2, 0)
AimbotButton.Text = "Aimbot"
AimbotButton.TextColor3 = Color3.fromRGB(255, 255, 255)
AimbotButton.Font = Enum.Font.SourceSans
AimbotButton.TextSize = 20

AimbotButton.MouseButton1Click:Connect(function()
    print("Aimbot ativado (placeholder)")
    -- termine o código do aimbot aqui
end)

-- Botão ESP
ESPButton.Parent = Frame
ESPButton.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
ESPButton.Size = UDim2.new(0, 250, 0, 40)
ESPButton.Position = UDim2.new(0.08, 0, 0.5, 0)
ESPButton.Text = "ESP"
ESPButton.TextColor3 = Color3.fromRGB(255, 255, 255)
ESPButton.Font = Enum.Font.SourceSans
ESPButton.TextSize = 20

ESPButton.MouseButton1Click:Connect(function()
    print("ESP ativado (placeholder)")
    -- termine o código do ESP aqui
end)
