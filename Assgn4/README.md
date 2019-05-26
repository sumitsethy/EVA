1. 3x3 Convolutions

   used for feature extraction which helps in detecting edges, objects, parts of objects.

2. 1x1 Convolutions

   used to reduce the channels & also segments the features.

3. DropOut

   helps in reducing overfitting, idea is it disables some neurons/activations which helps in accuracy.

4. MaxPooling

   it helps the next layer to identify whether there's a edge/pattern are present or not.

5. Receptive Field

   at every layer what's the size of the image our model can see. our goal is at the last layer the rf should be the size of the image.

6. How many layers

   we add layers so that it can have the full receptive field .

7. SoftMax

   we add this layer so that model can 

8. Learning Rate,

9. Kernels and how do we decide the number of kernels?

10. Batch Normalization,

11. Image Normalization,

12. Position of MaxPooling,

13. Concept of Transition Layers,

14. Position of Transition Layer,

15. Number of Epochs and when to increase them,

16. When do we introduce DropOut, or when do we know we have some overfitting

17. The distance of MaxPooling from Prediction,

18. The distance of Batch Normalization from Prediction,

19. When do we stop convolutions and go ahead with a larger kernel or some other alternative (which we have not yet covered)

20. How do we know our network is not going well, comparatively, very early

21. Batch Size, and effects of batch size

22. When to add validation checks

23. LR schedule and concept behind it

24. Adam vs SGD