1. 3x3 Convolutions

   We used for feature extraction which helps in detecting edges, objects, parts of objects.

2. 1x1 Convolutions

   We used to reduce the channels & also segments the features.

3. DropOut

   helps in reducing overfitting, idea is it disables some neurons/activations which helps in accuracy.

4. MaxPooling

   It helps the next layer to identify whether there's a edge/pattern are present or not.

5. Receptive Field

   At every layer what's the size of the image our model can see. our goal is at the last layer the rf should be the size of the image.

6. How many layers

   We add layers so that it can have the full receptive field .

7. SoftMax

   We add this layer so that it converts the activation to probabilities like values 	and normalizes it.

8. Learning Rate,

   During gradient update, how fast or slow our gradient needs to update depends on learning rate.

9. Kernels and how do we decide the number of kernels.

   Kernels are also known as filters it helps in extraction of features. we increase the no of kernels gradually.

10. Batch Normalization

    We normalize the values by mean & stdv through channels.

11. Image Normalization

    It changes the range of values, increases the intensity.

12. Position of MaxPooling

    If we place in the middle of the layer it helps the model, as compared to placing it near the end of the layers. 

13. Concept of Transition Layers

    To reduce the no of channels we introduce the 1x1 convolution, then followed by normal convolution.

14. Position of Transition Layer

    Generally we use the transition layer at the mid of the layers.

15. Number of Epochs and when to increase them

    When the training accuracy haven't reached to a point where the model learned properly, till then we can increase the number of epocs.

16. When do we introduce DropOut, or when do we know we have some overfitting

    To reduce overfitting we use Dropout, when val accuracy doesn't decrease after no of epocs then overfitting occurs.

17. The distance of MaxPooling from Prediction

    Maxpooling should be quite far way from the Prediction.

18. The distance of Batch Normalization from Prediction

    We can use it just before the flatten layer it helps in normalizing the gradients.

19. When do we stop convolutions and go ahead with a larger kernel or some other alternative (which we have not yet covered)

    

20. How do we know our network is not going well, comparatively, very early

21. Batch Size, and effects of batch size

22. When to add validation checks

23. LR schedule and concept behind it

24. Adam vs SGD