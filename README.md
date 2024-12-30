# GameboyVramTileViewer
Gameboy VRAM Tile Viewer

Couldn't find anything to debug my Gameboy emulator's VRAM tiles so I made this.

Renders bytes from the input file as Gameboy tiles.
16 tiles per row. 24 tiles per column. 384 tiles total. 
Expects a Gameboy VRAM tile dump. (8000-97FF) 
Give it a 6,144 byte file or don't. What do I care?

It does gracefully render *any* input file, no matter the size - just for fun.

Extremely compact - less than 200 lines in a single file with human readable formatting.

Live version: https://dtabacaru.com/vram

Cheers