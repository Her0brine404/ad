--if u read this u gay lol--

local player = game.Players.LocalPlayer

local White = {
    "RobinConway9",
    "KostyaTasher",
    "Her0brine404",
    "motik_potik228",
    "Daunich2281337",
    "ggddaass9087",
    "the_richestPlayerME",
    "albina09875",
    "kabikov100000",
    "AMIRKA_228rusKZ",
    "ArtAcker4",
    "poli_offs",
    "XOX_Studios",
    "emo_piks",
    "imba_perchi"
 

}


if not table.find(White,player.Name) then
    player:Kick("Same account launched game from different device.Reconnect if you prefer to use this device.")
    return;
end



game:GetService("StarterGui"):SetCore("SendNotification", { 
Title = "Roblox";
Text = "Sussy Activity after 5 days u will be banned";
Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})

game:GetService("StarterGui"):SetCore("SendNotification", { 
Title = "Pop it trading script";
Text = "By Anha#4156";
Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})

game:GetService("StarterGui"):SetCore("SendNotification", { 
Text = "";
Title = "Helper: Kostya#3329";
Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})

game:GetService("StarterGui"):SetCore("SendNotification", { 
Text = "+9.9M Robux";
Title = "Robux";
Icon = "rbxthumb://type=Asset&id=1542459468&w=150&h=150"})


local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("AnhaHUB", "BloodTheme")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Guys")
local Section = Tab:NewSection("In this script only 50%")
local Section = Tab:NewSection("Sorry")
local Section = Tab:NewSection("in privious script is bug")
local Tab = Window:NewTab("Visual Money GUI")
local Section = Tab:NewSection("VISUAL")
Section:NewButton("Enable UI", "", function()
    local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Visual Money", "DarkTheme")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Main")
