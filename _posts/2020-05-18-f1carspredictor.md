## F1 cars predictor

Precict which team a car belongs to by analysing an image. The image can be from any angle.
This is an end-to-end example.

[Look here for Setup and Results](https://github.com/DexterDSilva/f1cars-detector)

This is a good example of a complete workflow
  - collecting data using google web search (local) 
  - cleaning the data (removing duplicate images and other rubbish) (local) 
  - porting data to Google Colab - When i was doing this I did not have my Github a/c organised properly  
  Otherwise I would have done git init and ported the local repo to github  
  From Google Colab it is easy to clone the Github repo 
  - Once the data is in repo start a new jupyter notebook and select a GPU for training.  
  - Download the trained model to the local dir  
  - Modify the webapp to point to the trained model and do the predictions
  
Note: I only used about 75 images per class (10 classes) to cut down on the training time.

I used Fastai's recommended Starlette web api and with a bit of playing around with the css and html file got something suitable.

This is only meant for demo purposes and to motivate me to carry on with the ret of the course.

Suggested Improvements:
 - [ ] Add more training data
 - [ ] Clean training data 
 - [ ] Overfit and then play around with hyperparameters
 - [ ] Give webapp better UI
 
> Note to self: Put results on this page too.
---
  ![](/images/aero-robot-with-logo-small.png)![](/images/onpointai-logo-small.png)
