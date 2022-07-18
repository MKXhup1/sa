local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("ควยภูมิ", "DarkTheme")

local Tab = Window:NewTab("วันพีช")

local Section = Tab:NewSection("เก็บกล่อง")

Section:NewButton("กด", "เก็บกล่อง", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/scriptpastebin/raw/main/chestfarm"))()

end)

local Section = Tab:NewSection("ฟาม")

Section:NewButton("กด", "ฟาม", function()

    loadstring(game:HttpGet("https://raw.githubusercontent.com/GooD1020/sazx-upka-Ton-Chicken/main/README.md"))();

end)

local Tab = Window:NewTab("คิง")

Section:NewButton("กด", "ฟาม", function()

    local ScreenGui = Instance.new("ScreenGui")

    local Toggle = Instance.new("TextButton")

    

    ScreenGui.Name = "ScreenGui"

    ScreenGui.Parent = game.CoreGui

    

    Toggle.Name = "Toggle"

    Toggle.Parent = ScreenGui

    Toggle.BackgroundColor3 = Color3.fromRGB(15, 15, 15)

    Toggle.Position = UDim2.new(0.120833337, 0, 0.0952890813, 0)

    Toggle.Size = UDim2.new(0, 50, 0, 50)

    Toggle.Font = Enum.Font.Code

    Toggle.Text = "Ui"

    Toggle.TextColor3 = Color3.fromRGB(255, 0, 0)

    Toggle.TextScaled = true

    Toggle.MouseButton1Down:connect(function()

        game:GetService("VirtualInputManager"):SendKeyEvent(true,305,false,game)

    game:GetService("VirtualInputManager"):SendKeyEvent(false,305,false,game)

    end)

loadstring(game:HttpGet"https://raw.githubusercontent.com/xQuartyx/DonateMe/main/ScriptLoader")()

end)

local Tab = Window:NewTab("วันพีช")

Section:NewButton("ButtonText", "ButtonInfo", function()

loadstring(game:HttpGet("https://raw.githubusercontent.com/viet452009/VietHub/main/VietHub.lua"))()

end)
