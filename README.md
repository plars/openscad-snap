[![Snap Status](https://build.snapcraft.io/badge/plars/openscad-snap.svg)](https://build.snapcraft.io/user/plars/openscad-snap)

# OpenSCAD Snap

This project creates a working snap of OpenSCAD

For more information about OpenSCAD, see http://openscad.org

## Installation

Install using --devmode if you want to be able to save in any path. Otherwise,
you will need to run the following command to give it access to your home::

   sudo snap connect openscad:home ubuntu-core:home


## Current state

Working features:
  - everything?

Known issues:
  - Sometimes shows a console error when rendering (but still works):
    "ERROR: boost::filesystem::create_directory: No such file or directory"
