# facemask
Recognize a person with and without a face mask

Description: For the purpose of this project, you can imagine a case here where you may want to detect a person, and then classify if that person is wearing a mask or a respirator or nothing at all and take an action based on that decision.

We can get away with a single-stage classification by just adding a label and training set for "masked person", much as imagenet can detect a person already, so a masked person is going to be very similar to a ordinary person, however, I don't imagine it will take all that much training to distinguish the differences that make one masked or not.

Task
 - If you're new to AI, study "transfer learning" on medium.com - great place to start. Be prepared to clear your calendar for the next year.
 - Download Juypter Notebook to work on a system with a GPU
 - Install tensorflow and keras

 
nVidia:

The nVidia Jetson Metropolis DeepStream SDK has gstreamer support and multi-stage inferencing. For instance, it'll do object detection, detect a car, then it will feed a secondary classifier that outputs probabilities on make or model, a third layer for color, etc.

 
Online References:

   https://towardsdatascience.com/transfer-learning-using-mobilenet-and-keras-c75daf7ff299
   https://towardsdatascience.com/transfer-learning-for-image-classification-using-keras-c47ccf09c8c8
   https://towardsdatascience.com/keras-transfer-learning-for-beginners-6c9b8b7143e

Books:
   https://www.amazon.com/_/dp/1492032646?tag=oreilly20-20
   
If you're not familiar with nvidia Jetson, check out: 

   https://www.youtube.com/watch?v=BkZ1n_1F-Cg
   
