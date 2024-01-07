## Denoise-module
This module is used to denoise audio file and evaluate it. The module include 2 methods by using Spectral subtraction and FRCRN 
## Problem description

## How to use the file
Step 1: To use the denoise function please first install the requirement packages in requirements.txt\
Step 2: Go to this file Denoise_module.ipynb\
Step 3: Import the necessary package\
Step 4: Denoise module\
To use Spectral Subtraction method you can go to section Spectral Subtraction then define the path needed to denoised and run the following code. This method first compute the estimated noise and apply denoised based on the noise level. The drawbacks of this method is it not good when we have silence \
To use FRCRN we need to resample the signal as the architecture require the sampling rate fs is 16khz
Step 5: 
