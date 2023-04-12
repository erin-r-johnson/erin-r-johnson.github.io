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


Reference data for selected benchmark sets can be found here: [**refdata**](https://aoterodelaroza.github.io/refdata/)


XDM damping parameters for use with selected electronic structure packages can be found in the **postg** distribution. A subset of these is shown here:

**Quantum ESPRESSO**

| Functional | Basis | a<sub>1</sub> | a<sub>2</sub> (Å) |
|------------|-------|---------------|-------------------|
| B86bPBE    |  PAW  |    0.6512     |      1.4633       |
| PBE        |  PAW  |    0.3275     |      2.7673       |


**FHI-aims**

| Functional | Basis | a<sub>1</sub> | a<sub>2</sub> (Å) |
|------------|-------|---------------|-------------------|
| PBE        | light |     0.5312    |      2.3270       |
| B86bPBE    | light |     0.8219    |      1.2069       |
| PBE0       | light |     0.3302    |      3.0042       |
| B86bPBE-25 | light |     0.5235    |      2.1995       |
| B86bPBE-50 | light |     0.0831    |      3.7362       | 
| PBE        | tight |     0.6438    |      1.8533       |
| B86bPBE    | tight |     0.8976    |      0.8518       |
| PBE0       | tight |     0.5053    |      2.2527       |
| B86bPBE-25 | tight |     0.6546    |      1.6097       |
| B86bPBE-50 | tight |     0.4887    |      2.1855       |


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


