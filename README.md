print("You opened a treasure chest!")
local prompt = script.Parent
local wood = prompt.Parent
local top = wood.Parent:FindFirstChild("Top") -- Ensure this part is correct

prompt.Triggered:Connect(function()
    local vector = Vector3.new(wood.Position.X, wood.Position.Y + 2, wood.Position.Z)
    top.Position = vector

    -- Optional: Add a slight animation to make it look smooth
    -- You can use TweenService for this if you want smooth motion

    wait(1.5)  -- Wait for 1.5 seconds

    top:Destroy()  -- Remove the top of the chest

    prompt.Enabled = false
end)





* Fixed issue where you couldnt spawn in tradoc building 
* Fixed overhead ui 
* added a time gui
* untested fix for auto teaming 
* untested fix for where you spawn at different locations 


- Removed invisible barriers at exchange classrooms and lockers
- Removed insert command
```


+ 
+

* Fixed issue where you couldnt teleport in tradoc building
* Added a time gui 

- Removed main menu


--------------------------
+ added uniforms to the teleport mcx
+ warning the other mcx is no longer in use use the main one for now only use the other mcx for nametags
+ 
+ fixed teaming issue 
+ added a better obby
+ more changes coming soon
+ 

* Fixed issue with invsible parts at the mcx

* temporarliy removed profile gui 
* 
* 
* Fixed overhead gui 
* 
* 

- 
- 
- 
```




