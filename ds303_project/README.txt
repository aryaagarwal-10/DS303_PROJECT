Refer to video explaination given in the folder.

# DS303: Project - Handwritten Text Recognition and Conversion Using Convolutional Neural Network (CNN) Based Deep Learning Model

Even in this age of digital information, people prefer writing information on paper due to the unavailability of digital note-taking devices or because they feel more comfortable writing than typing 					
One of those methods is using Deep learning, more specifically Neural Networks. Neural Networks are designed based on the functionality of neurons in the human brain. 		
Identifying each character will not be enough as words are a sequence of characters, and each word contains similar characters in different sequences . To understand these sequences, a very specific type of Recurrent Neural Network (RNN) , the Long Short Term Memory (LSTM) is used. LSTM divides the image into time steps and attempts to understand where each character occurs and what it means. The placement of these characters in the input image needs to be precise for LSTM to work but human handwriting does not satisfy this requirement. Human writes each character with different dimensions and in different positions each time. Connectionist Temporal Classification (CTC) loss is used to solve this specific problem. CTC attempts all possible placements of characters and takes the sum of all the probabilities. 




## Contribution

1.Pratik Yabaji (210070094)\
2.Arya Agrawal (210070012)\
3.Sumit Londhe (210070089)



## Installation

Please download the dataset from https://fki.tic.heia-fr.ch/databases/iam-handwriting-database .

Please install this libraries in order to run the code.

  Libraries used :
  OS,
  Numpy,
  OpenCV,
  Tensorflow,
  Matplotlib
    


