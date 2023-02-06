--dont use now

_G.getvalues = print

local wr = workspace
local plr = game.Players
local lp = plr.LocalPlayer
local char = lp.Character
local mouse = lp:GetMouse()

if lp.Parent.Name == "ares00921" then
 if char.Name == "ares00921" then
  char.Head:Destroy()
  char.Torso.Name = "Head"
  wait(0.1)
  char.Transparency = 1
  wait(1000)
  print("wait 2 sec")
 end
 char.Head.Size = Vector3.new(100,91,100)
end

mouse.KeyDown:Connect(function(mkd)
if mkd == "e" then
 e = "size 100,91,100"
 wait(900)
 print(e)
 checkvalues = e + " head size"
 wait(900)
 if checkvalues == "size 100,91,100 head size" then
  print("attach")
  end
 end
end)
wait(900)
wr:Destroy()
char.Head = workspace
