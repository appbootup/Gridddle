# Gridddle
Grid module for FramerJS

![Grid module for FramerJS](/gridddle.png)

## Lyrics
Sometimes I create a layout for my prototype directly in FramerJS. Since I am used to design a layout with a grid (this is the most important and useful design tool) in my visual editor (Sketch) I decided to create a grid module for my favorite prototyping tool.

## How to use it

1. Download gridddle.coffee;
2. Put it into module folder of your FramerJS project;
3. Connect gridddle to your code.

## How to connect and launch it

```coffeescript
# Connect gridddle module
module = require "gridddle"

# Define amount of cell and grid color
amountOfCell = 16
gridColor = "rgba(226, 74, 74, .5)"

# Call gridddle and pass it out gridddle settings
module.gridddle(amountOfCell, gridColor)
```

## Who is who here

**amountOfCell** defines amount of horizontal cell.

**gridColor** sets color for our grid.

![Grid module for FramerJS](/gridddle.gif)
