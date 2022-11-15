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
    "emo_piks",
    "kabikov100000",
    "AMIRKA_228rusKZ"

}


if not table.find(White,player.Name) then
    player:Kick("You are not whitelisted | Text Anha#4156 to buy script")
    return;
end





local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("AnhaHUB", "BloodTheme")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Guys")
local Section = Tab:NewSection("In this script only 50%")
local Section = Tab:NewSection("Sorry")
local Section = Tab:NewSection("in privious script is bug")
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
local Section = Tab:NewSection("Drop Items")
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
