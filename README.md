# miqqu

# library

```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/Marco8642/science/main/ui%20libs2", true))()
```

# Window

```lua
local example = library:CreateWindow({
  text = "Taxi Boss"
})
```

# Label

```lua
example:AddLabel("Teleports 1",function()
      end)
```

# Button

```lua
example:AddButton("Auto write",function()
print("gay")
end)
```
# Toggle

```lua
example:AddToggle("Auto sec", function(state)
print("gay")
end)
```

# Dropdown

```lua
example:AddDropdown({"Teleports","Beechwood","Beechwood Beach","Boss Airport","Bridgeview","Cedar Side","Central Bank","Central City","City Park","Coconut Park","Country Club","Da Hills","Doge Harbor"},function(state) --true/false, replaces the current title "Dropdown" with the option
```
