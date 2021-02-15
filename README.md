# This repository will be archived as the contents have moved [here](https://github.com/joshmurr/machine-learnings) to keep things in one place.

---

## Lecture Slides

[Part 1](https://docs.google.com/presentation/d/1vfH3TzpFDXsYprBvngnzpUAa1rZ09BiS4fM9z1b75SI/edit?usp=sharing)
[Part 2](https://docs.google.com/presentation/d/1w53_d7_Nh747I58kBRUZZVas2LvXKm9Jknuxygeb9-U/edit?usp=sharing)

## Training a Model

1. Go to  https://colab.research.google.com/
2. Click on the _Github_ tab.
3. Paste in this link: https://github.com/joshmurr/DI_TrainYourOwnGAN/blob/master/DI_TrainYourOwnGAN.ipynb
4. Click on the magnifiying glass.

## Downloading Your Model

1. Go to https://drive.google.com
2. Go into the folder 'DI_Workshop_Output'
3. Go into the folder 'model'
4. Right click on the foler 'converted' and click _Download_.
5. Unzip the folder you have downloaded.


## Using Your Model Online

1. __!!! USE GOOGLE CHROME !!!__
2. Go to https://learning-to-learn-to-see.netlify.app/
3. Click on _Upload_.
4. Click on _Upload Model (.json)_ and select the file called `model.json`.
5. Click on _Upload Model (.bin)_ and select _all_ the `.bin` files in the folder you downloaded.
6. Click _Init Cam_ to allow Chrome access to your webcam.
7. Click on _Step_ a couple times to produce single images and make sure it's working.
8. Click on _Play_ to interact with your webcam.

__Note: The quality of the interaction is highly dependant on whether you have a dedicated GPU or not (like in a gaming laptop). If you _do_ it should run pretty quickly. If you _do not_ it will unfortunately be quite slow, but hopefully quick enough to still get a sense of how the model runs!__

__Note 2: This is all quite experimental work making TensorflowJS (Tensorflow on the web) do stuff it was never really meant to do. So I can't gurantee it will work the same for everyone... But I still hope you gain something from the process any way!__

