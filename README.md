# gmtkn55-fhiaims
GMTKN55 inputs in FHI-aims format

This repository contains input files for all subsets of the GMTKN55
quantum-chemistry benchmark for use with the FHI-aims program. Each
directory corresponds to a particular subset. For each chemical
species, control.in and geometry.in files are provided.

The control.in files use the PBE0 exchange-correlation functional, but
this can be changed by modifying the xc line. The tight species
defaults are used, except for the AHB21, BH76, BH76RC, G21EA, and IL16
benchmarks, which use the tier2_aug2 basis to the presence of small,
weakly bound anions. For WATER27, tight was used for all cases except
for reactions involving an anion, where tier2_aug2 was used for oxygen
atoms only.

For each subset, the reference data is also provided in .din format,
compatible with aoterodelaroza's refdata repository:
https://github.com/aoterodelaroza/refdata

