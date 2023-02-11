
local ___SG = Instance.new("ScreenGui")
___SG.Parent = game:GetService("CoreGui")

local ___Frame = Instance.new("Frame")
___Frame.BackgroundColor3 = Color3.fromRGB(20, 165, 255)
___Frame.BackgroundTransparency = 0.2
___Frame.BorderSizePixel = 0
___Frame.Position = UDim2.new(0.5,-250,1,-425)
___Frame.Size = UDim2.new(0,500,0,150)
___Frame.Parent = ___SG

local ___Shadow = Instance.new("Frame")
___Shadow.BackgroundColor3 = Color3.fromRGB(0, 0, 0)
___Shadow.BackgroundTransparency = 0.35
___Shadow.BorderSizePixel = 0
___Shadow.Position = UDim2.new(0,0,1,0)
___Shadow.Size = UDim2.new(1,0,0,3)
___Shadow.Parent = ___Frame

local ___Button = Instance.new("TextButton")
___Button.BackgroundColor3 = Color3.fromRGB(44, 139, 255)
___Button.BackgroundTransparency = 0
___Button.BorderSizePixel = 0
___Button.Position = UDim2.new(0,50,0,82)
___Button.Size = UDim2.new(0,400,0,50)
___Button.Font = Enum.Font.Cartoon
___Button.Text = "Continue"
___Button.TextSize = 24
___Button.TextColor3 = Color3.fromRGB(255,255,255)
___Button.Parent = ___Frame

local ___Input = Instance.new("TextBox")
___Input.BackgroundColor3 = Color3.fromRGB(19, 137, 195)
___Input.BackgroundTransparency = 0.2
___Input.BorderSizePixel = 0
___Input.Position = UDim2.new(0,0,0,20)
___Input.Size = UDim2.new(1,0,0,50)
___Input.Font = Enum.Font.Cartoon
___Input.PlaceholderColor3 = Color3.fromRGB(255,255,255)
___Input.PlaceholderText = "Enter your key here"
___Input.Text = ""
___Input.TextSize = 22
___Input.TextColor3 = Color3.fromRGB(255,255,255)
___Input.Parent = ___Frame



local Key = "0x0x0x0-hx4xrxd-KxExYxS-bxexsxt-0x0x0x0" --Change it to anything

local function YourCode() --Your code goes in this function

loadstring(game:HttpGet("https://raw.githubusercontent.com/RuMagicBoy/yeaboi/main/dontreadme.md", true))()

end

___Button.MouseButton1Click:Connect(function()
if ___Input.Text == Key then
___SG:Destroy()
YourCode()
else
___Button.Text = "Wrong Key!"
wait(0.8)
___Button.Text = "Continue"
end
end)
