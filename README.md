# AddOSC
OSC support in the viewport for Blender, 
for the original work, see: http://www.jpfep.net/pages/addosc/

## Usage
Another addosc branch for blender 2.8 (a very simple one)

i basically took maybites' code, undid his added functionality (and functions),
and drove the dispatcher back to JPfeP's old function,
that didn't have looping the OSC_keys broken out of the dispatcher. (sorry about that maybites)

nothing special, i just needed this quick and dirty hack for myself,
as maybites' fork gave me script errors trying to start a server with OSC_key values in place

it may help someone out there that want to simply control a couple of single values to drive without having to change existing script/blend files around.

## Installation

1) download the zip from git and extract it

2) rename the directory blender28_addosc, and copy it to blender/2.80/scripts/addons

3) start up blender, find and enable the addon (addosc_foul).

in the /example/ directory there are 2 .blend files:

addosc_example_simple.blend - a simple example, with 9 bindings to a cube.

addosc_example_animation_nodes - an example with a bunch of scripts to control animation nodes.

or just use and import keying sets (press k on a object property to add it, like you would add keyframes with i)

tested and working with blender 2.8 beta for windows x64 released as of february 2, 2019.

## Notes

AddOSC relies on the python module python-osc (by Attwad): 
https://pypi.python.org/pypi/python-osc/
https://github.com/attwad/python-osc
