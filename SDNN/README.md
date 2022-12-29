# Stokes Inversion for GST/NIRIS Using Stacked Deep Neural Networks

Haodi Jiang 

New Jersey Institute of Technology

----
References:

Inferring Line-of-sight Velocities and Doppler Widths from Stokes Profiles of GST/NIRIS Using Stacked Deep Neural Networks. Haodi Jiang et al 2022 ApJ 939 66

https://iopscience.iop.org/article/10.3847/1538-4357/ac927e

----

Requirement: 

tensorflow=1.11.0
keras=2.2.4
astropy

Usage:

The source code package contains the following folders/directories.

1. The “inputs”folder contains NIRIS Stokes profiles samples from BBSO/GST.
2. The “Outputs”folder contains inverted results: bx, by, bz, Doppler width and LOS velocity.

Run 

python SDNN.py

Notes:
# The code will also save b_total, inclination and azimuth if save_mag_field_o = True;
# otherwise only save bx, by, bz, Doppler width and LOS velocity.