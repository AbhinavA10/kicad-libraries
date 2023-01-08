# kicad-libraries
Collection of KiCad Libraries

## Installation Instructions
- Install KiCad 6.0
- clone this repo to your `Documents` folder.
- Open KiCad -> Preferences -> Manage Symbol Libraries
- In the Global Libraries page, add `.lib` files to KiCAD
    - `./digikey-kicad-library/digikey-symbols/*`
    - `./sparkfun-kicad-library/Libraries/*`
    - `myelin-kicad.lib`
    - `AA_Custom_Components.kicad_sym`
        - (For KiCad 5.0, use `AA_Custom_Components.lib`)
- Open KiCad -> Preferences -> Manage Footprint Libraries
- In the Global Libraries page, add `.lib` files to KiCAD
    - `./digikey-kicad-library/digikey-footprints.pretty`
    - `./sparkfun-kicad-library/Footprints/*`
    - `myelin-kicad.lib`
    - `AA_Custom_Components.pretty`

## Sources
- `myelin-kicad.lib` is from [here](https://github.com/myelin/myelin-kicad-libraries)
- Digikey and Sparkfun KiCad library were added using [git subtree](https://gist.github.com/SKempin/b7857a6ff6bddb05717cc17a44091202)

## Links
- [Shawn Hymel's KiCAD tutorial](https://www.youtube.com/playlist?list=PLEBQazB0HUyR24ckSZ5u05TZHV9khgA1O)
- [Creating a new symbol library and symbol in KiCad 5](https://forum.kicad.info/t/creating-a-new-symbol-library-and-a-new-symbol-in-kicad-5/13341)
- [Making a symbol - written Tutorial](https://forum.kicad.info/t/tutorial-how-to-make-a-symbol-kicad-v5-1-x/13336/3)
- [Importing a lib file for symbols](https://forum.kicad.info/t/how-to-get-a-downloaded-symbol-footprint-or-full-library-into-kicad-version-5/19485)
- [Designators for Chips](https://en.wikipedia.org/wiki/Reference_designator#Designators)