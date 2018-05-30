# Deblending

First section of code plots HSC image using APLpy

Second section creates an HDU list to display image using astropy input and output

Third section plots HDU image using matplotlib function plt.imshow()

Fourth section is a watermark deblending algorithm that uses scipy.ndimage to plot detected peaks next to the original image by comparing pixel brightness to 8 neighbouring pixels

Fifth section is another watermark deblending algorithm that compares to 24 neighbouring pixels in square around central pixel

Sixth section calculates average pixel brightness and its standard deviation

Seventh section makes pixels less than 5 sigma (5 standard deviations) above the average equal to zero. This removes background from the image. Afterwards, it locates the pixels that are bigger than the pixels directly above and below.


