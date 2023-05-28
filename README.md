# ASTROTHON 2022 SUBMITTION

The project contains three folders.

CODE ->
This folder contains the jupyter notebook and the Source Data required to output processed images.
No additional files are required to run the jupyter notebook.

Jupyter Notebook has three control variables in the first block, which are explained below.
i->
This is the variable to control which images from the Source Data are processed.
If i = 0, images from Source Data/20160212 are processed and output is generated from them.
If i = 1, images from Source Data/20160213 are processed and output is generated from them.

display_combined_flat_filters and display_combined_bias are booleans to tell whether to show the images of the combined bias and comblined flat filters when running the notebook. These have no effect on the output.

How to use the notebook:
After setting the value of i as described above, run all the cells of the notebook.
Two new folders will be generated, output and combined_i.
The notebook will display the processed images along with their pixel ranges in the end and also save them in the output folder.

output-> contains the output processed images
combined_i -> contains the combined flat filters and combined bias


Calibrated FITS File ->
This folder contains all the processed outputs generated in the same way as described above.


Pixel Ranges of the outputs:

For 20160212:

File Name                          Min Pixel Value          Max Pixel Value
sn16b_b1_2d.fits_B_20160212.fit         5.02                    496.12
sn16b_b2_2d.fits_B_20160212.fit         5.04                    461.3
sn16b_b3_2d.fits_B_20160212.fit         5.27                    400.77
sn16b_b4_2d.fits_B_20160212.fit         5.02                    315.34

sn16b_i1_2d.fits_I_20160212.fit         227.89                  8335.6
sn16b_i2_2d.fits_I_20160212.fit         234.49                  7761.89

sn16b_r1_2d.fits_R_20160212.fit         80.36                   6203.74
sn16b_r2_2d.fits_R_20160212.fit         79.71                   5048.47

sn16b_u1_2d.fits_U_20160212.fit         -4.6                    79.51
sn16b_u2_2d.fits_U_20160212.fit         -5.16                   175.23
sn16b_u3_2d.fits_U_20160212.fit         -5.02                   108.01
sn16b_u4_2d.fits_U_20160212.fit         -5.67                   328.85
sn16b_u5_2d.fits_U_20160212.fit         -6.0                    289.39

sn16b_v1_2d.fits_V_20160212.fit         33.57                   1920.46
sn16b_v2_2d.fits_V_20160212.fit         32.75                   1858.0
sn16b_v3_2d.fits_V_20160212.fit         33.39                   1859.25

Same data in the form of Python list:
[['sn16b_b1_2d.fits_B_20160212.fit', 5.02, 496.12], ['sn16b_b2_2d.fits_B_20160212.fit', 5.04, 461.3], ['sn16b_b3_2d.fits_B_20160212.fit', 5.27, 400.77], ['sn16b_b4_2d.fits_B_20160212.fit', 5.02, 315.34], ['sn16b_i1_2d.fits_I_20160212.fit', 227.89, 8335.6], ['sn16b_i2_2d.fits_I_20160212.fit', 234.49, 7761.89], ['sn16b_r1_2d.fits_R_20160212.fit', 80.36, 6203.74], ['sn16b_r2_2d.fits_R_20160212.fit', 79.71, 5048.47], ['sn16b_u1_2d.fits_U_20160212.fit', -4.6, 79.51], ['sn16b_u2_2d.fits_U_20160212.fit', -5.16, 175.23], ['sn16b_u3_2d.fits_U_20160212.fit', -5.02, 108.01], ['sn16b_u4_2d.fits_U_20160212.fit', -5.67, 328.85], ['sn16b_u5_2d.fits_U_20160212.fit', -6.0, 289.39], ['sn16b_v1_2d.fits_V_20160212.fit', 33.57, 1920.46], ['sn16b_v2_2d.fits_V_20160212.fit', 32.75, 1858.0], ['sn16b_v3_2d.fits_V_20160212.fit', 33.39, 1859.25]]


For 20160213:

File Name                          Min Pixel Value          Max Pixel Value
sn16b_b1_2d.fits_B_20160213.fit         4.28                    697.36
sn16b_b2_2d.fits_B_20160213.fit         4.64                    729.21
sn16b_b3_2d.fits_B_20160213.fit         4.38                    668.15
sn16b_b4_2d.fits_B_20160213.fit         4.99                    702.15
sn16b_i1_2d.fits_I_20160213.fit         234.5                   8617.64
sn16b_i2_2d.fits_I_20160213.fit         232.41                  8727.29
sn16b_r1_2d.fits_R_20160213.fit         81.12                   8980.52
sn16b_r2_2d.fits_R_20160213.fit         81.12                   8866.71
sn16b_u1_2d.fits_U_20160213.fit         -5.98                   262.29
sn16b_u2_2d.fits_U_20160213.fit         -5.02                   153.95
sn16b_u3_2d.fits_U_20160213.fit         -4.43                   240.58
sn16b_u4_2d.fits_U_20160213.fit         -4.75                   484.94
sn16b_u5_2d.fits_U_20160213.fit         -4.7                    160.08
sn16b_v1_2d.fits_V_20160213.fit         33.08                   2876.87
sn16b_v2_2d.fits_V_20160213.fit         33.42                   3635.79
sn16b_v3_2d.fits_V_20160213.fit         33.59                   3500.64

Same data in the form of Python list:
[['sn16b_b1_2d.fits_B_20160213.fit', 4.28, 697.36], ['sn16b_b2_2d.fits_B_20160213.fit', 4.64, 729.21], ['sn16b_b3_2d.fits_B_20160213.fit', 4.38, 668.15], ['sn16b_b4_2d.fits_B_20160213.fit', 4.99, 702.15], ['sn16b_i1_2d.fits_I_20160213.fit', 234.5, 8617.64], ['sn16b_i2_2d.fits_I_20160213.fit', 232.41, 8727.29], ['sn16b_r1_2d.fits_R_20160213.fit', 81.12, 8980.52], ['sn16b_r2_2d.fits_R_20160213.fit', 81.12, 8866.71], ['sn16b_u1_2d.fits_U_20160213.fit', -5.98, 262.29], ['sn16b_u2_2d.fits_U_20160213.fit', -5.02, 153.95], ['sn16b_u3_2d.fits_U_20160213.fit', -4.43, 240.58], ['sn16b_u4_2d.fits_U_20160213.fit', -4.75, 484.94], ['sn16b_u5_2d.fits_U_20160213.fit', -4.7, 160.08], ['sn16b_v1_2d.fits_V_20160213.fit', 33.08, 2876.87], ['sn16b_v2_2d.fits_V_20160213.fit', 33.42, 3635.79], ['sn16b_v3_2d.fits_V_20160213.fit', 33.59, 3500.64]]
