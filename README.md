# Dogs_Gone_Sideways
Predicts whether the image of a dog is upright or sideways.

The training dataset consists of images categorized into 2 folders. One folder contains upright images (named upright) and other folder contains images that are rotated 90 degrees clockwise (named sideways).

Also, this training dataset is augmented by flipping the image horizontally, performing width shift and height shift

Based on this, a ResNet50 model is trained with the last layer as a custom layer that is used to predict whether the image is upright or is sideways (rotated by 90 degrees).

Validation Accuracy was obtained as 94.3%.

Credits and Motivation: https://www.kaggle.com/dansbecker/exercise-data-augmentation
