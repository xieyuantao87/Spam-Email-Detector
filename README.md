# Spam-Email-Detector
In this project, our progam learns how to detect a spam email. 
The progam is first trained by some data, and then it try to detected a spam email. 
The feature of email is defined as following: 
there are some words, which are usaully in spam email. We use these words to define a dictionary
We defined a vector to feature a email, with each element corresponding toa word in dictionary. 
If one word in dictionary appears in a email, we will set the corresponding element in feature vector to be 1; 
