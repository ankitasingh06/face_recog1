# face_recog1

Under the topic of Transferred Learning ,The task was to make a model which can predict any one's face whose image dataset is available with us. 

I have created this model with my own image dataset for my face recognition. 

A facial recognition system is a technology capable of identifying or verifying a person from a digital image or a video frame from a video source. 

Program uses "cv2" concpet for capturing images(Live streaming) and with the help of "CNN" Pretrained model(Mobilenet) and by using the concept of "transfer learning" we are able to create this face recognition model.

Transfer Learning is the method to create your own model with the use of parameters(bias & weights) of pre-trained model. It is an alternative and helpful method. Transfer learning is just using a model which is pretrained and stacking your layers on top of the the pretrained model for predictions based on your custom dataset.

Transfer Learning gives following advantages-
1. Less computational power is required as the weights are known.
2. space efficient.
3. As CNN deals with big data and we can-not have even our own 1,00,000 images, so with the limited no. of data we are able to find output.

#Idea:-With the better accuracy given by our own CNN model we can use this in face recognition of any person.
