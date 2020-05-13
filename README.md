# Scene Recognition

The is able to successfully distinguish 6 different shot types:

### Shot Types:

###  1. Extreme Closeup 

![Darren-Scene-054-01](C:\Users\Kwasi\Documents\github\Movie_Capstone\README_imgs\Darren-Scene-054-01.jpg)



### 2. Closeup 



![Juice-Scene-0758-02](C:\Users\Kwasi\Documents\github\Movie_Capstone\README_imgs\Juice-Scene-0758-02.jpg)

### 3. Medium Closeup 

![Drive-Scene-336-01](C:\Users\Kwasi\Desktop\Movie Capstone\Train\MCU\Drive-Scene-336-01.jpg)

### 4. Medium

![Pulp_Fiction-Scene-0949-01](C:\Users\Kwasi\Documents\github\Movie_Capstone\README_imgs\Pulp_Fiction-Scene-0949-01.jpg)

### 5. Longshot 

![django-Scene-0398-02](C:\Users\Kwasi\Documents\github\Movie_Capstone\README_imgs\django-Scene-0398-02.jpg)

### 6. Extreme Wide Shot 



![ews-Scene-004-01](C:\Users\Kwasi\Documents\github\Movie_Capstone\README_imgs\ews-Scene-004-01.jpg)

## Data:
Thus, the dataset for this project had to be constructed from scratch. It is diverse, consisting of samples from over 300 movies, collected from various sources. Each image had to be looked over several times to ensure that it had been categorised correctly.

In total, the dataset consists of 2,724 (2,180 training + 544 validation) images, split into 6 shot types:

1. Long Shot: 263 images
2. Medium Shot: 142 images
3. Medium Close Up: 223 images
4. Close Up: 841 images
5. Extreme Close Up:1041 images
6. Extreme Wide Shot:210 images

## Conclusions

Even though we are getting great accuracy with our model there is still alot of work to do. Most of it has to do with the dataset, which has to be built out bigger. Because as we can see the model has learned ecu well because of the sheer number of them in our dataset.

#### Future Work

   * Use it to generate stats for film analysis 
   * Integration into a live video  
   * Add heatmaps to show activations 
