https://persephone007.github.io/Sign-Language-with-Machine-Learning/
# Sign Language with Machine Learning
by Charlene Gray and Sathya Kulatunga


In this project we wanted to create a model that would recognize any given ASL sign language alphabet gesture and output the corresponding letter in the alphabet.

The first step was to create our own data sets. We created three data sets of three skin tones using small videos of hand gestures then converted them into pictures. At the end we were able to gather about 200 pictures corresponding to each letter of the alphabet, or about 5000 total files for our dataset. All the images then needed to be cropped and processed.

Our Data was then uploaded to AWS. We pulled the data from AWS to create numpy arrays of data to feed to our model in  Jupyter Notebook. Labels(Y) were attached to each data point using one hot encoding.

The machine was then trained and ready for testing. 

Further training is required as the machine does not recognize all hand signals when testing. Changing pixels, nodes, and tweeking the model more may produce better results in the future. 

We also made tablaeu datasets to represent Deaf statistics and hosted them on out webpage. 
