game.StarterGui:SetCore("SendNotification", {
Title = "1";
Text = "1";
Duration = math.huge;
Button1 = "1"
})
wait (1)
game.StarterGui:SetCore("SendNotification", {
Title = "2";
Text = "2";
Duration = math.huge;
Button1 = "2"
})
wait (1)
game.StarterGui:SetCore("SendNotification", {
Title = "3";
Text = "3";
Duration = math.huge;
Button1 = "3"
})
wait(1)
wait(0.5)
local message = Instance.new("Message", workspace)
        message.Text = "Happy New Year 2022."
        wait(3.5)
        message:Destroy()
        setclipboard("https://www.youtube.com/watch?v=Z0o3eLPbJ1k")
game:GetService('Players').LocalPlayer:Kick ("Happy New Year. Thank you everyone who supported me.")
