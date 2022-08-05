# AVAS.py
A python module for the AVAS minecraft server api

### Usage
To use the api just add the avas.py file to your project and import it with "from avas import *" or "from avas import avas".
Theres a very basic example for how to use the module in the main.py file

### Variables
The variables are updated whenever ping() is called
- online : returns true/false depending on if the server is up
- playerCount : returns the number of currently logged in players

### Functions
- ping() : returns server online, refreshes all variables
- get_online() : returns server online, refreshes "online" variable
- get_playercount() : returns playercount, refreshes "playerCount" variable
- get_ip() : gets the ip of the api client


I am currently working on getting this package ready for PIP but my python experience is pretty limmited so this may take some time. If you wanna help out with doing packaging then just let me know