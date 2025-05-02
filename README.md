Graphics experiments with various dithering algorithms.

[blue_noise_optimize_fft.ipynb](blue_noise_optimize_fft.ipynb) is a Google Colab based on
https://bartwronski.com/2020/04/26/optimizing-blue-noise-dithering-backpropagation-through-fourier-transform-and-sorting/
modified to support uploading file from local machine, since urlretrieve from imgur results in HTTP 429 error.

## Input
![Example Input: Linear Black to White Horizontal Gradient](BlackGreyWhiteHorizontalGradient-350x350.png?raw=true "Example Input: Linear Black to White Horizontal Gradient")

## Blue Noise Dithered Output: 3 Colors
![Example 3-Color Dithered Output (Black, Gray, White)](BlackGrayWhiteDitheredGradient-output-350x350.png?raw=true "Example 3-Color Dithered Output (Black, Gray, White)")

## Blue Noise Dithered Output: 2 Colors
![Example 2-Color Dithered Output (Black, White)](BlackWhiteDitheredGradient-output-350x350.png?raw=true "Example 2-Color Dithered Output (Black, White)")


# Credits, License
Most of the code in this repository was written by [Bart Wronski](https://bartwronski.com/), not me. Please check with him for licensing if you wish to use this in a commerical project.
