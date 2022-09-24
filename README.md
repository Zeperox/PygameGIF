# A .gif loader for Pygame

A tool to make loading .gif files in pygame easier

```py
import PygameGIF
loaded_gif = PygameGIF.load("path.gif") # loads the .gif file

# inside the game loop
loaded_gif.render(surface, (x, y)) # renders and animates the .gif file. DO NOT USE `surface.blit` TO RENDER THE .gif FILE
```
You can use other functions like `loaded_gif.convert()` or `loaded_gif.get_surf()`
