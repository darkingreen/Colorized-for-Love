# Colorized-for-Love
this library for lua help to load a array of r[1], g[2], b[3], a[4] for implement colors in your project
an examle:
````lua
  require("colorized")
  love.draw()
    love.graphics.setBackgroundColor(hex("#fff")) --this will go turn the background into white and 1 of alpha
    love.graphics.setColor(rgba(255, 140, 10)) --a type of orange i think
    love.graphics.setColor(vec4(0, 0, 50, 0.5)) --dark blue with parcial alpha
    love.graphics.setColor(hex("#a2f5a1")) --i dont know ;D
  end
````

future implementations:
  -hsva
  -hsla
