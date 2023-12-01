# extract_msx_font
jupyter notebook to extract the fonts from msx system ROMs

You must use the BASIC roms. Just put .ROM files in the rom/ directory as the notebook and run it. It will produce png images in the images/ directory.

I added a hardcoded exception for the ax170_arabic.rom. Others will grab data from CGTABL (0x0004) variable inside the ROM.

