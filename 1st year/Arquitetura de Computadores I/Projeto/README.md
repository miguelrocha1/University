# About the project
This project goal was to develop a program that was able to denoise an 400x599 corrupted image provided by the teacher.
This project was developed in Assembly RISC-V programming language.

# Functionalities
This program denoises any grayscale noise corrupted image with the dimensions 400x599, using two denoising techniques (median and mean).
### Mean filter:
This filter calculates the mean of all eight surrounding pixels, as well as the pixel that we are visiting, then replaces it in the new image.
### Median filter:
This filter calculates the median of all eight surrounding pixels, as well as the pixel that we are visiting, then replaces it in the new image.
This result is usually better than the mean filter, since a single very unrepresentative pixel in a neighborhood won't affect the median value significantly.
The border of the image is set to black because of some limitations and to make the project more simple.
# How to run 
- Open it in an RISC-V simulator, just like RARS. (make sure to enable the "Initialize Program Counter to 'global' main if defined" option if you are using RARS simulator.
- Convert the image to .gray then change the name of the file inside the .data section.
- Convert the .gray optput to the desired file extention.
# Grade
### 20.0/20.0
# Authors
- Miguel Rocha
- [Miguel Pombeiro](https://github.com/MiguelPombeiro)
