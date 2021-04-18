# vanillaui-edit-jt
Hello! This is a edit of Vanillas UI which includes
~ sub menus
~ some buttons
~ different height / width
~ ON / OFF checkboxes, rather than a big rectangle.

-- [ BUTTON EXAMPLE ] --
UI.Button("Refill Health", Vec2(100, 20), function()
  SetEntityHealth(PlayerPedId(-1), 200)
end)

-- [ CHECK BOX EXAMPLE ] --
  UI.Button("Godmode", Vec2(100, 20), function() godmode = not godmode SetEntityInvincible(player, godmode) end, nil, nil, nil, true, godmode)
  
 NOTE: If you'd like a certain button within a certain submenu make sure the code is before the end & under the "if IsSubMenuOpen("subMenuName") then
 
 If you can't figure out the rest, I'm concerned..
