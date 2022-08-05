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



The AVAS api was released like an hour ago so I will probably be making a lot of changes as the API develops
