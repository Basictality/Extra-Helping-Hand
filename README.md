r65 = game.Players.LocalPlayer.Character

back=Instance.new("Part",r65)
back.Color = Color3.new(0,0,0)
back.Material = "DiamondPlate"
back.FormFactor = "Custom"
back.Size = Vector3.new(2,2,0)

backw = Instance.new("Weld",back)
backw.Part0=r65.Torso
backw.Part1=back
backw.C0=CFrame.new(0,0,0.5)

back1=Instance.new("Part",back)
back1.Color = Color3.new(0,0,0)
back1.Material = "DiamondPlate"
back1.FormFactor = "Custom"
back1.Size = Vector3.new(1,1,1)

backw = Instance.new("Weld",back1)
backw.Part0=r65.Torso
backw.Part1=back1
backw.C0=CFrame.new(1.5,0.5,1)

back2=Instance.new("Part",back)
back2.Color = Color3.new(0,0,0)
back2.Material = "DiamondPlate"
back2.FormFactor = "Custom"
back2.Size = Vector3.new(1,1,1)

backw1 = Instance.new("Weld",back2)
backw1.Part0=r65.Torso
backw1.Part1=back2
backw1.C0=CFrame.new(-1.5,0.5,1)
