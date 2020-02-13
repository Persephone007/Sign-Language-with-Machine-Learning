https://persephone007.github.io/Sign-Language-with-Machine-Learning/
# Sign Language with Machine Learning
by Charlene Gray and Sathya Kulatunga


In this project we needed to create a model to recognize ASL alphabet where the machine will recognize any given sign language alphabet gesture and output the corresponding letter in the alphabet.

The first step was to create our own data sets; We have created three data sets of three skin tones using small videos of hand gestures then converted them into pictures. At the end we were able to gather about 200 pictures corresponding to each letter of the alphabet.

Then cropped all the pictures and uploaded them into AWS.

From AWS we pulled all the pictures in to Jupyter Notebook then converted all the pictures to list of arrays.

Then used those arrays to train the model and make predictions.

Based on the training given so far Machine is not able to recognize the full alphabet if a random sign language letter was given from an outside source, however with more training with different picture resolutions will improve the accuracy of the Machine.