Section:NewToggle("Inf money", "", function(state)
    if state then
                getgenv().infm = true;

while wait() do
    if getgenv().infm == true then
        game:GetService("Players").LocalPlayer.Cash.Value = "inf"
    end
end
    else
                getgenv().infm = false;

while wait() do
    if getgenv().infm == true then
        game:GetService("Players").LocalPlayer.Cash.Value = "inf"
    end
end
    end
end)
Section:NewToggle("funny number", "", function(state)
    if state then
                getgenv().cool = true;

while wait() do
    if getgenv().cool == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 69420
    end
end
    else
                getgenv().cool = false;

while wait() do
    if getgenv().cool == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 69420
    end
end
    end
end)
Section:NewToggle("1", "", function(state)
    if state then
                getgenv().one = true;

while wait() do
    if getgenv().one == true then
        game:GetService("Players").LocalPlayer.Cash.Value = "1"
    end
end
    else
                getgenv().one = false;

while wait() do
    if getgenv().one == true then
        game:GetService("Players").LocalPlayer.Cash.Value = "1"
    end
end
    end
end)
Section:NewToggle("100 qd", "", function(state)
    if state then
                getgenv().qd = true;

while wait() do
    if getgenv().qd == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 99999999999999999
    end
end
    else
                getgenv().qd = false;

while wait() do
    if getgenv().qd == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 99999999999999999
    end
end
    end
end)
Section:NewToggle("0", "", function(state)
    if state then
                getgenv().zero = true;

while wait() do
    if getgenv().zero == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 0
    end
end
    else
                getgenv().zero = false;

while wait() do
    if getgenv().zero == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 0
    end
end
    end
end)
Section:NewToggle("100t", "", function(state)
    if state then
                getgenv().t = true;

while wait() do
    if getgenv().t == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 100000000000000
    end
end
    else
                getgenv().t = false;

while wait() do
    if getgenv().t == true then
        game:GetService("Players").LocalPlayer.Cash.Value = 100000000000000
    end
end
    end
end)
Section:NewToggle("WTHH", "", function(state)
    if state then
                getgenv().m = true;

while wait() do
    if getgenv().m == true then
        game:GetService("Players").LocalPlayer.Cash.Value = -69420
    end
end
    else
                getgenv().m = false;

while wait() do
    if getgenv().m == true then
        game:GetService("Players").LocalPlayer.Cash.Value = -69420
    end
end
    end
end)
end)
local Tab = Window:NewTab("Fake Drop")
local Section = Tab:NewSection("fake drop ")
Section:NewButton("Enable fake drop", "Button", function()
    game.Players.LocalPlayer.Character.RightHand:Destroy()
end)
local Tab = Window:NewTab("Xray")
local Section = Tab:NewSection("Xray")
Section:NewToggle("Xray", " ", function(state)
    if state then
        game:GetService("Players").LocalPlayer.XRayEnabled.Value = true
    else
        game:GetService("Players").LocalPlayer.XRayEnabled.Value = false
    end
end)
local Tab = Window:NewTab("Dupe")
local Section = Tab:NewSection("Dupe")
Section:NewButton("Buy Silver Trophy", "Buy", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Silver")
end)
Section:NewButton("Buy Box House", "Buy", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Box Toy  House")
end)
Section:NewButton("Buy Inxta", "Buy", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Inxta")
end)
Section:NewButton("Buy Banana", "BUY not DUPE", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("The banana")
end)
Section:NewButton("Dupe F", "DUPE", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("F")
end)
Section:NewButton("Dupe harambe", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Box Toy Harambe")
end)
Section:NewButton("Dupe dart", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Dart")
end)
Section:NewButton("Dupe controller", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("XOX Controller")
end)
Section:NewButton("Dupe Tweet", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Tweet")
end)
Section:NewButton("Dupe bike", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Retro Bike")
end)
Section:NewButton("Dupe ooze", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Green Ooze")
end)
Section:NewButton("Dupe walky", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Walky Talky")
end)
Section:NewButton("Dupe demogorgan", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Demogorgan")
end)
Section:NewButton("Dupe demogorgan uwu", "dupe", function()
    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer("Demogorgan Kawaii")
end)
local Tab = Window:NewTab("Admin Scripts")
local Section = Tab:NewSection("Admin scripts")
Section:NewButton("FE Fly", "By Kostya#3329", function()
    local main = Instance.new("ScreenGui")
local Frame = Instance.new("Frame")
local up = Instance.new("TextButton")
local down = Instance.new("TextButton")
local onof = Instance.new("TextButton")
local TextLabel = Instance.new("TextLabel")
local plus = Instance.new("TextButton")
local speed = Instance.new("TextLabel")
local mine = Instance.new("TextButton")
local closebutton = Instance.new("TextButton")
local mini = Instance.new("TextButton")
local mini2 = Instance.new("TextButton") 

main.Name = "main"
main.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
main.ZIndexBehavior = Enum.ZIndexBehavior.Sibling
main.ResetOnSpawn = false 

Frame.Parent = main
Frame.BackgroundColor3 = Color3.fromRGB(163, 255, 137)
Frame.BorderColor3 = Color3.fromRGB(103, 221, 213)
Frame.Position = UDim2.new(0.100320168, 0, 0.379746825, 0)
Frame.Size = UDim2.new(0, 190, 0, 57) 

up.Name = "up"
up.Parent = Frame
up.BackgroundColor3 = Color3.fromRGB(79, 255, 152)
up.Size = UDim2.new(0, 44, 0, 28)
up.Font = Enum.Font.SourceSans
up.Text = "UP"
up.TextColor3 = Color3.fromRGB(0, 0, 0)
up.TextSize = 14.000 

down.Name = "down"
down.Parent = Frame
down.BackgroundColor3 = Color3.fromRGB(215, 255, 121)
down.Position = UDim2.new(0, 0, 0.491228074, 0)
down.Size = UDim2.new(0, 44, 0, 28)
down.Font = Enum.Font.SourceSans
down.Text = "DOWN"
down.TextColor3 = Color3.fromRGB(0, 0, 0)
down.TextSize = 14.000 

onof.Name = "onof"
onof.Parent = Frame
onof.BackgroundColor3 = Color3.fromRGB(255, 249, 74)
onof.Position = UDim2.new(0.702823281, 0, 0.491228074, 0)
onof.Size = UDim2.new(0, 56, 0, 28)
onof.Font = Enum.Font.SourceSans
onof.Text = "fly"
onof.TextColor3 = Color3.fromRGB(0, 0, 0)
onof.TextSize = 14.000 

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(242, 60, 255)
TextLabel.Position = UDim2.new(0.469327301, 0, 0, 0)
TextLabel.Size = UDim2.new(0, 100, 0, 28)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "FE Fly"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextScaled = true
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true 

plus.Name = "plus"
plus.Parent = Frame
plus.BackgroundColor3 = Color3.fromRGB(133, 145, 255)
plus.Position = UDim2.new(0.231578946, 0, 0, 0)
plus.Size = UDim2.new(0, 45, 0, 28)
plus.Font = Enum.Font.SourceSans
plus.Text = "+"
plus.TextColor3 = Color3.fromRGB(0, 0, 0)
plus.TextScaled = true
plus.TextSize = 14.000
plus.TextWrapped = true 

speed.Name = "speed"
speed.Parent = Frame
speed.BackgroundColor3 = Color3.fromRGB(255, 85, 0)
speed.Position = UDim2.new(0.468421042, 0, 0.491228074, 0)
speed.Size = UDim2.new(0, 44, 0, 28)
speed.Font = Enum.Font.SourceSans
speed.Text = "1"
speed.TextColor3 = Color3.fromRGB(0, 0, 0)
speed.TextScaled = true
speed.TextSize = 14.000
speed.TextWrapped = true 

mine.Name = "mine"
mine.Parent = Frame
mine.BackgroundColor3 = Color3.fromRGB(123, 255, 247)
mine.Position = UDim2.new(0.231578946, 0, 0.491228074, 0)
mine.Size = UDim2.new(0, 45, 0, 29)
mine.Font = Enum.Font.SourceSans
mine.Text = "-"
mine.TextColor3 = Color3.fromRGB(0, 0, 0)
mine.TextScaled = true
mine.TextSize = 14.000
mine.TextWrapped = true 

closebutton.Name = "Close"
closebutton.Parent = main.Frame
closebutton.BackgroundColor3 = Color3.fromRGB(225, 25, 0)
closebutton.Font = "SourceSans"
closebutton.Size = UDim2.new(0, 45, 0, 28)
closebutton.Text = "X"
closebutton.TextSize = 30
closebutton.Position = UDim2.new(0, 0, -1, 27) 

mini.Name = "minimize"
mini.Parent = main.Frame
mini.BackgroundColor3 = Color3.fromRGB(192, 150, 230)
mini.Font = "SourceSans"
mini.Size = UDim2.new(0, 45, 0, 28)
mini.Text = "-"
mini.TextSize = 40
mini.Position = UDim2.new(0, 44, -1, 27) 

mini2.Name = "minimize2"
mini2.Parent = main.Frame
mini2.BackgroundColor3 = Color3.fromRGB(192, 150, 230)
mini2.Font = "SourceSans"
mini2.Size = UDim2.new(0, 45, 0, 28)
mini2.Text = "+"
mini2.TextSize = 40
mini2.Position = UDim2.new(0, 44, -1, 57)
mini2.Visible = false 

speeds = 1 

local speaker = game:GetService("Players").LocalPlayer 

local chr = game.Players.LocalPlayer.Character
local hum = chr and chr:FindFirstChildWhichIsA("Humanoid") 

nowe = false 

game:GetService("StarterGui"):SetCore("SendNotification", { 
Title = "FE Fly";
Text = "By Kostya#3329";
Icon = "rbxthumb://type=Asset&id=5107182114&w=150&h=150"})
Duration = 5; 

Frame.Active = true -- main = gui
Frame.Draggable = true 

onof.MouseButton1Down:connect(function() 

if nowe == true then
nowe = false 

speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Climbing,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.FallingDown,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Flying,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Freefall,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Jumping,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Landed,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Physics,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Ragdoll,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Running,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.RunningNoPhysics,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Seated,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.StrafingNoPhysics,true)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Swimming,true)
speaker.Character.Humanoid:ChangeState(Enum.HumanoidStateType.RunningNoPhysics)
else 
nowe = true



