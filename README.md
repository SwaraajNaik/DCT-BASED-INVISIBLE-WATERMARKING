# DCT-BASED-INVISIBLE-WATERMARKING
DCT BASED INVISIBLE WATER MARKING WITH ATTACKS
DCT (discrete cosine transform) domain watermarking is robust against attacks such as 
noising, compression, sharpening, and filtering. ... DCT allows an image to be decomposed 
into different frequency bands, making it easy to embed watermarking information into the 
frequency bands of the image.


# Pre-requisite
-   Git-Hub account
-   Python 3
-   pip
# Import
- import cv2
- from scipy.fftpack import *
- import numpy as np
- import math
- from skimage.util import random_noise
- from google.colab.patches import cv2_imshow

# Inputs
**Embedding the watermark**
  -   **Image** - This takes the name of the image where the watermark to be embedded.
  -   **watermark** - This is the image to be embedded in the background image.
  -   **DCT** -applying dct on the image

**Extracting the logo**
- **Decode algo** - To perform IDCT to extract the logo.

**Attack**
- **geomatric attack**
- **salt and pepper attack**
- **gaussian noise**

# How-to-run
  - Step-1 Open the Audio-steganography.ipynb file in colab or jupyter notebook.
      Link to the .ipynb file - 
     https://github.com/SwaraajNaik/DCT-BASED-INVISIBLE-WATERMARKING
      
      - To open the file in colab, copy the above link and in colab page, paste it in the git-hub url.
      
      -  ![Screenshot 2022-02-03 233739](https://user-images.githubusercontent.com/40821800/152402697-73f4a30f-d5ea-4af4-969c-fd3486059798.png)

      
  - Step-2 Once open, run all the cells from the beginning.
  - Step-3 Finally run the **result** segment to see the results 


![2](https://user-images.githubusercontent.com/40821800/152402589-1a1417e5-71a4-47c6-b17f-fb1b99997dfb.png)
![3](https://user-images.githubusercontent.com/40821800/152402601-937a5106-4579-4a1e-8d45-c8bd8be2c5f5.png)
![iitbbs_logo](https://user-images.githubusercontent.com/40821800/152402628-30195bfc-9ad6-4c3f-9d7a-9685e7ad57bd.jpeg)

![afterpsnr11](https://user-images.githubusercontent.com/40821800/152402660-c855f843-6336-4a4e-aa8e-ed992bde06f3.png)

