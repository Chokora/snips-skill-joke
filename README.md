# Snips Joke Skill

This is a Python3 skill allowing to retrieve jokes in French from the 
Chuck Norris Joke API: https://chucknorrisfacts.fr/facts

I added a little modification to replace Chuck Norris by GladOS, best 
suited for a robotic assistant. It may add a little to the joke.

## Setup

This app requires some python dependencies to work properly, these are
listed in the `requirements.txt`. You can use the `setup.sh` script to
create a python virtualenv that will be recognized by the skill server
and install them in it.

## Executables

This dir contains a number of python executables named `action-*.py`.
One such file is generated per intent supported. These are standalone
executables and will perform a connection to MQTT and register on the
given intent using the `hermes-python` helper lib.
