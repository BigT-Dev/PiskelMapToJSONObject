# PiskelMapToJSONObject

## Why ?
During a game Jam my team and i used piskel for the sprites and a map. But we didn't have a game engine.
So we have to detect and handle collision ourself. Furthermore we had to define every wall and other stuff wich the player wasn't able to go trough.

So I wrote this little convertor.

## How to use it ?
Well you have to create a new layer on top of you current map. Draw in black every shape where the player won't be able to go.
Download the new layer as .c file. Copy it in the Convertissor folder. Rename it map.py. Refactor the C code into python code.
Fillay set the global in converter.py to the value find in the top of the C file.

Enter the command : 'python3 converter.py'
Then you'll have a file called 'rectangle.json'.

## Contribuate ?
If for some reason you wan't to contribute, feel free to do so.
Have a great day !