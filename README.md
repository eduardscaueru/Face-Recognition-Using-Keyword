# Face recognition using keyword
## Downloading modules
To run this project you must have the following modules: Pillow, tesseract, OpenCV and zipfile36. Below are provided instructions to install all the modules.
### Install Pillow
```
python3 -m pip install --upgrade pip
python3 -m pip install --upgrade Pillow
```
### Install tesseract
Follow the instructions from [this link](https://github.com/tesseract-ocr/tessdoc/blob/master/Home.md).
### Install OpenCV
Follow the instructions from [this link](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_setup/py_setup_in_windows/py_setup_in_windows.html).
### Install zipfile36
```
pip install zipfile36
```
## What does this project do ?
You must give input a zipfile name in which are png images. The images need to have text and faces. It works best with newspaper pages in which are both text and faces. Then you must give a keyword for input. Now, the program converts the text from the images for each image into string and searches for the keyword. If found it searches for faces and if there are faces it puts them in a sheet, but if it doesn't, it will paste a image with text informing that there were no faces found.
In the end it's generated an image with all the results.
