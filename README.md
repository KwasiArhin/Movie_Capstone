# Scene Recognition

Analysing cinema is a time-consuming process. In the cinematography domain alone, there's a lot of factors to consider, such as shot scale, shot composition, camera movement, color, lighting, etc. Whatever you shoot is in some way influenced by what you've watched. There's only so much one can watch, and even lesser that one can analyse thoroughly.

This is where neural networks offer ample promise. They can recognise patterns in images that weren't possible until less than a decade ago, thus offering an unimaginable speed up in analysing cinema.

## Data:
Thus, the dataset for this project had to be constructed from scratch. It is diverse, consisting of samples from over 300 movies, collected from various sources. Each image had to be looked over several times to ensure that it had been categorised correctly.

In total, the dataset consists of 2,724 (2,180 training + 544 validation) images, split into 6 shot types:

1. Long Shot: 263 images
2. Medium Shot: 142 images
3. Medium Close Up: 223 images
4. Close Up: 841 images
5. Extreme Close Up:1041 images
6. Extreme Wide Shot:210 images

### Shot Types:

###  1. Extreme Closeup 

![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/Darren-Scene-054-01.jpg?raw=true)

Extreme Close Up-An Extreme Close Up (ECU) highly zooms in to any one feature of the subject to draw attention to that feature specifically.

### 2. Closeup 

![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/Juice-Scene-0758-02.jpg?raw=true)

Close Up-A Close Up (CU) shows the face of the character, sometimes including the neck/shoulders.Emphasises the facial expressions of the character.
### 3. Medium Closeup 
![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/babydriver018.jpg?raw=true)

Medium Close Up-A Medium Close Up (MCU) shows the character from the chest/shoulders up. It allows one to see nuances of the character's facial expressions, and some upper-body language.
### 4. Medium

![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/Pulp_Fiction-Scene-0949-01.jpg?raw=true)

Medium Shot- A Medium Shot (MS) shows the character from the waist up.It allows one to see nuances of the character's body language, and to some degree the facial expressions.

### 5. Longshot 

![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/django-Scene-0398-02.jpg?raw=true)

Long Shot-A Long Shot (LS) includes characters in their entirety, and a large portion of the surrounding area.

### 6. Extreme Wide Shot 
![](https://github.com/KwasiArhin/Movie_Capstone/blob/master/README_imgs/ews-Scene-004-01.jpg?raw=true)

Extreme Wide Shot-An Extreme Wide Shot (EWS) emphasises the vastness of the location.When there is a subject, it usually occupies a very small part of the frame.


## Conclusions

Even though we are getting great accuracy with our model there is still alot of work to do. Most of it has to do with the dataset, which has to be built out bigger. Because as we can see the model has learned ecu well because of the sheer number of them in our dataset.

#### Future Work

   * Use it to generate stats for film analysis 
   * Integration into a live video  
   * Add heatmaps to show activations 
