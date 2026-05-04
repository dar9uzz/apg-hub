local Rayfield = loadstring(game:HttpGet('https://sirius.menu/rayfield'))()

local Window = Rayfield:CreateWindow({
   Name = "antenaplayguys script hub",
   Icon = 0, -- Icon in Topbar. Can use Lucide Icons (string) or Roblox Image (number). 0 to use no icon (default).
   LoadingTitle = "antenaplayguys script hub",
   LoadingSubtitle = "by antenaplayguy",
   ShowText = "Open", -- for mobile users to unhide Rayfield, change if you'd like
   Theme = "Ocean", -- Check https://docs.sirius.menu/rayfield/configuration/themes

   ToggleUIKeybind = "K", -- The keybind to toggle the UI visibility (string like "K" or Enum.KeyCode)

   DisableRayfieldPrompts = false,
   DisableBuildWarnings = false, -- Prevents Rayfield from emitting warnings when the script has a version mismatch with the interface.

   -- ScriptID = "sid_xxxxxxxxxxxx", -- Your Script ID from developer.sirius.menu — enables analytics, managed keys, and script hosting

   ConfigurationSaving = {
      Enabled = true,
      FolderName = nil, -- Create a custom folder for your hub/game
      FileName = "Big Hub"
   },

   Discord = {
      Enabled = false, -- Prompt the user to join your Discord server if their executor supports it
      Invite = "noinvitelink", -- The Discord invite code, do not include Discord.gg/. E.g. Discord.gg/ABCD would be ABCD
      RememberJoins = true -- Set this to false to make them join the Discord every time they load it up
   },

   KeySystem = false, -- Set this to true to use our key system
   KeySettings = {
      Title = "Untitled",
      Subtitle = "Key System",
      Note = "No method of obtaining the key is provided", -- Use this to tell the user how to get a key
      FileName = "Key", -- It is recommended to use something unique, as other scripts using Rayfield may overwrite your key file
      SaveKey = true, -- The user's key will be saved, but if you change the key, they will be unable to use your script
      GrabKeyFromSite = false, -- If this is true, set Key below to the RAW site you would like Rayfield to get the key from
      Key = {"Hello"} -- List of keys that the system will accept, can be RAW file links (pastebin, github, etc.) or simple strings ("hello", "key22")
   }
})

local Tab = Window:CreateTab("Basics", 0) -- Title, Image (can be string or number)

local Button = Tab:CreateButton({
   Name = "Infinite Yield",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "CMD-X",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/Source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Owl Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Proxo Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/ProxoHub/ProxoHub/main/Loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Dark Dex",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/DarkDex/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Vynixius Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RegularVynixu/VynixiusHub/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Eclipse X",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Reviz Admin",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/RevizAdmin/RevizAdmin/main/Loader.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Nebula X",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/7GrandDadPGN/VapeV4ForRoblox/main/NewMainScript.lua"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Adonis Admin",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/Sceleratis/Adonis/master/Source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Sentinel",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/sentinel/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Star Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/starhub/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Prism Admin",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/prismadmin/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Raven Admin",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/ravenadmin/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Shadow Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/shadowhub/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Lunar Hub",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/lunarhub/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Fluxus",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/fluxus/master/source"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Universal X",
   Callback = function()
        loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/universalx/master/source"))()
   end,
})

local Tab = Window:CreateTab("Genesis", 0) -- Title, Image (can be string or number)

local Button = Tab:CreateButton({
   Name = "Neko[Try It At Your Own Risk,This Is Sus]",
   Callback = function()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/GenesisFE/Genesis/main/Obfuscations/Neko"))()
   end,
})

local Button = Tab:CreateButton({
   Name = "Ban Hammer",
   Callback = function()
         loadstring(game:HttpGet("https://raw.githubusercontent.com/GenesisFE/Genesis/main/Obfuscations/Ban%20Hammer"))()
   end,
})






