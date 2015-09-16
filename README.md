local screen = Instance.new("ScreenGui")
screen.Name = "Admin"
screen.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

local z = Instance.new("TextLabel")
z.Parent = screen
z.Name = "xd"
z.Text = "Welcome,"..game.Players.LocalPlayer.Name.."!"
z.Size = UDim2.new(0, 550,0, 400)
z.FontSize = Enum.FontSize.Size24
z.Position = UDim2.new(0, 100,0, 0)
z.BackgroundTransparency = 0.5
z.BackgroundColor3 = Color3.new(0,0,0)
z.TextColor3 = Color3.new(255,255,255)
z:TweenPosition(UDim2.new(0, 400,0, 200),"In",style,interval,false)
wait(2)
z:TweenPosition(UDim2.new(0, 0,0, -10000),"In",style,interval,false)
wait(1)
z:remove()

local z = Instance.new("TextLabel")
z.Parent = screen
z.Name = "LOL"
z.Text = "Unity"
z.Size = UDim2.new(0, 350,0, 70)
z.FontSize = Enum.FontSize.Size24
z.Position = UDim2.new(0, 100,0, 0)
z.BackgroundTransparency = 0.5
z.BackgroundColor3 = Color3.new(0,0,0)
z.TextColor3 = Color3.new(255,255,255)



local x = Instance.new("ImageLabel")
x.Parent = screen
x.Name = "Notify"
x.Image = "rbxassetid://214389321"
x.Size = UDim2.new(0, 100,0, 70)



local sc = Instance.new("ScrollingFrame")
sc.Parent = screen
sc.Name = "SC"
sc.Size = UDim2.new(0, 200,0, 400)
sc.Position = UDim2.new(0, 1,0, 70)
sc.BackgroundColor3 = Color3.new(0,0,0)
sc.BackgroundTransparency = 0.5
wait()
local chattext = Instance.new("TextBox")
chattext.Parent = screen
chattext.Name = "xd"
chattext.Text = "To Chat, Click this bar, or press /"
chattext.Size = UDim2.new(0, 400,0, 50)
chattext.FontSize = Enum.FontSize.Size18
chattext.Position = UDim2.new(0, 950,0, 500)
chattext.BackgroundTransparency = 0.5
chattext.BackgroundColor3 = Color3.new(0,0,0)
chattext.TextColor3 = Color3.new(1,0,0)