for i = 1, speeds do
spawn(function() 

local hb = game:GetService("RunService").Heartbeat


tpwalking = true
local chr = game.Players.LocalPlayer.Character
local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")
while tpwalking and hb:Wait() and chr and hum and hum.Parent do
if hum.MoveDirection.Magnitude > 0 then
chr:TranslateBy(hum.MoveDirection)
end
end 

end)
end
game.Players.LocalPlayer.Character.Animate.Disabled = true
local Char = game.Players.LocalPlayer.Character
local Hum = Char:FindFirstChildOfClass("Humanoid") or Char:FindFirstChildOfClass("AnimationController") 

for i,v in next, Hum:GetPlayingAnimationTracks() do
v:AdjustSpeed(0)
end
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Climbing,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.FallingDown,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Flying,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Freefall,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.GettingUp,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Jumping,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Landed,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Physics,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.PlatformStanding,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Ragdoll,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Running,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.RunningNoPhysics,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Seated,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.StrafingNoPhysics,false)
speaker.Character.Humanoid:SetStateEnabled(Enum.HumanoidStateType.Swimming,false)
speaker.Character.Humanoid:ChangeState(Enum.HumanoidStateType.Swimming)
end




if game:GetService("Players").LocalPlayer.Character:FindFirstChildOfClass("Humanoid").RigType == Enum.HumanoidRigType.R6 then



