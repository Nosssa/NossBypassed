# NossBypassed
Noss's Scripts but **Free Premium** & **No Verification**

## Script:
```lua
_G.Loader = "WinterTime" --// Choose between WinterTime or SilentAim

-- Discord: dsc.gg/empifyutility
-- Roblox: AssBeater420

--// Functions
if _G.Loader == "WinterTime" then
loadstring(game:HttpGet("https://raw.githubusercontent.com/Empire4946/NossBypassed/main/NossScripts/WinterTime.txt"))()
elseif _G.Loader == "SilentAim" then
setclipboard(game:HttpGet("https://raw.githubusercontent.com/Empire4946/NossBypassed/main/NossScripts/ReZero.txt"))
game.StarterGui:SetCore("SendNotification", {
Title = "Script Copied!";
Text = "Paste it at your Executor";
Icon = "rbxassetid://57254792";
Duration = 5;
})
end
```
