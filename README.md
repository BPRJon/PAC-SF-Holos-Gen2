# PAC > SF Holos Gen2
Two Starfall chips to allow you to convert a PAC3 to Holos able to be used for holomechs. This isn't made to take a character PAC and convert it to SF unfortately, just to make the process of creating Holomechs in Starfall a lot easier

# How to use
[Here](https://youtu.be/26LFWriORqQ) is a link to a youtube video of me using the chips.

## Holo Translator V2
- Line 6 has a variable called path, set the string inside to the path to your PAC file relative to the `/garrysmod/` folder. *MAKE SURE TO INCLUDE .TXT AT THE END*
  -  EX: "data/pac3/astromech v1.txt" will load the file `astromech v1.txt` that isnt in any subfolders
- Place the chip down and it will automatically run through the entire PAC file and convert any PAC models to Bug Standard holo data.
- Your holo data will be saved to `sf_filedata/pac2starfall/[pac name].txt`

## Holo Creator V10
- Line 11 has a CreationTable variable. Put any Bug Standard holo data into the variable and when you place the chip it will load the holos
- Line 5 has a load_filedata variable. This will load *serialized* Bug Standard holo data from your `sf_filedata` folder.
  - To use holo data that you made with the Holo Translator do `pac2starfall/[pac name].txt`

# If you have issues
Please either make an issue on here or message me on discord (bprjon)
