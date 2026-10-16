# MATLAB Image Interpolation Analysis

## Overview

This repository contains MATLAB scripts for image interpolation, pixel reconstruction, and image processing. The project explores different approaches to image enlargement and pixel value estimation, with image quality evaluation using Peak Signal-to-Noise Ratio (PSNR) and Structural Similarity Index Measure (SSIM), where implemented.

## Features

- Image resizing and interpolation
- Pixel reconstruction and estimation
- Image processing and filtering experiments
- Bitwise operations and data embedding experiments
- Image quality evaluation using PSNR and SSIM, where implemented

## Repository Contents

The repository contains the following seven MATLAB scripts:

| File | Description |
|---|---|
| `ENMI.m.txt` | Image interpolation and quality evaluation |
| `INP.m.txt` | Image interpolation and quality evaluation |
| `MNI.m.txt` | MATLAB image processing script |
| `RAS.m.txt` | MATLAB image processing script |
| `c6ano.m.txt` | Interpolation, bitwise operations, and filtering experiments |
| `intbymaxpix.m.txt` | Maximum-pixel-based interpolation experiments |
| `neime.m.txt` | MATLAB image processing script |

*Note: Descriptions are based on the currently available project information. Refer to each source file for its exact implementation.*

## Requirements

- MATLAB
- Input images required by the scripts
- Image Processing Toolbox, if required by the functions used

## How to Run

1. Download or clone this repository.
2. Open MATLAB and set the repository folder as the current working directory.
3. Ensure that the required input images are available in the expected locations.
4. Open the MATLAB script you want to execute.
5. Run the script in MATLAB.

For example, after renaming `ENMI.m.txt` to `ENMI.m`, run:

```matlab
run('ENMI.m')
```

Repeat these steps for the other scripts as needed.

## Image Quality Metrics

### Peak Signal-to-Noise Ratio (PSNR)

PSNR measures the difference between a reconstructed image and a reference image. A higher PSNR generally indicates lower pixel-level reconstruction error.

### Structural Similarity Index Measure (SSIM)

SSIM compares structural information between a reconstructed image and a reference image. A value closer to 1 generally indicates greater structural similarity.

These metrics are applicable to scripts that implement them and require suitable reference and reconstructed images.

## Applications

- Image interpolation and enlargement
- Pixel reconstruction
- Digital image processing
- Image quality assessment
- Experimental image filtering

## Author

**Bushara AR**

GitHub: [@BUSHARAAR](https://github.com/BUSHARAAR)

## License

No license has been specified yet. Please add a license file if you intend to define permissions for using, modifying, or distributing this code.
