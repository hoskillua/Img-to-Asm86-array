This script is used to extract pixel data (24-bit RGB) out of images, map it into 256-color VGA palette in asm, and out put it as a string formatted as asm 86 array to be pasted in the asm code
This works well with the TASM/MASM Extention for VS CODE

# Used palette: https://upload.wikimedia.org/wikipedia/commons/thumb/6/66/VGA_palette_with_black_borders.svg/1200px-VGA_palette_with_black_borders.svg.png
# This palette is the default 256 colors in the Tasm/Masm Extension for VS code, Note that the original asm86 only supported the first 16 colors
# So make sure while drawing your art to pick (via color picker) from this palette, btw: Krita(~30mb) is a great and easy app for creating pixel art:
# How to set up Krita for pixel art(5 mins): https://www.youtube.com/watch?v=aaRzNTCanIQ
# Nice Pixel art tutorials playlist (each video is 5~15 mins): https://www.youtube.com/playlist?list=PLmac3HPrav-9UWt-ahViIZxpyQxJ2wPSH
