# Code100-1-VarAndManageData

#Working with Variables in Python to Manage Data

#The following example creates a name generator which prompts the user to enter variables(city name and pet name). Both user input names are concatenated(join data) to give the suggested band name. 



#1. Create a greeting for your program.
print("Welcome to the Band Name Generator\n")

#2. Ask the user for the city that they grew up in.
cityname = input("\nWhat's the name of the city your grew up in:\n")

#3. Ask the user for the name of a pet.
petname = input("\nWhat's your pet name:\n")

#4. Combine the name of their city and pet and show them their band name.
print("\nYour bandname is:\n" + petname + " " + cityname)
