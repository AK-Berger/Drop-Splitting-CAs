# Drop-Splitting-CAs
The toolkit is particularly useful for studying drop impact on edged structures, providing insights into how surface wettability and impact velocity affect the behavior of the drops. This script can be applied to similar experiments for accurate and efficient measurement of contact angles and drop dynamics.


---
# Publication Information:

Title: Drop Splitting from Central Impact on Edged Structures: Effect of Sharpness and Wetting Properties

Authors: Xiaoteng Zhou, Diego Diaz, Zhongyuan Ni, Sajjad Shumaly, Jie Liu, Michael Kappl, Hans-Jürgen Butt

Journal: --

Publication Date: --

DOI: --


---
# Data Information:

### The toolkit code

- "Drop Splitting CAs.ipynb"

    It calculates advancing and receding contact angles using tan fitting and enhances resolution through custom algorithms to refine edge detection. Velocities are calculated by measuring the spatial displacement of contact points over time. The image processing pipeline includes morphological transformations and rotation correction to ensure precise alignment, with automated handling of image sets and saving of processed images with visualized results.

### An example

- example.avi
    This video demonstrates an example of measurements we analyzed using the "Drop Splitting CAs.ipynb" notebook to illustrate its functionality.
      find it here: https://drive.google.com/file/d/1UcsFBUvKf-milUfHYe2pJQwPUwdIK6Hb/view?usp=sharing


### The Frames folder

- Frames

    First, we convert the video into .tiff frames using the toolkit.

    Next, we remove all the extra frames that are not relevant for analysis. The first frame should capture the moment when the drop makes contact with the surface, and the last frame should be when the drop is still connected to the surface. This ensures we're focusing on the drop's advancing phase.

    Create a folder named "slope" and copy the first and last frames into this folder.

    Open these frames in Microsoft Paint and mark the advancing points on both the left and right sides by placing a red pixel using the pencil tool. Save the frames as 1.bmp and 2.bmp respectively.
    
    Finally, run the rest of the code to complete the analysis.
  

  ---
# Dependencies 

matplotlib 3.8.0; https://pypi.org/project/matplotlib/

cv2 4.10.0; https://pypi.org/project/opencv-python/

numpy 1.26.4; https://pypi.org/project/numpy/

scipy 1.11.4; https://pypi.org/project/scipy/

pandas 2.1.4; https://pypi.org/project/pandas/

natsort 8.4.0; https://pypi.org/project/natsort/

---
# Support

You can communicate with us using the following e-mails:

- shumalys@mpip-mainz.mpg.de
- zhoux@mpip-mainz.mpg.de
---
