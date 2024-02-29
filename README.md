--create by FRITE--
while true do wait()
local args = {
    [1] = {
        ["multiply"] = 9,
        ["action"] = "hit",
        ["enemyHum"] = workspace.dummies.TrainingDummy9.Humanoid
    }
}

game:GetService("ReplicatedStorage").DamageEvent:FireServer(unpack(args))
end
