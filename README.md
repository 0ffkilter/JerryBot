# JerryBot

A Python Facebook chat bot written in Python.  Uses a forked [fbchat](https://pypi.python.org/pypi/fbchat/) module with applied patches to get group chat working.

Written for Python2.7 in Python3

##Installation

1. Clone Repo
2. Run
`git submodule init`
to initialize the submodule repo
3. Run
`git submodule update`
to update the repo and pull the data.
4. Update credentials.py with relevant account information
5. Rename auth.py.example to auth.py and fill in the relevant information

##Usage

`python JerryBot.py`

##Modules

Currently provided modules:
 * Flip (Flip a coin)
 * Roll (Roll an n sided die, default six)
 * Menu $day $dining_hall $meal (order of params shouldn't matter)
 * eatadick 
 * weather
 * jackets
 * help
 * thanks
 
Planned Modules:
 * Reminders
 * Linkme/define
 * Random quote generation
 * Random joke generation
 * Combinatorial calculations
 
Create a module:

1. Create a module in modules/
2. Have one endpoint function that takes in a list of arguments (doesn't have to do anything with them)
3. Add function to modules{} in modules/modules.py
