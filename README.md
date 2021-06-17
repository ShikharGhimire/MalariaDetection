# MalariaDetection
Detecting different types of blood cells including those infected from Malaria.

### Original file: Json

Malaria sample images:

<div align="left">
    <img src="https://github.com/ShikharGhimire/MalariaDetection/blob/main/Malaria%20screenshot.png" width="600px"</img> 
</div>

### Brute Force Technique

Rectangle.patches was used. How does rectangle.patches work?

<div align="left">
    <img src="https://github.com/ShikharGhimire/MalariaDetection/blob/main/rectangle.JPG" width="600px"</img> 
</div>

### BruteForce Result

<div align="left">
    <img src="https://github.com/ShikharGhimire/MalariaDetection/blob/main/malariabb.JPG" width="600px"</img> 
</div>

# Paused it because of RAM ISSUES 

- Had issues converting 80k pictures into numpy arrays

-I think I came up with solution. Rather than converting the image into numpy arrays from dataframe, let's convert each file into numpy arrays and then later see how many times the image appears in the original dataframe and duplicate the numpy arrays depending on how many times the image file occured in the original dataframe
