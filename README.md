## My Approach (Solution)
# The Steps involved in solving the Objectives are as follows:

1.Importing Required Libraries
2.Defining Required Function

Defining custom "show" function for Image Visualization
2. Image Pre-Processing
  * GrayScale Conversion
  * Image Thresholding
  * Morphological Transformations (Noise Removal)
3. Counting rice grains using the Contours method
  * Working over Clear image to get insight into grain touching problem
3.Applying Watershed Algorithm (Solving grains touching problem)
  * Applying Watershed Algorithm for Solving Touching rice grains problem
4.Counting total Rice grains and Broken Rice grains using the contour area
  * For total rice grains counting: the Watershed method
  * For broken rice grains counting: A filter of an average area of broken rice grain.
  
## Explanation
The main Idea behind solving the objectives(Counting rice grains) is to make the provided image in the best possible format. If there would be clarity in the image, and rice grains are well separated from the background image then there would be ease in counting them.

Then, Solving the Corner cases and hence building the soluction.
