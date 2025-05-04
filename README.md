--[Script Made By FireServiceScripter#1073, Or Error333615 in Roblox]
--[NOTICE : TO THE STUPID SKIDDIE STEALER DON'T STEAL THIS SCRIPT OR YOU WILL PAY FOR COPRYGHT]


local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()
local Window = Rayfield:CreateWindow({
   Name = "c00lhub v1.0",
   LoadingTitle = "Loading FE Bypass...",
   LoadingSubtitle = "by Error333615 ( Owner )",
   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },
   Discord = {
      Enabled = false,
      Invite = "noinvitelink", -- The Discord invite code, do not include discord.gg/. E.g. discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the discord every time they load it up
   },
   KeySystem = true, -- Set this to true to use our key system
   KeySettings = {
      Title = "c00lgui hub non-skidder verification",
      Subtitle = "Key System",
      Note = "Contact FireServiceScripter#1073 on discord and you will have a chance to get the key",
      FileName = "Key", -- It is recommended to use something unique as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"abc39s'd01sja9sk"} -- List of keys that will be accepted by the system, can be RAW file links (pastebin, github etc) or simple strings ("hello","key22")
   }
})

Rayfield:Notify({
   Title = "Welcome !",
   Content = "Welcome To The Best FE Bypass",
   Duration = 6.5,
   Image = 4483362458,
   Actions = { -- Notification Buttons
      Ignore = {
         Name = "Okay!",
         Callback = function()
         print("The user tapped Okay!")
      end
   },
},
})

local Welcome = Window:CreateTab("Welcome !", nil) -- Title, Image
local InfoSection = Welcome:CreateSection("Information")

local Paragraph = Welcome:CreateParagraph({Title = "What Is c00gui hub v1.0 ?", Content = "It's a fe bypass c00lgui create by Error333615"})
local Paragraph = Welcome:CreateParagraph({Title = "What Features There In It", Content = "We have fe c00lgui / Speed/Jump Hack Noclip and more..."})
local Paragraph = Welcome:CreateParagraph({Title = "Thanks For Supporting Our Team", Content = "When You Execute It You Support The team c00lkidd reborn ty"})
local Paragraph = Welcome:CreateParagraph({Title = "NOTICE", Content = "Press The close gui button only if you have problem to close the gui"})

local Button = Welcome:CreateButton({
   Name = "Close GUI",
   Callback = function()
        Rayfield:Destroy()
   end,
})



local c00lgui = Window:CreateTab("c00lgui", nil) -- Title, Image
local c00lguiSection = c00lgui:CreateSection("c00lgui")

local Button = c00lgui:CreateButton({
   Name = "c00lgui v2.2 by team c00lkidd",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/theawesomari0/c00lgui/66033e8ff67eccc421fb04b3924e42d4adf3d7a2/c00lgui%20v2.2?subid1=20230826-2047-4399-8bd3-612370889e32",true))()
   end,
})

local Button = c00lgui:CreateButton({
   Name = "c00lgui rc7",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/MiRw3b/c00lgui-v3rx/main/c00lguiv3rx.lua",true))()
   end,
})

local Button = c00lgui:CreateButton({
   Name = "c00lgui reborn v0.5",
   Callback = function()
        loadstring(game:GetObjects("rbxassetid://8127297852")[1].Source)()
   end,
})

local feTab = Window:CreateTab("Fe Bypass", nil) -- Title, Image
local feSection = feTab:CreateSection("Fe Bypass")

local Paragraph = feTab:CreateParagraph({Title = "NOTICE", Content = "Some FE script can doesn't work if they don't work contact me FireServiceScripter#1073 on discord"})

local Button = feTab:CreateButton({
   Name = "FE Free Gamepass GUI",
   Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/QtQ4YnVR'))()
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Twilight Daycare Destroyer",
   Callback = function()
        loadstring(game:HttpGet('https://gist.githubusercontent.com/dark-modz/46b122bee4a227eca1355a56ebff0cd3/raw/1a1eb29f7eb7153a718986afb379d2786c420fab/OPtwilightdaycareGUI'))(' Watermelon ? ')
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Build And Survive Destroyer",
   Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/LgfZbBVy'))()
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Bypass Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RealMrQuacks/AuratusX/master/Load"))()
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Tools Drop [FREE ADMIN]",
   Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/brownfieldd00/Roblox/main/Games/FREE%20ADMIN.lua'))()
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Troll GUI",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/GetYoScript/Aayus/main/Sick"))()
   end,
})

local Button = feTab:CreateButton({
   Name = "FE Btools",
   Callback = function()
        loadstring(game:HttpGet('https://pastebin.com/raw/WaqDDa8v'))()
    end,
    })

local Button = feTab:CreateButton({
   Name = "FE Hub Script [best]",
   Callback = function()
        loadstring(game:HttpGet('https://raw.githubusercontent.com/Dvrknvss/UniversalFEScriptHub/main/Script'))()
   end,
})

local Executors = Window:CreateTab("Executors", nil) -- Title, Image
local ExSection = Executors:CreateSection("RC7")

local Button = Executors:CreateButton({
   Name = "RC7",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CoreGui/Scripts/main/RC7"))()
   end,
})

--[Script Made By FireServiceScripter#1073, Or Error333615 in Roblox]
--[NOTICE : This Script Has Been Create By Error333615 The Owner Of The Team c00lkidd Reborn nobody have create this script with him.]
--[NOTICE : IF THIS SCRIPT BE PATCHED SAY IT TO ME ON DISCORD : FireServiceScripter#1073 ]
--[NOTICE : IF YOU MAKE A REBORN OF THIS SCRIPT CREATE A CREDITS TAB AND MAKE CREDITS FOR ME FOR HAVE CREATE THE ORIGINAL C00LHUB]
--[team c00lkidd reborn join today !]
