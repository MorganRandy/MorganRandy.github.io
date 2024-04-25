# First Day on FastAI

Fastai is really cool and exciting. It is crazy to think that since 2015, the idea of training an AI model to categorise images was crazy, and now it is easy. The AI community has really taken this 
break through technology and run with it. Models like dall-e 2 have been developed to generate its own arbitrary images from an input of just a few words. The capabilities of these models is unthinkable 
with how fast this technology is evolving. The mind blowing part is that the technology is not only developed by the coder but it is also able to teach itself in very short periods of time with a few 
simple commands from the fastai library. The model learns from a data set provided by the user which can be of a size as small as 50 items and then outputs results from what it learnt. The results are then
output in a table like the one shown below. 

| Epoch  | Train Loss | Valid Loss | Error Rate |  Time | 
| ------ | ---------- | ---------- | ---------- | ----- |
|    0   |  0.619305  |  1.113084  |  0.333333  | 00:06 |
| ------ | ---------- | ---------- | ---------- | ------|
|    0   |  0.041649  |  0.110463  |  0.053333  | 00:06 |
|    1   |  0.030028  |  0.007707  |  0.000000  | 00:07 |
|    2   |  0.025199  |  0.004377  |  0.000000  | 00:07 |

In a lesson by Jeremy Howard, the lead developer of fastai, he programs a simple model to categorise images of birds and forests in under 2 minutes. After he writes the program utilising the pre-trained
*resnet18* computer vision model, he then runs it which shows in just 7 seconds, the model has taught itself to be able to differentiate between the two types with 100% confidence. The second round of runs
in the table (epoch 0-2) is using the fastai command *.fine_tune()* which does exactly that: automatically fine tunes the model by adjusting the weights at the input stage so that the model learns to
recognise the new dataset that it is being presented with. In this case, the dataset has only 2 categories, so it is fine tuned to this smaller data set rather than the thousands of categories it was 
pre-trained with, hence the increase in accuracy.   

So thanks to the advancements in fastAI, the possible applications for AI is continuously growing. Some examples; 
- Image recognition
- Image segmentation
- Analysis of tabular data for income prediction
- Recommendation systems by collaborative filtering 
