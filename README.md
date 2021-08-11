# Mixor Image
![mi-photo]

**Modular Maculata 'Mixor Image' Eurorack Module.**

6 input, 2 output minimal panning mixer in 12hp.
Designed for Intellijel 1U format.
100% through-hole parts for maximum DIY-Friendliness :)

Mixor Image is built upon the bones of Nearness designed by [Jesper Särnesjö][nearness-git].
Nearness is a product of the *[llllllll][nearness-lines]* community. 

# Changes

* This module has been re-designed to suit the Intellijel 1U format behind a 12hp panel, and be made with entirely through-hole components
* Resistor values have been changed throughout to give a different stereo image *(An automated method was used for this to select nearest common resistor values based on angle of placement in the stereo field for each input)*
* An additional centre input with a high pass filter has been added so as not to muddy the middle of the stereo field
* Stereo in & out *link* connectors have been added allowing for chaining of multiple modules or linking to other manufacturers' stereo modules without patch cables

# PCB & Panel

KiCad files are provided for the 2 PCB's and a plain panel without artwork.

Gerber files can be found in the Gerbers directory.

The BOM can be found in the Build Guide document.

# License

In accordance with the wishes of the designer of the work that inspired this, and in the spirit of community development, this work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[nearness-lines]: https://llllllll.co/t/prototyping-nearness-a-minimal-panning-mixer-module/8330
[nearness-git]: https://github.com/sarnesjo/nearness
[mi-photo]: https://github.com/modular-maculata/mixor-image/blob/main/mixor-image.jpeg
[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
