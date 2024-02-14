# Handheld-MRI-Parts
Parts Library for Handheld MRI Project

## Library Setup
Clone this repository. Open KiCAD, go to Preferences -> Configure Paths..., and add a new Environment Variable called "HANDHELD_MRI" that points to the Handheld-MRI-Parts folder. Then add the symbol library by selecting Preferences -> Manage Symbol Libraries... and selecting the handheld_mri.kicad_sym file in this repository. Check that the library path shows up as "${HANDHELD_MRI}.kicad_sym". Add the footprint library by selecting Preferences -> Manage Footprint Libraries... and selecting the handheld_mri_footprints.pretty folder in this repository. Check that the library path uses the ${HANDHELD_MRI} variable.

## Conventions
When creating new symbols, include the footprint, datasheet, description, and keywords. 

Thanks to Hans Gaensbauer for showing me how to set this up. This README is taken from his [analagous project](https://github.mit.edu/hgaens/BioMEMS-Parts)
