# Neural-Networks
Neural networks are not a new method, the first artificial neural network was devised in 1943, but advances in computational power and speed have made them a much more viable strategy for solving complex problems over the last 5-10 years. Originally devised by mathmaticians and neuroscientists to illustrate the fundamental principles of how brains might work they lost favor in the second half of the 20th century only to surge in popularity in the 20-teens as software engineers used them to resolve mathmatically intractable problems. The application of neural networks to learning problems has been ongoing for 20 years, often to predict student behvior or to parse unstructured data such as student writing samples and provide natural sounding feedback through AI avatars.

# Packages
`library(tidyverse)`<br>
`library(neuralnet)`


<img src="./h1.png" alt="Editor" width="700">
First network model plot, with only 1 hidden layer

<img src="./h2.png" alt="Editor" width="700">
Second network model plot, with 2 hidden layers

# Result

- The prediction accuracy of the model is 94%. The true positive rate (sensitivity) is 93.18% ，indicating that 93.18% of the absent-minded students(not paying attention) was correctly predicted and the true negative rate is 94.64%, showing that 94.69% of the students who are concentrated were corrected predicted.
 
- To sum up, the model successfully predicted whether the students were paying attention 94% of the time. 93.18% of the students who indeed paid attention during the online discussion were predicted to pay attention. 94.64% of students who were predicted not to pay attention during the online discussion, did not actually pay attention.


This is a very simple example of a neural network. Real facial recognition is very complex though. Would a neural network be a good solution for predicting real facial movements? Why, why not? 

 # Comments:
 - A neural network would be a good solution for prediction real facial movements. Recognition+Prediction
 
 - First, instead of just using several features determined by us human, the computer can train itself and learn the critical features that are most useful for face recognition. The solution is to train a Deep Convolutional Neural Network. The computer will be trained to generate 128 measurements for each face. These procedure will incresase the accuracy of face recognition. 
- Second, instead of traditional prediction of making model relying on rather simple relationships, neural networks have the ability to learn and model non-linear and complex relationships, which is really important because in real-life, many of the relationships between inputs and outputs are non-linear as well as complex.
- Third, unlike many other prediction techniques, neural networks do not impose any restrictions on the input variables (like how they should be distributed).
 
- However, there is existing problem that the facial expression of human being varied based on cultural or physiological differences across different populations. Thus, it will be computationally exhausting to learn all the features and predict for all the situations. 
- Nevertheless, it is in all a good approach to predict facial movement using neural network, especially in the educational context, as the online learning is facing a dilemma of tracing and retaining students' attention.
