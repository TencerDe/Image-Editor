# Image-Editor
This is a simple and intuitive image editor application built using Python and PyQt5. The application allows users to perform basic image editing operations such as rotation, mirroring, sharpening, grayscale conversion, saturation adjustment, contrast enhancement, and blurring.The edited images are saved in a designated folder within the working directory.

Features
Load Images: Choose a folder containing your images and select the image you want to edit.
Rotate Left/Right: Rotate the image 90 degrees to the left or right.
Mirror: Flip the image horizontally.
Sharpness: Enhance the sharpness of the image.
Grayscale: Convert the image to grayscale.
Saturation: Adjust the saturation of the image.
Contrast: Enhance the contrast of the image.
Blur: Apply a blur effect to the image.
Save Edits: Save the edited image in a separate folder named Edits within the selected working directory.
Installation
To use this application, you'll need to have Python installed along with the necessary dependencies.

Clone this repository:

bash
Copy code
git clone https://github.com/TencerDe/Image-Editor.git
Install the required dependencies:

bash
Copy code
pip install PyQt5 Pillow
Usage
Run the application:

bash
Copy code
python main.py
Click on "Choose folder" to select the directory containing the images you want to edit.

Select an image from the list on the left-hand side to load it into the editor.

Use the provided buttons to apply different effects to your image.

The edited image will be saved automatically in the Edits folder within your selected working directory.

Code Overview
Editor Class
load_image(self, filename): Loads the selected image from the working directory.
save_image(self): Saves the edited image to the Edits folder.
show_image(self, path): Displays the current image in the UI.
gray(self): Converts the image to grayscale.
left(self): Rotates the image 90 degrees to the left.
right(self): Rotates the image 90 degrees to the right.
mirror(self): Flips the image horizontally.
sharpness(self): Enhances the sharpness of the image.
saturation(self): Increases the saturation of the image.
contrast(self): Enhances the contrast of the image.
blur(self): Applies a blur effect to the image.
UI Components
Buttons: Trigger image transformations like rotation, mirroring, etc.
File List: Displays a list of images from the chosen directory.
Image Display: Shows the current image with the applied effects.
Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
