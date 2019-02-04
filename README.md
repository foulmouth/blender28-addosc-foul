# AddOSC
OSC support in the viewport for Blender, see: http://www.jpfep.net/pages/addosc/

## Usage
Another addosc branch for blender 2.8

basically took maybites' code i happened to stumble upon,
undid the broken out-functions and drove the dispatcher back to JPfeP's old function

nothing special, i just needed it for myself
but it may help someone out there that want to simply control a couple of single values to drive without having to change existing script/blend files around.

look for the scripts in the blend file in /example/ (or just use keying sets)
tested and working with blender 2.8 beta for windows x64 released as of february 2, 2019.


AddOSC relies on the python module python-osc (by Attwad): 
https://pypi.python.org/pypi/python-osc/
https://github.com/attwad/python-osc