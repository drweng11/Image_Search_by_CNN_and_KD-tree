To run the code, please install requried lib and 
download image data and put into the corresponding folder.

# Env. and Library requried:
Python 3.6
keras
sklearn
cv2
numpy
json
scipy
and others ...

# Images and model file
Add images from geological_similarity.zip in folder ./code/geological_similarity/geological_similarity. If no images, the code cannot run.
Note that the trained model file of CNN, stored as as "cnn.h5" and the kd-tree indexed file stored as "kt_x.pickle"

# Running
Run the shell script, run.sh, under folder ./code
$ ./run.sh

# Number of top-k, input image file path
Note that you can change # of top-k returns and should input file path of a image for a search.
