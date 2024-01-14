Circle Mask Generation

This Python script, circle_mask_generation.py, is designed to generate a circular mask on an image. The code utilizes the OpenCV library for image processing, NumPy for numerical operations, and the matplotlib library for visualization in a Colab environment.

Features

Reads an image from a specified file path.
Displays the original image using cv2_imshow in Colab.
Generates a blank image (im2) as a NumPy array.
Displays the blank image.
Creates a circular mask on the blank image.
Displays the resulting image with the circular mask.
Saves the final image with the circular mask to a specified file path.
Usage

Replace the file path in im1=cv2.imread('/content/sample_data/test.jpg') with the path to your desired image.
Run the script to visualize the original image and the circular mask applied.
Adjust parameters such as length, width, and radius to customize the circular mask.
Note

Certain visualization functions, such as cv2.imshow and plt.imshow, might not work directly in a Colab environment, so the code uses cv2_imshow for displaying images.
The final image with the circular mask is saved to the specified file path (/content/sample_data/test2.jpg in the provided example).
