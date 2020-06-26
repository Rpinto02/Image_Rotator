# Image_Rotator

## Introduction
This is 24hour challenge to create a CNN classificator using the CIFAR10-CNN model to classify images according to it's position (upright, rotated-left, rotated right and upside-down). As well as aditional code to rotate and save the images according to the prediction in the model.

Inside the Challenge.pdf you can find indepth details of my difficulties and solutions during this challenge.

## Getting started

### Dependencies

* Python 3.8
* Scipy
* Matplotlib
* Pillow
* Keras
* Pandas, Numpy



### Instructions

* Open the notebook image_rotator_CIFAR10-CNN and follow the comments inside, it is self-explanatory.
  * Due to file size limitations on github free the original data as well as respective folders can't be found in the repository. If you wish to replicate this, please contact me so I can send you the data.
  * You should replace the paths inisde the code with your own paths.
  * Furthermore the notebook initial code is to ilustrate the step by step I describe in the Challenge.pdf file.

## License
[MIT](https://opensource.org/licenses/MIT)

## Issue/Bug

Please open issues on github to report bugs or make feature requests.

## Further Developments

Since it was a 24hour challenge, I had no time to parameter tuning and investigate why the predictions weren't accurate (in the code you can find one example). However with given time I would start there, testing with different parameters, however our accuracy was 96%, so first I would need to find a way to verify this accuracy.
