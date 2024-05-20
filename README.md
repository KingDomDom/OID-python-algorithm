# Project Name

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Description

This project aims to [write a python version OID algorithm].#Annotations are disordered .
The main problem now is in threshold_px_py_v1.
If you want to debug, please add a breakpoint in line 18 there.

Here are specific introduction:
<span style="color:orange">blind_deconv,coarse_deblur,fine_deblur,wrap_boundary_liu ,psf_x_otf </span>are writen mannually and already checked(may still have bugs).
<span style="color:blue">opt_fft_size, estimate_matrix and threshold </span>have the most serious problem.
<span style="color:red">fftconv,deconv_L2, bwconncomp </span>may be replaced by other functions .
<span style="color:green">other file are just writen from MATLAB,some are just writen by Copilot.</span>
## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Installation

[download, zip all files, and run locally]

## Usage

[run main.py and the program will process example.png automatically]

## Contributing

[Please help me debug,there are many bugs hidden in this project.I write it according to the MATLAB code on https://drive.google.com/file/d/19PCEXVs6imWqqae37r5By-OCUlrNGHnd/view#/ ]

## License

This project is licensed under the [MIT License](LICENSE).
