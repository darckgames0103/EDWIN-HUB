
                                                                                                                        
                              

                                                                                                                                                                
local UILibrary = loadstring(game:HttpGet("https://raw.githubusercontent.com/bloodball/-back-ups-for-libs/main/twink"))()

local MainUI = UILibrary.Load("EDWIN")
local FirstPage = MainUI.AddPage("Nfts")

FirstPage.AddButton("Ben", function()
    local args = {
		[1] = "Trading Ben"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)


FirstPage.AddButton("Munneh", function()
    local args = {
		[1] = "Munneh"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

FirstPage.AddButton("Mommeh long legs", function()
    local args = {
		[1] = "Mommeh Long Legs"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)


FirstPage.AddToggle("auto buy ben", false, function(Value)
    if Value then
        _G.on = true
        
        while _G.on == true do
            wait(0.1)
        
        wait(0.1)
        local args = {
                [1] = "Trading Ben"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                local args = {
                [1] = "Trading Ben"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
        
        wait(0.1)
        
            end
            else
        _G.on = false
                
            end
        end)

        
FirstPage.AddToggle("auto buy munehh", false, function(Value)
    if Value then
        _G.on = true
        
        while _G.on == true do
            wait(0.1)
        
        wait(0.1)
        local args = {
                [1] = "Munneh"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                local args = {
                [1] = "Munneh"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
        
        wait(0.1)
        
            end
            else
        _G.on = false
                
            end
        end)

        
FirstPage.AddToggle("auto buy ben", false, function(Value)
    if Value then
        _G.on = true
        
        while _G.on == true do
            wait(0.1)
        
        wait(0.1)
        local args = {
                [1] = "Mommeh Long Legs"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                local args = {
                [1] = "Mommeh Long Legs"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
        
        wait(0.1)
        
            end
            else
        _G.on = false
                
            end
        end)



local FirstPage = MainUI.AddPage("Dupe")
FirstPage.AddButton("duplicar the banana", function()
    local args = {
		[1] = "The banana"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
	local args = {
		[1] = "The banana"
	}

	game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
end)

FirstPage.AddToggle("auto dupe the banana", false, function(Value)
    if Value then
        _G.on = true
        
        while _G.on == true do
            wait(0.2)
        
        wait(0.1)
        local args = {
                [1] = "The banana"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                local args = {
                [1] = "The banana"
            }
            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
        
        wait(0.1)
        
            end
            else
        _G.on = false
                
            end
        end)
        

        FirstPage.AddToggle("auto dupe Pop it Rainbow", false, function(Value)
            if Value then
                _G.on = true
                
                while _G.on == true do
                    wait(0.2)
                
                wait(0.1)
                local args = {
                        [1] = "Pop It Rainbow!"
                    }
                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                        local args = {
                        [1] = "Pop It Rainbow!"
                    }
                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                
                wait(0.1)
                
                    end
                    else
                _G.on = false
                        
                    end
                end)

                FirstPage.AddToggle("auto dupe lolly Rb", false, function(Value)
                    if Value then
                        _G.on = true
                        
                        while _G.on == true do
                            wait(0.2)
                        
                        wait(0.1)
                        local args = {
                                [1] = "Lolly Rainbow"
                            }
                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                local args = {
                                [1] = "Lolly Rainbow"
                            }
                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                        
                        wait(0.1)
                        
                            end
                            else
                        _G.on = false
                                
                            end
                        end)

                        FirstPage.AddToggle("auto dupe Amogus Rainbow", false, function(Value)
                            if Value then
                                _G.on = true
                                
                                while _G.on == true do
                                    wait(0.2)
                                
                                wait(0.1)
                                local args = {
                                        [1] = "Amogus Rainbow"
                                    }
                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                        local args = {
                                        [1] = "Amogus Rainbow"
                                    }
                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                
                                wait(0.1)
                                
                                    end
                                    else
                                _G.on = false
                                        
                                    end
                                end)

                                FirstPage.AddToggle("auto dupe Crystal Rainbow", false, function(Value)
                                    if Value then
                                        _G.on = true
                                        
                                        while _G.on == true do
                                            wait(0.2)
                                        
                                        wait(0.1)
                                        local args = {
                                                [1] = "Crystal Rainbow"
                                            }
                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                local args = {
                                                [1] = "Crystal Rainbow"
                                            }
                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                        
                                        wait(0.1)
                                        
                                            end
                                            else
                                        _G.on = false
                                                
                                            end
                                        end)
                
                                        FirstPage.AddToggle("auto dupe slippy Rainbow", false, function(Value)
                                            if Value then
                                                _G.on = true
                                                
                                                while _G.on == true do
                                                    wait(0.2)
                                                
                                                wait(0.1)
                                                local args = {
                                                        [1] = "Slippy Rainbow"
                                                    }
                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                        local args = {
                                                        [1] = "Slippy Rainbow"
                                                    }
                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                
                                                wait(0.1)
                                                
                                                    end
                                                    else
                                                _G.on = false
                                                        
                                                    end
                                                end)

                                                FirstPage.AddToggle("auto dupe Rainbow banana", false, function(Value)
                                                    if Value then
                                                        _G.on = true
                                                        
                                                        while _G.on == true do
                                                            wait(0.2)
                                                        
                                                        wait(0.1)
                                                        local args = {
                                                                [1] = "Rainbow Banana"
                                                            }
                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                local args = {
                                                                [1] = "Rainbow Banana"
                                                            }
                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                        
                                                        wait(0.1)
                                                        
                                                            end
                                                            else
                                                        _G.on = false
                                                                
                                                            end
                                                        end)

                                                        FirstPage.AddToggle("auto dupe gummy rainbow", false, function(Value)
                                                            if Value then
                                                                _G.on = true
                                                                
                                                                while _G.on == true do
                                                                    wait(0.2)
                                                                
                                                                wait(0.1)
                                                                local args = {
                                                                        [1] = "Gummy Rainbow"
                                                                    }
                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                        local args = {
                                                                        [1] = "Gummy Rainbow"
                                                                    }
                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                
                                                                wait(0.1)
                                                                
                                                                    end
                                                                    else
                                                                _G.on = false
                                                                        
                                                                    end
                                                                end)

                                                                FirstPage.AddToggle("auto dupe Gem Rainbow", false, function(Value)
                                                                    if Value then
                                                                        _G.on = true
                                                                        
                                                                        while _G.on == true do
                                                                            wait(0.2)
                                                                        
                                                                        wait(0.1)
                                                                        local args = {
                                                                                [1] = "Gem Rainbow"
                                                                            }
                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                local args = {
                                                                                [1] = "Gem Rainbow"
                                                                            }
                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                        
                                                                        wait(0.1)
                                                                        
                                                                            end
                                                                            else
                                                                        _G.on = false
                                                                                
                                                                            end
                                                                        end)

                                                                        FirstPage.AddToggle("auto dupe muscles", false, function(Value)
                                                                            if Value then
                                                                                _G.on = true
                                                                                
                                                                                while _G.on == true do
                                                                                    wait(0.2)
                                                                                
                                                                                wait(0.1)
                                                                                local args = {
                                                                                        [1] = "muscles"
                                                                                    }
                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                        local args = {
                                                                                        [1] = "muscles"
                                                                                    }
                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                
                                                                                wait(0.1)
                                                                                
                                                                                    end
                                                                                    else
                                                                                _G.on = false
                                                                                        
                                                                                    end
                                                                                end)

                                                                                FirstPage.AddToggle("auto dupe illuminaty", false, function(Value)
                                                                                    if Value then
                                                                                        _G.on = true
                                                                                        
                                                                                        while _G.on == true do
                                                                                            wait(0.2)
                                                                                        
                                                                                        wait(0.1)
                                                                                        local args = {
                                                                                                [1] = "Illuminati"
                                                                                            }
                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                local args = {
                                                                                                [1] = "Illuminati"
                                                                                            }
                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                        
                                                                                        wait(0.1)
                                                                                        
                                                                                            end
                                                                                            else
                                                                                        _G.on = false
                                                                                                
                                                                                            end
                                                                                        end)

                                                                                        FirstPage.AddToggle("auto dupe jet", false, function(Value)
                                                                                            if Value then
                                                                                                _G.on = true
                                                                                                
                                                                                                while _G.on == true do
                                                                                                    wait(0.2)
                                                                                                
                                                                                                wait(0.1)
                                                                                                local args = {
                                                                                                        [1] = "Jet"
                                                                                                    }
                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                        local args = {
                                                                                                        [1] = "Jet"
                                                                                                    }
                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                
                                                                                                wait(0.1)
                                                                                                
                                                                                                    end
                                                                                                    else
                                                                                                _G.on = false
                                                                                                        
                                                                                                    end
                                                                                                end)

                                                                                                FirstPage.AddToggle("auto dupe eTruck", false, function(Value)
                                                                                                    if Value then
                                                                                                        _G.on = true
                                                                                                        
                                                                                                        while _G.on == true do
                                                                                                            wait(0.2)
                                                                                                        
                                                                                                        wait(0.1)
                                                                                                        local args = {
                                                                                                                [1] = "eTruck"
                                                                                                            }
                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                local args = {
                                                                                                                [1] = "eTruck"
                                                                                                            }
                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                        
                                                                                                        wait(0.1)
                                                                                                        
                                                                                                            end
                                                                                                            else
                                                                                                        _G.on = false
                                                                                                                
                                                                                                            end
                                                                                                        end)

                                                                                                        FirstPage.AddToggle("auto dupe shiny Thing", false, function(Value)
                                                                                                            if Value then
                                                                                                                _G.on = true
                                                                                                                
                                                                                                                while _G.on == true do
                                                                                                                    wait(0.2)
                                                                                                                
                                                                                                                wait(0.1)
                                                                                                                local args = {
                                                                                                                        [1] = "shiny Thing"
                                                                                                                    }
                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                        local args = {
                                                                                                                        [1] = "shiny Thing"
                                                                                                                    }
                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                
                                                                                                                wait(0.1)
                                                                                                                
                                                                                                                    end
                                                                                                                    else
                                                                                                                _G.on = false
                                                                                                                        
                                                                                                                    end
                                                                                                                end)

                                                                                                                FirstPage.AddToggle("auto dupe Spidy", false, function(Value)
                                                                                                                    if Value then
                                                                                                                        _G.on = true
                                                                                                                        
                                                                                                                        while _G.on == true do
                                                                                                                            wait(0.2)
                                                                                                                        
                                                                                                                        wait(0.1)
                                                                                                                        local args = {
                                                                                                                                [1] = "Spidy"
                                                                                                                            }
                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                local args = {
                                                                                                                                [1] = "Spidy"
                                                                                                                            }
                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                        
                                                                                                                        wait(0.1)
                                                                                                                        
                                                                                                                            end
                                                                                                                            else
                                                                                                                        _G.on = false
                                                                                                                                
                                                                                                                            end
                                                                                                                        end)

                                                                                                                        
                                                                                                                FirstPage.AddToggle("auto dupe Tulsa Rainbow", false, function(Value)
                                                                                                                    if Value then
                                                                                                                        _G.on = true
                                                                                                                        
                                                                                                                        while _G.on == true do
                                                                                                                            wait(0.2)
                                                                                                                        
                                                                                                                        wait(0.1)
                                                                                                                        local args = {
                                                                                                                                [1] = "Tusla Rainbow"
                                                                                                                            }
                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                local args = {
                                                                                                                                [1] = "Tusla Rainbow"
                                                                                                                            }
                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                        
                                                                                                                        wait(0.1)
                                                                                                                        
                                                                                                                            end
                                                                                                                            else
                                                                                                                        _G.on = false
                                                                                                                                
                                                                                                                            end
                                                                                                                        end)

                                                                                                                        FirstPage.AddToggle("auto dupe Rainbow Scythe", false, function(Value)
                                                                                                                            if Value then
                                                                                                                                _G.on = true
                                                                                                                                
                                                                                                                                while _G.on == true do
                                                                                                                                    wait(0.2)
                                                                                                                                
                                                                                                                                wait(0.1)
                                                                                                                                local args = {
                                                                                                                                        [1] = "Rainbow Scythe"
                                                                                                                                    }
                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                        local args = {
                                                                                                                                        [1] = "Rainbow Scythe"
                                                                                                                                    }
                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                
                                                                                                                                wait(0.1)
                                                                                                                                
                                                                                                                                    end
                                                                                                                                    else
                                                                                                                                _G.on = false
                                                                                                                                        
                                                                                                                                    end
                                                                                                                                end)

                                                                                                                                FirstPage.AddToggle("auto dupe  Light Cube", false, function(Value)
                                                                                                                                    if Value then
                                                                                                                                        _G.on = true
                                                                                                                                        
                                                                                                                                        while _G.on == true do
                                                                                                                                            wait(0.2)
                                                                                                                                        
                                                                                                                                        wait(0.1)
                                                                                                                                        local args = {
                                                                                                                                                [1] = "Light Cube"
                                                                                                                                            }
                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                                local args = {
                                                                                                                                                [1] = "Light Cube"
                                                                                                                                            }
                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                        
                                                                                                                                        wait(0.1)
                                                                                                                                        
                                                                                                                                            end
                                                                                                                                            else
                                                                                                                                        _G.on = false
                                                                                                                                                
                                                                                                                                            end
                                                                                                                                        end)

                                                                                                                                        FirstPage.AddToggle("auto dupe Siren Head", false, function(Value)
                                                                                                                                            if Value then
                                                                                                                                                _G.on = true
                                                                                                                                                
                                                                                                                                                while _G.on == true do
                                                                                                                                                    wait(0.2)
                                                                                                                                                
                                                                                                                                                wait(0.1)
                                                                                                                                                local args = {
                                                                                                                                                        [1] = "Siren Head"
                                                                                                                                                    }
                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                                        local args = {
                                                                                                                                                        [1] = "Siren Head"
                                                                                                                                                    }
                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                
                                                                                                                                                wait(0.1)
                                                                                                                                                
                                                                                                                                                    end
                                                                                                                                                    else
                                                                                                                                                _G.on = false
                                                                                                                                                        
                                                                                                                                                    end
                                                                                                                                                end)

                                                                                                                                                FirstPage.AddToggle("auto dupe  Lightning Katana", false, function(Value)
                                                                                                                                                    if Value then
                                                                                                                                                        _G.on = true
                                                                                                                                                        
                                                                                                                                                        while _G.on == true do
                                                                                                                                                            wait(0.2)
                                                                                                                                                        
                                                                                                                                                        wait(0.1)
                                                                                                                                                        local args = {
                                                                                                                                                                [1] = "Lightning Katana"
                                                                                                                                                            }
                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                                                local args = {
                                                                                                                                                                [1] = "Lightning Katana"
                                                                                                                                                            }
                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                        
                                                                                                                                                        wait(0.1)
                                                                                                                                                        
                                                                                                                                                            end
                                                                                                                                                            else
                                                                                                                                                        _G.on = false
                                                                                                                                                                
                                                                                                                                                            end
                                                                                                                                                        end)

                                                                                                                                                        FirstPage.AddToggle("auto dupe  Tnt", false, function(Value)
                                                                                                                                                            if Value then
                                                                                                                                                                _G.on = true
                                                                                                                                                                
                                                                                                                                                                while _G.on == true do
                                                                                                                                                                    wait(0.2)
                                                                                                                                                                
                                                                                                                                                                wait(0.1)
                                                                                                                                                                local args = {
                                                                                                                                                                        [1] = "TNT"
                                                                                                                                                                    }
                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.Sell:FireServer(unpack(args))
                                                                                                                                                                        local args = {
                                                                                                                                                                        [1] = "TNT"
                                                                                                                                                                    }
                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                
                                                                                                                                                                wait(0.1)
                                                                                                                                                                
                                                                                                                                                                    end
                                                                                                                                                                    else
                                                                                                                                                                _G.on = false
                                                                                                                                                                        
                                                                                                                                                                    end
                                                                                                                                                                end)
                                                                                                                                                                
                                                                                                                                                                                
                                                                                                                                                                local FirstPage = MainUI.AddPage("buy")     
                                                                                                                                                                FirstPage.AddToggle("auto buy ben", false, function(Value)
                                                                                                                                                                    if Value then
                                                                                                                                                                        _G.on = true
                                                                                                                                                                        
                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                            wait(0.00)
                                                                                                                                                                        
                                                                                                                                                                        wait(0.00)
                                                                                                                                                                        local args = {
                                                                                                                                                                                [1] = "Trading Ben"
                                                                                                                                                                            }
                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                local args = {
                                                                                                                                                                                [1] = "Trading Ben"
                                                                                                                                                                            }
                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                        
                                                                                                                                                                        wait(0.00)
                                                                                                                                                                        
                                                                                                                                                                            end
                                                                                                                                                                            else
                                                                                                                                                                        _G.on = false
                                                                                                                                                                                
                                                                                                                                                                            end
                                                                                                                                                                        end)

                                                                                                                                                                        FirstPage.AddToggle("auto buy muneh", false, function(Value)
                                                                                                                                                                            if Value then
                                                                                                                                                                                _G.on = true
                                                                                                                                                                                
                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                    wait(0.0)
                                                                                                                                                                                
                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                local args = {
                                                                                                                                                                                        [1] = "Munneh"
                                                                                                                                                                                    }
                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                        local args = {
                                                                                                                                                                                        [1] = "Munneh"
                                                                                                                                                                                    }
                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                
                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                
                                                                                                                                                                                    end
                                                                                                                                                                                    else
                                                                                                                                                                                _G.on = false
                                                                                                                                                                                        
                                                                                                                                                                                    end
                                                                                                                                                                                end)

                                                                                                                                                                                FirstPage.AddToggle("auto buy Mommeh Long legs", false, function(Value)
                                                                                                                                                                                    if Value then
                                                                                                                                                                                        _G.on = true
                                                                                                                                                                                        
                                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                                            wait(0.00)
                                                                                                                                                                                        
                                                                                                                                                                                        wait(0.000)
                                                                                                                                                                                        local args = {
                                                                                                                                                                                                [1] = "Mommeh Long Legs"
                                                                                                                                                                                            }
                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                local args = {
                                                                                                                                                                                                [1] = "Mommeh Long Legs"
                                                                                                                                                                                            }
                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                        
                                                                                                                                                                                        wait(0.0)
                                                                                                                                                                                        
                                                                                                                                                                                            end
                                                                                                                                                                                            else
                                                                                                                                                                                        _G.on = false
                                                                                                                                                                                                
                                                                                                                                                                                            end
                                                                                                                                                                                        end)

                                                                                                                                                                                        FirstPage.AddToggle("auto buy The banana", false, function(Value)
                                                                                                                                                                                            if Value then
                                                                                                                                                                                                _G.on = true
                                                                                                                                                                                                
                                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                                    wait(0.00)
                                                                                                                                                                                                
                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                local args = {
                                                                                                                                                                                                        [1] = "The banana"
                                                                                                                                                                                                    }
                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                        [1] = "The banana"
                                                                                                                                                                                                    }
                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                
                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                
                                                                                                                                                                                                    end
                                                                                                                                                                                                    else
                                                                                                                                                                                                _G.on = false
                                                                                                                                                                                                        
                                                                                                                                                                                                    end
                                                                                                                                                                                                end)

                                                                                                                                                                                                FirstPage.AddToggle("auto buy pop it rb", false, function(Value)
                                                                                                                                                                                                    if Value then
                                                                                                                                                                                                        _G.on = true
                                                                                                                                                                                                        
                                                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                                                            wait(0.0)
                                                                                                                                                                                                        
                                                                                                                                                                                                        wait(0.0)
                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                [1] = "Pop It Rainbow!"
                                                                                                                                                                                                            }
                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                [1] = "Pop It Rainbow!"
                                                                                                                                                                                                            }
                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                        
                                                                                                                                                                                                        wait(0.0)
                                                                                                                                                                                                        
                                                                                                                                                                                                            end
                                                                                                                                                                                                            else
                                                                                                                                                                                                        _G.on = false
                                                                                                                                                                                                                
                                                                                                                                                                                                            end
                                                                                                                                                                                                        end)

                                                                                                                                                                                                        FirstPage.AddToggle("auto buy lolly", false, function(Value)
                                                                                                                                                                                                            if Value then
                                                                                                                                                                                                                _G.on = true
                                                                                                                                                                                                                
                                                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                                                    wait(0.00)
                                                                                                                                                                                                                
                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                        [1] = "Lolly Rainbow"
                                                                                                                                                                                                                    }
                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                        [1] = "Lolly Rainbow"
                                                                                                                                                                                                                    }
                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                
                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                
                                                                                                                                                                                                                    end
                                                                                                                                                                                                                    else
                                                                                                                                                                                                                _G.on = false
                                                                                                                                                                                                                        
                                                                                                                                                                                                                    end
                                                                                                                                                                                                                end)

                                                                                                                                                                                                                FirstPage.AddToggle("auto buy AMOGUS", false, function(Value)
                                                                                                                                                                                                                    if Value then
                                                                                                                                                                                                                        _G.on = true
                                                                                                                                                                                                                        
                                                                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                                                                            wait(0.00)
                                                                                                                                                                                                                        
                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                [1] = "Amogus Rainbow"
                                                                                                                                                                                                                            }
                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                [1] = "Amogus Rainbow"
                                                                                                                                                                                                                            }
                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                        
                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                        
                                                                                                                                                                                                                            end
                                                                                                                                                                                                                            else
                                                                                                                                                                                                                        _G.on = false
                                                                                                                                                                                                                                
                                                                                                                                                                                                                            end
                                                                                                                                                                                                                        end)

                                                                                                                                                                                                                        FirstPage.AddToggle("auto buy Crystal Rainbow", false, function(Value)
                                                                                                                                                                                                                            if Value then
                                                                                                                                                                                                                                _G.on = true
                                                                                                                                                                                                                                
                                                                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                                                                    wait(0.00)
                                                                                                                                                                                                                                
                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                        [1] = "Crystal Rainbow"
                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                        [1] = "Crystal Rainbow"
                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                
                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                
                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                    else
                                                                                                                                                                                                                                _G.on = false
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                end)

                                                                                                                                                                                                                                FirstPage.AddToggle("auto buy Slippy Rainbow", false, function(Value)
                                                                                                                                                                                                                                    if Value then
                                                                                                                                                                                                                                        _G.on = true
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                                                                                            wait(0.00)
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                                [1] = "Slippy Rainbow"
                                                                                                                                                                                                                                            }
                                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                                [1] = "Slippy Rainbow"
                                                                                                                                                                                                                                            }
                                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                            end
                                                                                                                                                                                                                                            else
                                                                                                                                                                                                                                        _G.on = false
                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                            end
                                                                                                                                                                                                                                        end)

                                                                                                                                                                                                                                        FirstPage.AddToggle("auto buy Rainbow Banana", false, function(Value)
                                                                                                                                                                                                                                            if Value then
                                                                                                                                                                                                                                                _G.on = true
                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                                                                                    wait(0.00)
                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                                        [1] = "Rainbow Banana"
                                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                                        [1] = "Rainbow Banana"
                                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                                    else
                                                                                                                                                                                                                                                _G.on = false
                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                                end)

                                                                                                                                                                                                                                                FirstPage.AddToggle("auto buy Gummy Rainbow", false, function(Value)
                                                                                                                                                                                                                                                    if Value then
                                                                                                                                                                                                                                                        _G.on = true
                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                        while _G.on == true do
                                                                                                                                                                                                                                                            wait(0.00)
                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                                                [1] = "Gummy Rainbow"
                                                                                                                                                                                                                                                            }
                                                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                                                [1] = "Gummy Rainbow"
                                                                                                                                                                                                                                                            }
                                                                                                                                                                                                                                                            game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                        wait(0.00)
                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                            end
                                                                                                                                                                                                                                                            else
                                                                                                                                                                                                                                                        _G.on = false
                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                            end
                                                                                                                                                                                                                                                        end)

                                                                                                                                                                                                                                                        FirstPage.AddToggle("auto buy Gem Rainbow", false, function(Value)
                                                                                                                                                                                                                                                            if Value then
                                                                                                                                                                                                                                                                _G.on = true
                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                while _G.on == true do
                                                                                                                                                                                                                                                                    wait(0.00)
                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                                                local args = {
                                                                                                                                                                                                                                                                        [1] = "Gem Rainbow"
                                                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                                        local args = {
                                                                                                                                                                                                                                                                        [1] = "Gem Rainbow"
                                                                                                                                                                                                                                                                    }
                                                                                                                                                                                                                                                                    game:GetService("ReplicatedStorage").RemoteEvents.BuyItemCash:FireServer(unpack(args))
                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                wait(0.00)
                                                                                                                                                                                                                                                                
                                                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                                                    else
                                                                                                                                                                                                                                                                _G.on = false
                                                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                                                    end
                                                                                                                                                                                                                                                                end)

                                                                                                                                                                                                            local FirstPage = MainUI.AddPage("Scripts")
                                                                                                                                                                                                            FirstPage.AddButton("inf yeld", function()
                                                                                                                                                                                                            loadstring(game:HttpGet('https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source'))()
                                                                                                                                                                                                            end)

                                                                                                                                                                                                            FirstPage.AddButton("scam v1", function()
                                                                                                                                                                                                             loadstring(game:HttpGet(('https://raw.githubusercontent.com/imaboy12321/shhh/main/gaey'),true))()
                                                                                                                                                                                                            end)

                                                                                                                                                                                                            FirstPage.AddButton("scam v2", function()
                                                                                                                                                                                                               loadstring("\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\88\82\97\121\46\86\97\108\117\101\32\61\32\116\114\117\101\10\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\10\9\119\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\79\102\67\108\97\115\115\40\39\84\101\114\114\97\105\110\39\41\46\87\97\116\101\114\87\97\118\101\83\105\122\101\32\61\32\48\10\9\119\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\79\102\67\108\97\115\115\40\39\84\101\114\114\97\105\110\39\41\46\87\97\116\101\114\87\97\118\101\83\112\101\101\100\32\61\32\48\10\9\119\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\79\102\67\108\97\115\115\40\39\84\101\114\114\97\105\110\39\41\46\87\97\116\101\114\82\101\102\108\101\99\116\97\110\99\101\32\61\32\48\10\9\119\111\114\107\115\112\97\99\101\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\79\102\67\108\97\115\115\40\39\84\101\114\114\97\105\110\39\41\46\87\97\116\101\114\84\114\97\110\115\112\97\114\101\110\99\121\32\61\32\48\10\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\76\105\103\104\116\105\110\103\34\41\46\71\108\111\98\97\108\83\104\97\100\111\119\115\32\61\32\102\97\108\115\101\10\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\76\105\103\104\116\105\110\103\34\41\46\70\111\103\69\110\100\32\61\32\57\101\57\10\9\115\101\116\116\105\110\103\115\40\41\46\82\101\110\100\101\114\105\110\103\46\81\117\97\108\105\116\121\76\101\118\101\108\32\61\32\49\10\9\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\103\97\109\101\58\71\101\116\68\101\115\99\101\110\100\97\110\116\115\40\41\41\32\100\111\10\9\9\105\102\32\118\58\73\115\65\40\34\80\97\114\116\34\41\32\111\114\32\118\58\73\115\65\40\34\85\110\105\111\110\79\112\101\114\97\116\105\111\110\34\41\32\111\114\32\118\58\73\115\65\40\34\77\101\115\104\80\97\114\116\34\41\32\111\114\32\118\58\73\115\65\40\34\67\111\114\110\101\114\87\101\100\103\101\80\97\114\116\34\41\32\111\114\32\118\58\73\115\65\40\34\84\114\117\115\115\80\97\114\116\34\41\32\116\104\101\110\10\9\9\9\118\46\77\97\116\101\114\105\97\108\32\61\32\34\80\108\97\115\116\105\99\34\10\9\9\9\118\46\82\101\102\108\101\99\116\97\110\99\101\32\61\32\48\10\9\9\101\108\115\101\105\102\32\118\58\73\115\65\40\34\68\101\99\97\108\34\41\32\116\104\101\110\10\9\9\9\118\46\84\114\97\110\115\112\97\114\101\110\99\121\32\61\32\49\10\9\9\101\108\115\101\105\102\32\118\58\73\115\65\40\34\80\97\114\116\105\99\108\101\69\109\105\116\116\101\114\34\41\32\111\114\32\118\58\73\115\65\40\34\84\114\97\105\108\34\41\32\116\104\101\110\10\9\9\9\118\46\76\105\102\101\116\105\109\101\32\61\32\78\117\109\98\101\114\82\97\110\103\101\46\110\101\119\40\48\41\10\9\9\101\108\115\101\105\102\32\118\58\73\115\65\40\34\69\120\112\108\111\115\105\111\110\34\41\32\116\104\101\110\10\9\9\9\118\46\66\108\97\115\116\80\114\101\115\115\117\114\101\32\61\32\49\10\9\9\9\118\46\66\108\97\115\116\82\97\100\105\117\115\32\61\32\49\10\9\9\101\110\100\10\9\101\110\100\10\9\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\76\105\103\104\116\105\110\103\34\41\58\71\101\116\68\101\115\99\101\110\100\97\110\116\115\40\41\41\32\100\111\10\9\9\105\102\32\118\58\73\115\65\40\34\66\108\117\114\69\102\102\101\99\116\34\41\32\111\114\32\118\58\73\115\65\40\34\83\117\110\82\97\121\115\69\102\102\101\99\116\34\41\32\111\114\32\118\58\73\115\65\40\34\67\111\108\111\114\67\111\114\114\101\99\116\105\111\110\69\102\102\101\99\116\34\41\32\111\114\32\118\58\73\115\65\40\34\66\108\111\111\109\69\102\102\101\99\116\34\41\32\111\114\32\118\58\73\115\65\40\34\68\101\112\116\104\79\102\70\105\101\108\100\69\102\102\101\99\116\34\41\32\116\104\101\110\10\9\9\9\118\46\69\110\97\98\108\101\100\32\61\32\102\97\108\115\101\10\9\9\101\110\100\10\9\101\110\100\10\9\119\111\114\107\115\112\97\99\101\46\68\101\115\99\101\110\100\97\110\116\65\100\100\101\100\58\67\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\99\104\105\108\100\41\10\9\9\99\111\114\111\117\116\105\110\101\46\119\114\97\112\40\102\117\110\99\116\105\111\110\40\41\10\9\9\9\105\102\32\99\104\105\108\100\58\73\115\65\40\39\70\111\114\99\101\70\105\101\108\100\39\41\32\116\104\101\110\10\9\9\9\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\39\82\117\110\83\101\114\118\105\99\101\39\41\46\72\101\97\114\116\98\101\97\116\58\87\97\105\116\40\41\10\9\9\9\9\99\104\105\108\100\58\68\101\115\116\114\111\121\40\41\10\9\9\9\101\108\115\101\105\102\32\99\104\105\108\100\58\73\115\65\40\39\83\112\97\114\107\108\101\115\39\41\32\116\104\101\110\10\9\9\9\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\39\82\117\110\83\101\114\118\105\99\101\39\41\46\72\101\97\114\116\98\101\97\116\58\87\97\105\116\40\41\10\9\9\9\9\99\104\105\108\100\58\68\101\115\116\114\111\121\40\41\10\9\9\9\101\108\115\101\105\102\32\99\104\105\108\100\58\73\115\65\40\39\83\109\111\107\101\39\41\32\111\114\32\99\104\105\108\100\58\73\115\65\40\39\70\105\114\101\39\41\32\116\104\101\110\10\9\9\9\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\39\82\117\110\83\101\114\118\105\99\101\39\41\46\72\101\97\114\116\98\101\97\116\58\87\97\105\116\40\41\10\9\9\9\9\99\104\105\108\100\58\68\101\115\116\114\111\121\40\41\10\9\9\9\101\110\100\10\9\9\101\110\100\41\40\41\10\9\101\110\100\41\10\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\45\10\108\111\99\97\108\32\83\99\114\101\101\110\71\117\105\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\83\99\114\101\101\110\71\117\105\34\41\10\108\111\99\97\108\32\70\114\97\109\101\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\70\114\97\109\101\34\41\10\108\111\99\97\108\32\84\101\120\116\76\97\98\101\108\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\76\97\98\101\108\34\41\10\108\111\99\97\108\32\120\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\65\110\116\105\75\105\99\107\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\71\111\100\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\65\110\116\105\66\108\105\110\100\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\65\110\116\105\66\101\97\114\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\73\116\101\109\115\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\66\117\116\116\111\110\34\41\10\108\111\99\97\108\32\84\101\120\116\76\97\98\101\108\95\50\32\61\32\73\110\115\116\97\110\99\101\46\110\101\119\40\34\84\101\120\116\76\97\98\101\108\34\41\10\10\45\45\80\114\111\112\101\114\116\105\101\115\58\10\10\83\99\114\101\101\110\71\117\105\46\80\97\114\101\110\116\32\61\32\103\97\109\101\46\67\111\114\101\71\117\105\10\10\70\114\97\109\101\46\80\97\114\101\110\116\32\61\32\83\99\114\101\101\110\71\117\105\10\70\114\97\109\101\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\57\44\32\50\57\44\32\50\57\41\10\70\114\97\109\101\46\66\111\114\100\101\114\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\57\44\32\50\57\44\32\50\57\41\10\70\114\97\109\101\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\48\57\57\50\49\54\55\48\55\49\44\32\48\44\32\48\46\50\48\52\51\54\53\48\55\53\44\32\48\41\10\70\114\97\109\101\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\48\44\32\48\44\32\48\41\10\70\114\97\109\101\46\65\99\116\105\118\101\32\61\32\116\114\117\101\10\70\114\97\109\101\46\68\114\97\103\103\97\98\108\101\32\61\32\116\114\117\101\10\10\65\110\116\105\75\105\99\107\46\78\97\109\101\32\61\32\34\65\110\116\105\32\75\105\99\107\34\10\65\110\116\105\75\105\99\107\46\80\97\114\101\110\116\32\61\32\70\114\97\109\101\10\65\110\116\105\75\105\99\107\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\65\110\116\105\75\105\99\107\46\66\111\114\100\101\114\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\65\110\116\105\75\105\99\107\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\48\52\56\48\52\50\55\50\57\53\44\32\50\48\48\44\32\48\46\50\57\57\54\54\51\51\48\53\44\32\48\41\10\65\110\116\105\75\105\99\107\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\49\49\53\44\32\48\44\32\53\48\41\10\65\110\116\105\75\105\99\107\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\79\115\119\97\108\100\10\65\110\116\105\75\105\99\107\46\84\101\120\116\32\61\32\34\84\111\103\103\108\101\34\10\65\110\116\105\75\105\99\107\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\53\53\44\32\50\53\53\44\32\50\53\53\41\10\65\110\116\105\75\105\99\107\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\65\110\116\105\75\105\99\107\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\65\110\116\105\75\105\99\107\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\65\110\116\105\75\105\99\107\46\68\114\97\103\103\97\98\108\101\32\61\32\116\114\117\101\10\65\110\116\105\75\105\99\107\46\77\111\117\115\101\66\117\116\116\111\110\49\68\111\119\110\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\108\111\99\97\108\32\98\117\116\116\111\110\112\117\115\104\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\80\108\97\121\101\114\83\99\114\105\112\116\115\46\66\117\116\116\111\110\80\117\115\104\10\10\116\111\103\103\108\101\32\61\32\110\111\116\32\116\111\103\103\108\101\10\10\105\102\32\116\111\103\103\108\101\32\61\61\32\116\114\117\101\32\116\104\101\110\10\98\117\116\116\111\110\112\117\115\104\46\68\105\115\97\98\108\101\100\32\61\32\116\114\117\101\10\65\110\116\105\75\105\99\107\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\48\44\32\50\53\53\44\32\51\49\41\10\103\101\116\103\101\110\118\40\41\46\116\112\116\111\103\103\108\101\32\61\32\116\114\117\101\10\10\108\111\99\97\108\32\112\97\100\32\61\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\66\111\97\114\100\115\10\108\111\99\97\108\32\108\112\108\114\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\10\108\111\99\97\108\32\112\108\114\32\61\32\103\97\109\101\46\80\108\97\121\101\114\115\46\76\111\99\97\108\80\108\97\121\101\114\46\67\104\97\114\97\99\116\101\114\46\72\117\109\97\110\111\105\100\82\111\111\116\80\97\114\116\10\108\111\99\97\108\32\100\114\111\112\32\61\32\103\97\109\101\46\87\111\114\107\115\112\97\99\101\46\68\114\111\112\112\101\100\10\10\119\104\105\108\101\32\116\112\116\111\103\103\108\101\32\61\61\32\116\114\117\101\32\100\111\10\102\111\114\32\105\44\118\32\105\110\32\112\97\105\114\115\40\112\97\100\58\71\101\116\67\104\105\108\100\114\101\110\40\41\41\32\100\111\10\105\102\32\118\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\40\34\80\108\97\121\101\114\49\34\41\32\97\110\100\32\118\58\70\105\110\100\70\105\114\115\116\67\104\105\108\100\40\34\80\108\97\121\101\114\50\34\41\32\116\104\101\110\10\105\102\32\118\46\80\108\97\121\101\114\49\46\86\97\108\117\101\32\61\61\32\108\112\108\114\32\111\114\32\118\46\80\108\97\121\101\114\50\46\86\97\108\117\101\32\61\61\32\108\112\108\114\32\116\104\101\110\10\105\102\32\118\46\80\108\97\121\101\114\49\46\86\97\108\117\101\32\126\61\32\108\112\108\114\32\97\110\100\32\118\46\80\108\97\121\101\114\49\65\99\116\105\111\110\46\86\97\108\117\101\32\61\61\32\34\68\111\110\101\34\32\111\114\32\118\46\80\108\97\121\101\114\50\46\86\97\108\117\101\32\126\61\32\108\112\108\114\32\97\110\100\32\118\46\80\108\97\121\101\114\50\65\99\116\105\111\110\46\86\97\108\117\101\32\61\61\32\34\68\111\110\101\34\32\116\104\101\110\10\102\111\114\32\105\44\118\53\32\105\110\32\112\97\105\114\115\40\100\114\111\112\58\71\101\116\67\104\105\108\100\114\101\110\40\41\41\32\100\111\10\105\102\32\118\53\46\79\119\110\101\114\46\86\97\108\117\101\32\61\61\32\108\112\108\114\32\116\104\101\110\10\112\108\114\46\67\70\114\97\109\101\32\61\32\118\46\67\111\110\116\114\111\108\115\46\67\108\111\115\101\46\80\97\114\116\46\67\70\114\97\109\101\10\119\97\105\116\40\48\46\50\41\10\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\82\101\109\111\116\101\69\118\101\110\116\115\46\74\117\109\112\101\100\58\70\105\114\101\83\101\114\118\101\114\40\41\10\119\97\105\116\40\48\46\49\52\41\10\98\117\116\116\111\110\112\117\115\104\46\68\105\115\97\98\108\101\100\32\61\32\102\97\108\115\101\10\112\108\114\46\67\70\114\97\109\101\32\61\32\118\46\67\111\110\116\114\111\108\115\46\68\111\110\101\46\80\97\114\116\46\67\70\114\97\109\101\10\119\97\105\116\40\48\46\50\41\10\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\82\101\112\108\105\99\97\116\101\100\83\116\111\114\97\103\101\34\41\46\82\101\109\111\116\101\69\118\101\110\116\115\46\74\117\109\112\101\100\58\70\105\114\101\83\101\114\118\101\114\40\41\10\116\111\103\103\108\101\32\61\32\102\97\108\115\101\10\65\110\116\105\75\105\99\107\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\53\53\44\32\48\44\32\48\41\10\103\101\116\103\101\110\118\40\41\46\116\112\116\111\103\103\108\101\32\61\32\102\97\108\115\101\10\101\110\100\10\101\110\100\10\101\110\100\10\101\110\100\10\101\110\100\10\101\110\100\10\119\97\105\116\40\41\10\101\110\100\10\101\108\115\101\105\102\32\116\111\103\103\108\101\32\61\61\32\102\97\108\115\101\32\116\104\101\110\10\98\117\116\116\111\110\112\117\115\104\46\68\105\115\97\98\108\101\100\32\61\32\102\97\108\115\101\10\65\110\116\105\75\105\99\107\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\53\53\44\32\48\44\32\48\41\10\103\101\116\103\101\110\118\40\41\46\116\112\116\111\103\103\108\101\32\61\32\102\97\108\115\101\10\101\110\100\10\101\110\100\41\10\10\71\111\100\46\80\97\114\101\110\116\32\61\32\70\114\97\109\101\10\71\111\100\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\71\111\100\46\66\111\114\100\101\114\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\71\111\100\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\51\57\54\55\57\55\50\49\44\32\49\48\48\48\44\32\48\46\50\57\57\54\54\51\51\48\53\44\32\48\41\10\71\111\100\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\49\49\53\44\32\48\44\32\53\48\41\10\71\111\100\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\79\115\119\97\108\100\10\71\111\100\46\84\101\120\116\32\61\32\34\72\111\112\34\10\71\111\100\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\53\53\44\32\50\53\53\44\32\50\53\53\41\10\71\111\100\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\71\111\100\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\71\111\100\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\71\111\100\46\77\111\117\115\101\66\117\116\116\111\110\49\68\111\119\110\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\9\108\111\99\97\108\32\120\32\61\32\123\125\10\9\102\111\114\32\95\44\32\118\32\105\110\32\105\112\97\105\114\115\40\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\72\116\116\112\83\101\114\118\105\99\101\34\41\58\74\83\79\78\68\101\99\111\100\101\40\103\97\109\101\58\72\116\116\112\71\101\116\65\115\121\110\99\40\34\104\116\116\112\115\58\47\47\103\97\109\101\115\46\114\111\98\108\111\120\46\99\111\109\47\118\49\47\103\97\109\101\115\47\34\32\46\46\32\103\97\109\101\46\80\108\97\99\101\73\100\32\46\46\32\34\47\115\101\114\118\101\114\115\47\80\117\98\108\105\99\63\115\111\114\116\79\114\100\101\114\61\65\115\99\38\108\105\109\105\116\61\49\48\48\34\41\41\46\100\97\116\97\41\32\100\111\10\9\9\105\102\32\116\121\112\101\40\118\41\32\61\61\32\34\116\97\98\108\101\34\32\97\110\100\32\118\46\109\97\120\80\108\97\121\101\114\115\32\62\32\118\46\112\108\97\121\105\110\103\32\97\110\100\32\118\46\105\100\32\126\61\32\103\97\109\101\46\74\111\98\73\100\32\116\104\101\110\10\9\9\9\120\91\35\120\32\43\32\49\93\32\61\32\118\46\105\100\10\9\9\101\110\100\10\9\101\110\100\10\9\105\102\32\35\120\32\62\32\48\32\116\104\101\110\10\9\9\103\97\109\101\58\71\101\116\83\101\114\118\105\99\101\40\34\84\101\108\101\112\111\114\116\83\101\114\118\105\99\101\34\41\58\84\101\108\101\112\111\114\116\84\111\80\108\97\99\101\73\110\115\116\97\110\99\101\40\103\97\109\101\46\80\108\97\99\101\73\100\44\32\120\91\109\97\116\104\46\114\97\110\100\111\109\40\49\44\32\35\120\41\93\41\10\9\101\108\115\101\10\9\9\114\101\116\117\114\110\32\110\111\116\105\102\121\40\34\83\101\114\118\101\114\104\111\112\34\44\34\67\111\117\108\100\110\39\116\32\102\105\110\100\32\97\32\115\101\114\118\101\114\46\34\41\10\9\101\110\100\10\101\110\100\41\10\10\120\46\78\97\109\101\32\61\32\34\120\34\10\120\46\80\97\114\101\110\116\32\61\32\70\114\97\109\101\10\120\46\66\97\99\107\103\114\111\117\110\100\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\120\46\66\111\114\100\101\114\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\51\54\44\32\51\54\44\32\51\54\41\10\120\46\80\111\115\105\116\105\111\110\32\61\32\85\68\105\109\50\46\110\101\119\40\48\46\56\54\52\55\54\56\54\56\52\44\32\48\44\32\48\44\32\48\41\10\120\46\83\105\122\101\32\61\32\85\68\105\109\50\46\110\101\119\40\48\44\32\55\54\44\32\48\44\32\53\48\41\10\120\46\70\111\110\116\32\61\32\69\110\117\109\46\70\111\110\116\46\79\115\119\97\108\100\10\120\46\84\101\120\116\32\61\32\34\88\34\10\120\46\84\101\120\116\67\111\108\111\114\51\32\61\32\67\111\108\111\114\51\46\102\114\111\109\82\71\66\40\50\53\53\44\32\50\53\53\44\32\50\53\53\41\10\120\46\84\101\120\116\83\99\97\108\101\100\32\61\32\116\114\117\101\10\120\46\84\101\120\116\83\105\122\101\32\61\32\49\52\46\48\48\48\10\120\46\84\101\120\116\87\114\97\112\112\101\100\32\61\32\116\114\117\101\10\120\46\68\114\97\103\103\97\98\108\101\32\61\32\116\114\117\101\10\120\46\77\111\117\115\101\66\117\116\116\111\110\49\68\111\119\110\58\99\111\110\110\101\99\116\40\102\117\110\99\116\105\111\110\40\41\10\9\103\97\109\101\46\67\111\114\101\71\117\105\46\83\99\114\101\101\110\71\117\105\58\68\101\115\116\114\111\121\40\41\10\101\110\100\41\10")()
                                                                                                                                                                                                               end)

                               

                                                                                                                                                                                                      local      FirstPage = MainUI.AddPage("drop")
                                                                                                                                                                                                      FirstPage.AddButton("Drop Ben",function()
                                                                                                                                                                                                        getgenv().item_name = "Trading Ben"
                                                                                                                                                                                                        loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                        end)

                                                                                                                                                                                                        
                                                                                                                                                                                                        FirstPage.AddButton("Drop Munehh",function()
                                                                                                                                                                                                          getgenv().item_name = "Munneh"
                                                                                                                                                                                                          loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                          end)

                                                                                                                                                                                                          FirstPage.AddButton("Drop Momeh",function()
                                                                                                                                                                                                            getgenv().item_name = "Mommeh Long Legs"
                                                                                                                                                                                                            loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                            end)

                                                                                                                                                                                                            FirstPage.AddButton("Drop The banana",function()
                                                                                                                                                                                                                getgenv().item_name = "The banana"
                                                                                                                                                                                                                loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                end)

                                                                                                                                                                                                                FirstPage.AddButton("Drop Pop it rb",function()
                                                                                                                                                                                                                    getgenv().item_name = "Pop It Rainbow!"
                                                                                                                                                                                                                    loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                    end)

                                                                                                                                                                                                                    FirstPage.AddButton("Drop Lolli Rb",function()
                                                                                                                                                                                                                        getgenv().item_name = "Lolly Rainbow"
                                                                                                                                                                                                                        loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                        end)

                                                                                                                                                                                                                        FirstPage.AddButton("Drop Amogus Rainbow",function()
                                                                                                                                                                                                                            getgenv().item_name = "Amogus Rainbow"
                                                                                                                                                                                                                            loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                            end)

                                                                                                                                                                                                                            FirstPage.AddButton("Drop Crystal Rainbow",function()
                                                                                                                                                                                                                                getgenv().item_name = "Crystal Rainbow"
                                                                                                                                                                                                                                loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                                end)

                                                                                                                                                                                                                                FirstPage.AddButton("Drop banana Rainbow",function()
                                                                                                                                                                                                                                    getgenv().item_name = " Rainbow Banana"
                                                                                                                                                                                                                                    loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                                    
                                                                                                                                                                                                                                    end)

                                                                                                                                                                                       
                                                                                                                                                                                                                                    FirstPage.AddButton("Gummy rainbow drop",function()
                                                                                                                                                                                                                                        getgenv().item_name = "Gummy Rainbow"
                                                                                                                                                                                                                                        loadstring(game:HttpGet('https://raw.githubusercontent.com/THEBESTHAGEG/LOLOLO/main/README.md'))()
                                                                                                                                                                                                                                        
                                                                                                                                                                                                                                        end)






                                                                                                                                                                                                                                    
                                                    
              
                                                                                                                                                                                                                            
