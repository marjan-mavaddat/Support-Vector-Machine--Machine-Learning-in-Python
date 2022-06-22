# Support-Vector-Machine--Machine-Learning-in-Python
A file named txt.data has already been provided to you in the previous assignment. As you remember from the previous project, this file contains useful data
About 1,000 patients are suspected of having a heart condition called coronary artery disease. This file is actually a table that each
Its row represents a member of the study group and each column represents a specific feature. These features are in accordance with the table
They are named as follows.

age, Ischemia, Diastolic.function, E, A, Grade, E.A, e, a, and e.a.

The features that are underlined are the features that will be considered in this assignment. Values ​​in columns E,
A, e and a are the values ​​measured by the echocardiogram. Assuming that the data in the previous assignment
Identify outliers and do the following:

A. (As before, select about 60% of the samples completely randomly. This set of samples is called the training set) Train
Set). This collection does not change in any way after creation. From this set to teach the SVM algorithm using only the same
Use the previous two properties (A, E). Other examples make up the Set Test. This collection of samples has no contributions
They will not have in training and will only be used to evaluate the performance of the training algorithm. The proposed algorithm for SVM training
Repeat on the tutorial set. After each step of the training (Iteration) classify the error according to Iteration
Draw the desired. Consider the number of repetitions to be 100. As seen in the previous task, the obtained diagram is called the convergence diagram.
Is.

A practical point: it is better to mix the order of the training samples randomly in each repetition and the so-called data
Learn to cut in each repetition. 

B (After the end of the algorithm, calculate the error in practice (empirical error) as a set of training and experiments.
Draw the plot Scatter curve along with the separating superplate on a diagram. Note that in this case the plot Scatter with
The use of training examples is drawn.

Draw the plot Scatter curve with a separating superplate on a diagram. In this case, plot the Scatter using examples.
Draw an experiment.

Repeat steps "t", "s" and "c" in the case where you consider the value of repetition to be equal to 1000. How the results of this
Do you justify the preposition with the concepts of the lesson, such as "bias-variance compromise", "overbalance" and "optimal Bayesian error"?

C) Based on the results you have obtained, how do you compare the performance of the SVM classifier with that of Perceptron?

H (Now use all four attributes A, E, a and e and repeat the previous steps. Note that drawing Plot Scatter for this
Mode is not possible. But the convergence diagram can be obtained in a similar way.

It is also necessary to provide simulation results, describe the results and draw conclusions from them in the mentioned file
