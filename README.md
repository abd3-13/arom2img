# arom2img
Android ROM zip files extract and decompress the dat to img

# Orignal Work
This script is for a linux OS and is based on the work of [Andrei Conache](https://github.com/xpirt/sdat2img)

# Requirements
This script requires Python 2.7 or newer installed on your system.
Other requirements are checked by the script

# Usage
Script creates a folder with the 4 initial letter of the rom file followed by a random number in the current working dir that contains the sparse img files.


    #if script is added to PATH
    arom2img android_rom_file.zip
    
    #run from current dir
    ./arom2img android_rom_file.zip
    
    #run with bash
    bash arom2img android_rom_file.zip
