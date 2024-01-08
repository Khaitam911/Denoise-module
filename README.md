## Problem description

## Denoise-module
This module is used to denoise audio file and evaluate it. The module include 2 methods by using Spectral subtraction and FRCRN 

## How to use the file
Step 1: To use the denoise function please first install the requirement packages in requirements.txt\
Step 2: Go to this file Denoise_module.ipynb and open it (recommend in jupyter lab)\
Step 3: Import the necessary package\
Step 4: Denoise module
- To use Spectral Subtraction method you can go to section Spectral Subtraction then define the path needed to denoised and run the following code. This method first compute the estimated noise and apply denoised based on the noise level. The drawbacks of this method is it not good when we have silence 
- To use FRCRN we need to resample the signal as the architecture require the sampling rate fs is 16khz
  
Step 5: Evaluation Description
- PESQ (Perceptual Evaluation Of Speech Quality) is an objective and full-reference speech quality evaluation method. The score ranges from -0.5 to 4.5. The higher the score, the better the speech quality.
- STOI (Short-Time Objective Intelligibility) reflects the objective evaluation of speech intelligibility by the human auditory perception system. The STOI value is between 0 and 1. The larger the value, the higher the speech intelligibility , the clearer it is.
