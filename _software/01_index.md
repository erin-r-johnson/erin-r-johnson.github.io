---
layout: single
title: "Software"
permalink: /software/
excerpt: >-
  Links to software downloads.
search: true
---

[**critic2**](https://aoterodelaroza.github.io/critic2/) -- Our "swiss army" software tool. Use this for:
* converting between file formats and writing input for electronic structure codes starting from molecular or crystal geometries (.cif, .res, .xyz)
* extracting single molecules, dimers, trimers, etc. from a crystal structure
* comparing crystal structures with each other, and with experimental PXRD patterns
* operations on cube files and plotting results on a line or plane
* QTAIM analysis, including Bader charges and delocalization indices
* much more

Also, see here [VC-PWDF_Manual-v2.pdf](/downloads/VC-PWDF_Manual-v2.pdf) for a manual
describing the use of our variable-cell powder difference (VC-PWDF) method
within critic2, along with a script [vc-xpwdf-plot.sh](/downloads/vc-xpwdf-plot.sh) for
plotting overlays of simulated and experimental PXRD patterns.


[**postg**](https://github.com/aoterodelaroza/postg) -- Allows use of the XDM dispersion model with the Gaussian quantum-chemistry package.


[**nciplot**](https://github.com/aoterodelaroza/nciplot) -- Allows generation of NCI and ELF cube files from a wavefunction (.wfn, .wfx) file.


[**escher**](https://github.com/aoterodelaroza/escher) -- A set of octave routines for generating pretty images of molecular and crystal structures.


[**bicrystal**](https://tilaskabengele.github.io/BiCrystal/) -- Use this to build incommensurate structures of layered materials.


**Colour-blind resources**: colour-blind [simulator](https://pilestone.com/pages/color-blindness-simulator)
and colour-blind friendly [palettes](https://github.com/KyleBryenton/Dalhousie-Beamer-Theme/blob/main/ColourBlindSwatches.txt)


Reference data for selected benchmark sets can be found here: [**refdata**](https://aoterodelaroza.github.io/refdata/)


GMTKN55 inputs for use with FHI-aims can be found here: [**gmtkn55-fhiaims**](https://github.com/erin-r-johnson/gmtkn55-fhiaims)


XDM damping parameters for use with selected electronic structure packages can be found in the **postg** distribution. A subset of these is shown here:

**Quantum ESPRESSO**

| Functional | Basis | a<sub>1</sub> | a<sub>2</sub> (Å) |
|------------|-------|---------------|-------------------|
| B86bPBE    |  PAW  |    0.6512     |      1.4633       |
| PBE        |  PAW  |    0.3275     |      2.7673       |


**FHI-aims**

| Functional | Basis | a<sub>1</sub> | a<sub>2</sub> (Å) |
|------------|-------|---------------|-------------------|
| PBE        | lightdense | 0.3308 | 2.9589 |
| HSE06      | lightdense | 0.1652 | 3.5942 |
| PBE0       | lightdense | 0.1852 | 3.5044 |
| B86bPBE    | lightdense | 0.6913 | 1.5747 |
| B86bPBE-25 | lightdense | 0.4639 | 2.4079 |
| B86bPBE-50 | lightdense | 0.0565 | 3.9271 |
|------------|-------|---------------|-------------------|
| PBE        | intermediate | 0.2880 | 3.0439 |
| HSE06      | intermediate | 0.0362 | 3.9392 |
| PBE0       | intermediate | 0.0288 | 3.9293 |
| B86bPBE    | intermediate | 0.5575 | 1.9272 |
| B86bPBE-25 | intermediate | 0.1624 | 3.2667 |
| B86bPBE-50 | intermediate | 0.0000 | 4.0214 |
|------------|-------|---------------|-------------------|
| PBE        | tight | 0.5120 | 2.2592 |
| HSE06      | tight | 0.4521 | 2.4806 |
| PBE0       | tight | 0.4710 | 2.3857 |
| B86bPBE    | tight | 0.8983 | 0.7866 |
| B86bPBE-25 | tight | 0.7268 | 1.3825 |
| B86bPBE-50 | tight | 0.5898 | 1.9070 |


**Gaussian**

| Functional |     Basis      | a<sub>1</sub> | a<sub>2</sub> (Å) |
|------------|----------------|---------------|-------------------|
| PBE0       |  aug-cc-pVTZ   |     0.4186    |      2.6791       |
| B3LYP      |  aug-cc-pVTZ   |     0.6356    |      1.5119       |
| LC-wPBE    |  aug-cc-pVTZ   |     1.0149    |      0.6755       |
| B3LYP      | 6-311+G(2d,2p) |     0.4376    |      2.1607       |
| LC-wPBE    | 6-311+G(2d,2p) |     0.5313    |      2.2665       |
| B3LYP      |    Mixed DZ    |     0.0000    |      3.7737       |
| LC-wPBE    |    Mixed DZ    |     0.6889    |      1.9452       |

Mixed DZ indicates 6-31G* for H, B, C, and Si and 6-31+G* for all other elements.


