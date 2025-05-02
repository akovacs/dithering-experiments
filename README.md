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

# Further Information
In case you are interested in dithering algorithms, other useful resources are:

## Visual Comparisons
https://munksgaard.github.io/bluenoise/

Graphical comparison of Blue Noise dithering (the current state-of-the-art as of 2025)


https://tannerhelland.com/2012/12/28/dithering-eleven-algorithms-source-code.html

A graphical comparison of classical (1990 and earlier) dithering algorithms with source code. My favorites are:
- Stucki Dithering
- Sierra Dithering

https://surma.dev/things/ditherpunk/

Explanations and samples of other dithering algorithms including:

- Atkinson
- Riemersma

https://www.crisluengo.net/archives/355/

Gallery of other techniques such as halftoning.


https://nibnalin.me/dust-nib/analysing-image-dithering.html

Visual comparisons of dithering techniques applied to color images with implementation


## Other links of interest
https://blog.maximeheckel.com/posts/the-art-of-dithering-and-retro-shading-web/
Very comprehensive gallery of retro shading effects with demos and Javascript code

Detailed explanation of dithering techiques in a text file
https://gist.github.com/robertlugg/f0b618587c2981b744716999573c5b65
linked from
https://stackoverflow.com/questions/9150338/besides-floyd-steinberg-dithering-any-other-ways-to-dither-the-images


## Additional technical information on Gaussian Blue Noise

https://psychopath.io/post/2022_07_24_owen_scrambling_based_dithered_blue_noise_sampling

Implementation that I copied: https://colab.research.google.com/github/bartwronski/BlogPostsExtraMaterial/blob/master/blue_noise_optimize_fft.ipynb

https://bartwronski.com/2022/08/31/progressive-image-stippling-and-greedy-blue-noise-importance-sampling/

https://bartwronski.com/2020/04/26/optimizing-blue-noise-dithering-backpropagation-through-fourier-transform-and-sorting/

https://munksgaard.github.io/bluenoise/
