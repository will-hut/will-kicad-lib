# William's KiCAD Library #

* This repo contains the KiCAD 6 Libraries (footprints, symbols, 3d models) used in my personal designs.
* This must be downloaded locally and added to your KiCAD path, and global footprint/symbol libraries before use.

### How do I get set up? ###

* In the main KiCAD window, click "Preferences > Configure paths", and then click the plus button to add a new path.
* For the name, call it "WILLIAM", and for the path, set it to where you cloned this repo, for example, "C:\path\to\will-kicad-lib. Then click OK.
* Now, click "Preferences>Manage Symbol Libraries" and make sure you're in the "Global Libraries" tab.
* Click the plus button, put "William" for the nickname, and put "${WILLIAM}/symbols/william.kicad_sym" for the library path. Then click OK.
* Now, click "Preferences>Manage Footprint Libraries" and make sure you're in the "Global Libraries" tab.
* Click the plus button, put "William" for the nickname, and put "${WILLIAM}/footprints/william.pretty" for the library path. Then click OK.
* At this point, my library is set up, and you can now freely use the components in KiCAD.

### Moving the Library ###

* By adding a path in "Configure paths", you have made the location of the the library a variable. So, to move the library to a different location, update the path to the new location.