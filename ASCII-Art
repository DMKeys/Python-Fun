#    ____                _            _    ____   ____ ___ ___      _         _   
#   / ___|_ __ ___  __ _| |_ ___     / \  / ___| / ___|_ _|_ _|    / \   _ __| |_ 
#  | |   | '__/ _ \/ _` | __/ _ \   / _ \ \___ \| |    | | | |    / _ \ | '__| __|
#  | |___| | |  __/ (_| | ||  __/  / ___ \ ___) | |___ | | | |   / ___ \| |  | |_ 
#   \____|_|  \___|\__,_|\__\___| /_/   \_\____/ \____|___|___| /_/   \_\_|   \__|
#                                                                               
#  __        ___ _   _       ____        _   _                 _ 
#  \ \      / (_) |_| |__   |  _ \ _   _| |_| |__   ___  _ __ | |
#   \ \ /\ / /| | __| '_ \  | |_) | | | | __| '_ \ / _ \| '_ \| |
#    \ V  V / | | |_| | | | |  __/| |_| | |_| | | | (_) | | | |_|
#     \_/\_/  |_|\__|_| |_| |_|    \__, |\__|_| |_|\___/|_| |_(_) 
#                                  |___/                             By: DMKeys


# To Use A Differant Font Then The One From Below, Just Change The Name Of The "font_selection" String Variable To One Of The Font Names In The "Font-Example.txt" File In The Repo.

# Happy ASCII Arting!!!

#!/usr/bin/env python3

# PyFiglet Library Import
from pyfiglet import figlet_format

# User Instruction
print("\n")
print("Input text to be converted to ASCII Art?")

# User Input Text to Be Converted To ASCII Art
input_text = input("[---->]: ")
print("\n")

# Font Selection
font_selection = "standard"

# Format User Input To Be Converted
art_text =figlet_format(input_text, font=font_selection)

# Name Output File
print("Name For Output File? ")

# Output Filename
output_filename = input("[---->]:")
output_filename_full = str(output_filename+".txt")

# Create Output File
f = open(output_filename_full, 'a')

# Write Output File
f.write(art_text)

# Close Output File
f.close()

# Print Name Of Output File To Terminal
print("\n")
print("Successfully Created File: ", output_filename_full)
