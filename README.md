# Face Expression Recognition in Keras
 
In this repository, I have developed a Facial Expression Recognition application and deployed it in Flask.

# Goal
To categorize each face based on the emotion shown in the facial expression in to one of seven categories 
 
- `Happy`
- `Sad`
-  `Disgust`
-  `Surprise`
-  `Neutral`
-  `Fear`
-  `Angry`

# Data
The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. 

`Training Set : 28,709 Images` <br/>
`Validation Set : 3,589 Images`

This is what the data looks like : <br/>
![Image1](https://github.com/Aishwarya4823/Face-Expression-Recognition-in-Keras/blob/master/Images/Dataset_Input.PNG)

# Model
This model is inspired by:<br/>
Challenged in representation learning: A report of three machine learning contests. *Neural Networks*, 64, 59-63. [doi:10.1016/j.neunet.2014.09.005](https://arxiv.org/pdf/1307.0414.pdf)
 
I have tried to implement the same model as mentioned in this paper. It looks as follows:<br/>
![Image4](https://github.com/Aishwarya4823/Face-Expression-Recognition-in-Keras/blob/master/Images/model.png)


# Result
The winner of this Kaggle competition achieved an accuracy of 0.71161. My model, achieves an accuracy of 0.6318.<br/>
<br/>
Following are a few outputs of the classification model:</br>
**Ground Truth : Happy**<br/>
![Image2](https://github.com/Aishwarya4823/Face-Expression-Recognition-in-Keras/blob/master/Images/happy.PNG)
<br/>
<br/>
**Group Truth : Surprised**<br/>
![Image3](https://github.com/Aishwarya4823/Face-Expression-Recognition-in-Keras/blob/master/Images/Surprised.PNG)


# How to Run
- Download this repository
- Make sure all dependencies are pre-installed (Note: You would require a GPU to run this repository)
- Run, through your command prompt, `python3 main.py`
- View the results on `0.0.0.0.5000/`

To view the complete code, please have a look at the following:
https://drive.google.com/drive/folders/11SbvwIC8UNNdQ85CqdJZA4qa7gZaAFBp?usp=sharing