local plr = game.Players.LocalPlayer
local torso = plr.Character.Torso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 50
local speed = 0


local bg = Instance.new("BodyGyro", torso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = torso.CFrame
local bv = Instance.new("BodyVelocity", torso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
if nowe == true then
plr.Character.Humanoid.PlatformStand = true
end
while nowe == true or game:GetService("Players").LocalPlayer.Character.Humanoid.Health == 0 do
game:GetService("RunService").RenderStepped:Wait() 

if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0,0)
end
--game.Players.LocalPlayer.Character.Animate.Disabled = true
bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
end
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
game.Players.LocalPlayer.Character.Animate.Disabled = false
tpwalking = false




else
local plr = game.Players.LocalPlayer
local UpperTorso = plr.Character.UpperTorso
local flying = true
local deb = true
local ctrl = {f = 0, b = 0, l = 0, r = 0}
local lastctrl = {f = 0, b = 0, l = 0, r = 0}
local maxspeed = 50
local speed = 0


local bg = Instance.new("BodyGyro", UpperTorso)
bg.P = 9e4
bg.maxTorque = Vector3.new(9e9, 9e9, 9e9)
bg.cframe = UpperTorso.CFrame
local bv = Instance.new("BodyVelocity", UpperTorso)
bv.velocity = Vector3.new(0,0.1,0)
bv.maxForce = Vector3.new(9e9, 9e9, 9e9)
if nowe == true then
plr.Character.Humanoid.PlatformStand = true
end
while nowe == true or game:GetService("Players").LocalPlayer.Character.Humanoid.Health == 0 do
wait() 

if ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0 then
speed = speed+.5+(speed/maxspeed)
if speed > maxspeed then
speed = maxspeed
end
elseif not (ctrl.l + ctrl.r ~= 0 or ctrl.f + ctrl.b ~= 0) and speed ~= 0 then
speed = speed-1
if speed < 0 then
speed = 0
end
end
if (ctrl.l + ctrl.r) ~= 0 or (ctrl.f + ctrl.b) ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (ctrl.f+ctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(ctrl.l+ctrl.r,(ctrl.f+ctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
lastctrl = {f = ctrl.f, b = ctrl.b, l = ctrl.l, r = ctrl.r}
elseif (ctrl.l + ctrl.r) == 0 and (ctrl.f + ctrl.b) == 0 and speed ~= 0 then
bv.velocity = ((game.Workspace.CurrentCamera.CoordinateFrame.lookVector * (lastctrl.f+lastctrl.b)) + ((game.Workspace.CurrentCamera.CoordinateFrame * CFrame.new(lastctrl.l+lastctrl.r,(lastctrl.f+lastctrl.b)*.2,0).p) - game.Workspace.CurrentCamera.CoordinateFrame.p))*speed
else
bv.velocity = Vector3.new(0,0,0)
end 

bg.cframe = game.Workspace.CurrentCamera.CoordinateFrame * CFrame.Angles(-math.rad((ctrl.f+ctrl.b)*50*speed/maxspeed),0,0)
end
ctrl = {f = 0, b = 0, l = 0, r = 0}
lastctrl = {f = 0, b = 0, l = 0, r = 0}
speed = 0
bg:Destroy()
bv:Destroy()
plr.Character.Humanoid.PlatformStand = false
game.Players.LocalPlayer.Character.Animate.Disabled = false
tpwalking = false



end





end) 

local tis 

up.MouseButton1Down:connect(function()
tis = up.MouseEnter:connect(function()
while tis do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,1,0)
end
end)
end) 

up.MouseLeave:connect(function()
if tis then
tis:Disconnect()
tis = nil
end
end) 

local dis 

down.MouseButton1Down:connect(function()
dis = down.MouseEnter:connect(function()
while dis do
wait()
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame * CFrame.new(0,-1,0)
end
end)
end) 

down.MouseLeave:connect(function()
if dis then
dis:Disconnect()
dis = nil
end
end)


game:GetService("Players").LocalPlayer.CharacterAdded:Connect(function(char)
wait(0.7)
game.Players.LocalPlayer.Character.Humanoid.PlatformStand = false
game.Players.LocalPlayer.Character.Animate.Disabled = false 

end)


plus.MouseButton1Down:connect(function()
speeds = speeds + 1
speed.Text = speeds
if nowe == true then


tpwalking = false
for i = 1, speeds do
spawn(function() 

local hb = game:GetService("RunService").Heartbeat


tpwalking = true
local chr = game.Players.LocalPlayer.Character
local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")
while tpwalking and hb:Wait() and chr and hum and hum.Parent do
if hum.MoveDirection.Magnitude > 0 then
chr:TranslateBy(hum.MoveDirection)
end
end 

end)
end
end
end)
mine.MouseButton1Down:connect(function()
if speeds == 1 then
speed.Text = 'cannot be less than 1'
wait(1)
speed.Text = speeds
else
speeds = speeds - 1
speed.Text = speeds
if nowe == true then
tpwalking = false
for i = 1, speeds do
spawn(function() 

local hb = game:GetService("RunService").Heartbeat


tpwalking = true
local chr = game.Players.LocalPlayer.Character
local hum = chr and chr:FindFirstChildWhichIsA("Humanoid")
while tpwalking and hb:Wait() and chr and hum and hum.Parent do
if hum.MoveDirection.Magnitude > 0 then
chr:TranslateBy(hum.MoveDirection)
end
end 

end)
end
end
end
end) 

closebutton.MouseButton1Click:Connect(function()
main:Destroy()
end) 

mini.MouseButton1Click:Connect(function()
up.Visible = false
down.Visible = false
onof.Visible = false
plus.Visible = false
speed.Visible = false
mine.Visible = false
mini.Visible = false
mini2.Visible = true
main.Frame.BackgroundTransparency = 1
closebutton.Position = UDim2.new(0, 0, -1, 57)
end) 

mini2.MouseButton1Click:Connect(function()
up.Visible = true
down.Visible = true
onof.Visible = true
plus.Visible = true
speed.Visible = true
mine.Visible = true
mini.Visible = true
mini2.Visible = false
main.Frame.BackgroundTransparency = 0 
closebutton.Position = UDim2.new(0, 0, -1, 27)
end)
end)

Section:NewButton("Break Chat", "check the chat xd", function()
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))
    local args = {
    [1] = " ",
    [2] = "All"
}

