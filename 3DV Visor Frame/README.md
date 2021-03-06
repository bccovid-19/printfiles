# 3DV Visor Frames

Please see http://faceshield.nu for information.
- [Print Settings Guide](https://3dverkstan.se/protective-visor/protective-visor-print-guide/)
- [Packaging & Handling](http://translate.google.com/translate?js=n&sl=sv&tl=en&u=https://3dverkstan.se/protective-visor/protective-visor-packing-handling/), specific to Sweden, but useful nonetheless.

# Common/Recommended Print Settings (See Print Settings Guide above for further details)
- Material: PETG, PLA acceptable if no other choice
- Nozzle: 0.4 mm (most common) to 1.0 mm
- Extrusion Width (0.4 mm to 0.6 mm nozzle, preferred): 0.72 mm
- Extrusion Width (0.4 mm to 0.6 mm nozzle, alternate): 0.70 mm, or see the guide.
- Extrusion Width (0.8 mm to 1.0 mm nozzle): 1.0 mm
- Layer Height: ~0.3 mm
- Infill: 0%, or increase to 100% if nubs have holes in them
- Walls: 3-4, goal is to have solid fill, i.e. the arms should be only filled with perimeters
- Support: No (N/A)
- Note that these are relatively aggressive print settings, may not work with all printers and will likely require finetuning. Your hotend's maximum volumetric flow (a factor of your extrusion width, layer height, and print speed) will likely determine how fast you can print each visor frame. For most printers, between 9-25 minutes/frame is very reasonable. You may need to run your extruder temperature hotter than normal to maintain good flow.
- For anyone new to printing PETG, main points to remember compared to PLA, it needs a hotter extruder temperature (220-260C), hotter build plate (70-100C), and is prone to stringing. Consider enabling "Combing" (print head avoids crossing perimeters) or equivalent, and especially with bowden setups, pay attention to retraction distance, retraction speed, and travel speed.


# File Selection
The [Extended Visor](./bcc3d_extended_v5.stl) version is preferred due to the increased forehead clearance and comfort. If your build plate cannot fit this model, then the standard [0.6mm Version](./Visor_Frame_NORTH_AMERICA_letter_6-hole_v5-0.6mm_chamferred.stl) and  [1mm Version](./Visor_Frame_NORTH_AMERICA_letter_6-hole_v5-1mm_chamferred.stl) are acceptable.

# Standard Visor
The [0.6mm Version](./Visor_Frame_NORTH_AMERICA_letter_6-hole_v5-0.6mm_chamferred.stl) should be tried first, as it has a reduced print time. If this version adheres too much to your print bed and is unable to be removed without damage please switch to the [1mm Version](./Visor_Frame_NORTH_AMERICA_letter_6-hole_v5-1mm_chamferred.stl).

# Extended Visor
The [Extended Visor](./bcc3d_extended_v5.stl) version can be used for practitioners needing an extended space between the visor and the face to accommodate glasses or goggles. It also increases the width of of the forehead contact surface and permits the use of padding (weatherstripping foam) if desired. It has been confirmed to work with the same dimensions and hole pattern as the standard version.

# Files for Prusa MK3 and MK3s

Within the `For Prusa MK3 and MK3s` folder you will find two .3mf files. These are print profiles of the [Extended Visor](./bcc3d_extended_v5.stl), with relatively aggressive settings for quick prints. One has had the bands flipped to spread the wear on the build platform a bit better.

# Credits

- 3D-Printed Protective Visor by 3DVerkstan/Erik Cederberg https://www.youmagine.com/designs/protective-visor-by-3dverkstan/
- 3D Printed Face Shield by by Retrolabs (remix of 3DVerkstan's model) https://retrolabs.com/3d-prints/3d-printed-face-shield-with-10-mil-pvc

# Changelog

### Version 5 - Extended:

- V5 provided by 3DVerskstan remixed with Retrolab's "Closed Top Padded" version

### Version 5:

- V5 provided by 3DVerskstan (improved joint between arms and forehead section, added separate file for 1 mm thick section)
- Chamfer added on the upper edges

### Version 3.3:

- Remixed to add chamfer on the upper edges

### Version 3:

- Original North America 6-hole version provided by 3DVerkstan

# License
This remix is created under [Creative Commons Attribution Share Alike](https://creativecommons.org/licenses/by-sa/3.0/deed.en_US)
- Commercial use is allowed, you must attribute the creator, you may remix this work and the remixed work should be made available under this license.
