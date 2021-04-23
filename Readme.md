# Driver Assist System

As someone who has driven many hours and many miles, I was always curious if there was anything out there that can help me while I drive. So using python and a number of different topics learned throughout this time.

The first, is a drowsiness detector. Essentially using a live feed directed to the drivers face that will alert them if their eyes happen to close.

The second, is a model that determine was street signs are in an image.


## Drowsiness
This program is used to detect drowsiness for any given person. If the eyes have been closed for a long period of time, the program will alert the user by playing an alarm.

A pre-trained, frontal face detector from Dlib's library was utilized. This is based on a modification to the Histogram of Oriented Gradients in combination with Linear SVM for classification

![Screen%20Shot%202021-04-22%20at%2010.53.59%20PM.png](attachment:Screen%20Shot%202021-04-22%20at%2010.53.59%20PM.png)

![Screen%20Shot%202021-04-22%20at%2010.54.30%20PM.png](attachment:Screen%20Shot%202021-04-22%20at%2010.54.30%20PM.png)


## Traffic Sign Recognition
In this section of the project, PyTorch was used to classify traffic signs. A model was trained to decode traffic signs from natural images by using the German Traffic Sign Dataset.

The model reached 99.3% test set accuracy   

The German Traffic Sign Recofnition Benchmark is provided by the Institut fur Neuroinformatik group. It was published for a competition held in 2011. Images are spread across 43 different types of traffic signs and contain a total of 39,209 train examples and 12,630 tests.

![Screen%20Shot%202021-04-22%20at%2010.56.42%20PM.png](attachment:Screen%20Shot%202021-04-22%20at%2010.56.42%20PM.png)

# Future Works
I hope to implement other systems and better ones as i get better in programming.

Roadway Detector
Lane-Keep Assist
Auto-Brakes


```python

```
