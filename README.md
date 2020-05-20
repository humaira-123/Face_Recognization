# Face_Recognization

The above model is a model of face recognization. This model is trained with two faces, one of mine and one of my friend. I trained this model with 100 images of each and it gave me an accuracy of 99+ percentage. 

Here are the steps for creating the model:

*First, I clicked some images using cv2 module and HaarCascade model. Then I stored those images in a folder.
The code of gathering images has also been uploaded in the repository.

*Then, I imported all the necessary libraries and modules required for the model.

*Then I loaded the MobileNet model

*Then I used transfer learning to train my own model by using the MobileNet model. I freezed all the layers of MobileNet model, removed the outpur layer, added my own layers to be trained, and then again added the output layer.

*After compiling the model, I did some augementation with the images, trained the model and then predicted some of the faces. 

That's it and my very own model of face recognization is ready to be used. 
