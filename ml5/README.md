# ml5js Style Transfer system

This code allows the quick and easy testing of style transfer models for ml5js.

All models created are original, except for Painting 1 and Mathura, which are part of the original ml5js library.
Please feel free to add more and contribute to this project on Github.

## Operating Instructions
Connect Your Webcam. Click Change Style to make a new selection.

You must Stop and then Start to change models. It can take some time, and you may need to repeat.

To load a model, wait until the text at the top of the screen reads "Model Loaded". Then press the green start button.
![alt text](https://raw.githubusercontent.com/unexpector/ml5js-Style-Gallery/master/images/model_loaded.jpg)

To change model, select the model name from the dropdown list. 

Then click the blue "Change Style" button. Wait 5 seconds, then click to stop and start green buttons. Repeat the stop start button push again if it does not work.

![alt text](https://raw.githubusercontent.com/unexpector/ml5js-Style-Gallery/master/images/model_change.jpg)

## How To Use

Clone the repository and upload to any webserver, or run locally. Needs to be run in a https environment.

### Adding New Models
To add new models, upload each  model folder to the models directory.

![alt text](https://raw.githubusercontent.com/unexpector/ml5js-Style-Gallery/master/images/model_folder.jpg)

When model is uploaded, add a new menu option to the menu.html file. This will make the model available to all views.
27/Aug/2018 8:20
![alt text](https://raw.githubusercontent.com/unexpector/ml5js-Style-Gallery/master/images/model_menu.jpg)

## To Do
- Get fullscreen mode working 
- Add more trained models
- Centre the overlay canvas 
- Add more models to libray