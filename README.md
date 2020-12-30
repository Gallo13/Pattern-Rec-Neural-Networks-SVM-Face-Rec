# Pattern-Rec-Neural-Networks-SVM-Face-Rec
Using SVM for Classification of data Face Recognition

Part 1
------
Pick a dataset for classification with number attributes 3-5, number of classes between 3-5
and number of patterns 300-500. Divide it into 2 datasets: training(80%) and testing(20%) if
there is no initial division. If there is an initial division, do not change it.

a) Perform SVC with linear kernel with scikit-learn and do the plotting.

b) Perform muticlass classification, calculate the score and probabilities and do the plotting.

c) Perform binary classification using non-linear SVM with RBG kernel where the target to predict
is an XOR of the inputs and one more logic function by your choice. Make plotting the color map
which illustrates the decision function learned by the SVC.
 -----------------------------------------
Seeds Dataset Description
The examined group comprised kernels belonging to three different variety of wheat: Kama, Rosa and Canadian, 70 elements each, randomly selected for the experiment. High quality visualization of the kernel structure was detected using a soft X-ray technique.
Attribute Information:
To construct the data, seven geometric parameters of wheat kernels were measured:
• Area
• Perimeter
• Compactness
• Length of kernel
• Width of kernel
• Asymmetry Coefficient
• Length of kernel groove
All of the parameters are real-valued continuous.
Target is labeled as 1, 2 and 3.
1: Kama 2: Rosa 3: Canadian
Link: http://archive.ics.uci.edu/ml/datasets/seeds
 -----------------------------------------
Part 2
------
Perform face recognition using the approach presented in https://machinelearningmastery.com/how-to-develop-a-face-recognition-system-using-facenet-in-keras-and-an-svm-classifier/
