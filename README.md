# cancer-neural-nets

(a)	State and Explain the final Algorithm

The assumptions used for the Neural Network Model are:
>test_size= 0.2 (Using 20% of the test size)
>hidden_layer_sizes = (12, 8, 1)
Where 12 signifies the number of inputs, 8 signify the number of hidden layers and 1 signifies the number of output.
>max_iter=10000
Where max_iter signifies the maximum number of iterations of the algorithm.
>random_state = 100
Where random_state signifies liberty given to the algorithm to harness the randomness.

(b)	Evaluating the Algorithm
 
>From the confusion matrix we can say that the neural network cannot predict the True Negative (0).
>The precision (0.60), recall (0.75) and the f1-score (0.67) of Class 0 (No Remission) have values that are more than 0 and the data provided holds a significance on the algorithm and has effects on it.
>On the other hand, the precision, recall and the f1-score all three are 0.00, this depicts that the data provided in Class 1 (Remission) has no effects on the algorithm.
> Resulting in the accuracy of the algorithm being 0.50 as only half of the algorithm can only satisfy half of the problem statement from the data provided.

(c) Comparing the Neural Network Algorithm to the Logistical Regression Algorithm.

>Even if the accuracy and support are the same in both algorithms, In the Logistical Regression Algorithm, the confusion matrix depicts that the predicted class, as well as the actual class, have values (2, 2, 1, 1) (True Positive, False Negative, False Positive, False Negative) respectively. Whereas in Neural Network Algorithm the confusion matrix the values are (3, 1, 2, 0) so as the True Negative is 0 its prediction is bound to be incorrect.

(d)	Conclusion and Next Steps
a.	Summarize key insights
>By glancing through the dataset, accessing the outputs of both models, we can say that the dataset is very small.
>The data in the dataset also does not seem to be impactful to any kind of a prediction when it comes to Class 1 values especially.
b.	Propose next steps that can be used to improve the algorithm
> Therefore, Mr. John Hughes should be adding more meaningful data in Class 1, to make the algorithm work in a better way eventually helping it to predict more efficiently.
>The confusion matrix for both the algorithms show an accuracy of 0.50, this shall increase when the data is balanced, more effective and complementing the problem statement when it comes to improvements.
