
--windows
local Window = Library.CreateLib("Angel hub", "DarkTheme")

--tabs
local Tab = Window:NewTab("scripts")

Section:NewLabel("script")


--comeco

Section:NewButton("fly", "ButtonInfo", function()
    print("loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))
end)

--slides 

Section:NewSlider("SliderText", "SliderInfo", 500, 0, function(s) -- 500 (MaxValue) | 0 (MinValue)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = s
end)