game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(unpack(args))

end)
Section:NewButton("Inf Yield", "fe admin", function()
    loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
end)
Section:NewSlider("Speed", "Flash!!!", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)

local Tab = Window:NewTab("Drop Items")
local Section = Tab:NewSection("Drop Items")
Section:NewButton("Drop Angel Eye", "drop", function()
    local args = {
    [1] = "Angel Eye"
}

game:GetService("ReplicatedStorage").RemoteEvents.Equip:FireServer(unpack(args))
wait(0.4)
local args = {
    [1] = "Angel Eye"
}

game:GetService("ReplicatedStorage").RemoteEvents.Drop:FireServer(unpack(args))
end)
Section:NewButton("Drop F", "drop", function()
    local args = {
    [1] = "F"
}

game:GetService("ReplicatedStorage").RemoteEvents.Equip:FireServer(unpack(args))
wait(0.4)
local args = {
    [1] = "F"
}

game:GetService("ReplicatedStorage").RemoteEvents.Drop:FireServer(unpack(args))
end)
Section:NewButton("Drop harambe", "drop", function()
    local args = {
    [1] = "Box Toy Harambe"
}

game:GetService("ReplicatedStorage").RemoteEvents.Equip:FireServer(unpack(args))
wait(0.4)
local args = {
    [1] = "Box Toy Harambe"
}

game:GetService("ReplicatedStorage").RemoteEvents.Drop:FireServer(unpack(args))
end)
Section:NewButton("Drop dart", "drop", function()
    local args = {
    [1] = "Dart"
}

game:GetService("ReplicatedStorage").RemoteEvents.Equip:FireServer(unpack(args))
wait(0.4)
local args = {
    [1] = "Dart"
}

game:GetService("ReplicatedStorage").RemoteEvents.Drop:FireServer(unpack(args))
end)
Section:NewButton("Drop banana", "drop", function()
    local args = {
    [1] = "The banana"
}

game:GetService("ReplicatedStorage").RemoteEvents.Equip:FireServer(unpack(args))
wait(0.4)
local args = {
    [1] = "The banana"
}

game:GetService("ReplicatedStorage").RemoteEvents.Drop:FireServer(unpack(args))
end)


local Tab = Window:NewTab("Credits")
local Section = Tab:NewSection("Owner: Anha#4156")
local Section = Tab:NewSection("Creator: Anha#4156")
local Section = Tab:NewSection("Helper: Kostya#3329")

print("test") 
print("script pop it")
print("created: Anha#4156")
