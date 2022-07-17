# Celebrity_Face_Recognition
A <code>**Data Science Project**</code> to Identify the <code>**Name of Celebrity**</code> using his/her image.

- The Model was trained on the <code>**image of 5 person**</code> (Virat Kohli, Serena Williams, Roger Federer, Maria Sharapova, Lionel Messi) and can identify them.
- <code>**StandardScaler()**</code> was used to scale the data and <code>**svm classifier**</code> was used to train the model.
- The model was trained for <code>**374 images**</code> downloaded from google and achieved an <code>**accuracy of 72%**</code>.
- The accuracy can be increased by using more images for training and testing.
- <code>**OpenCV**</code> was used to crop the images automatically and focus only on the face part.
- <code>**pyplot**</code> was used to plot the images correctly for better <code>**visualization of data**</code>.
- <code>**wavelet function**</code> was used to get the features of the face to identify the name correctly.
- The model was saved in the form of <code>**pickle file**</code> to avoid the training of model again and the classes was saved in the <code>**json file**</code>.

> iypnb file : [Click here](https://github.com/kabhishek20/Celebrity_Face_Recognition/blob/main/Face_Recognition.ipynb)

> pickle file : [Click here](https://github.com/kabhishek20/Celebrity_Face_Recognition/blob/main/Face_Recognition_Model.pickle)

> json file : [Click here](https://github.com/kabhishek20/Celebrity_Face_Recognition/blob/main/class_dictionary.json)