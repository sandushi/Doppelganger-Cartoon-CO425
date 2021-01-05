# Human image - Human image Mapping #

## Training for detecting landmarks of human faces ##

  * [custom-dlib-lanmarks-predictor-human-faces](https://github.com/sandushi/Doppelganger-Cartoon-CO425/tree/main/custom-dlib-lanmarks-predictor-human-faces)
    * In here the training steps & results are contained.
    
## Method Explanation ##
  
  * In this method, the mapping between human images. 
  * _Dataset_
    * This dataset is contained with the already existing Doppelganger human images for 70 cartoon characters (226 images) with the cartoon images in each folder. 
  * _steps_
    * Detect the landmarks of each face of images in datset
    * Calculate the distance & area between landmarks for each face
    * Save the distances and areas in a CSV file along with the path of corresponding cartoon image 
    * Insert a new human images, Detect lanmarks and Calculate same distances and areas
    * Compare the feature vector of inserted image with the feature vectors stored in CSV file
    * Get the most matching 5 images 
    
## Results ##

The 5 top most matching images for each tested image is displayed here.

    
