## Experiment with different configurations of the number of hidden layers, the number of hidden neurons, activation functions, learning rates, and weight initializations (Gaussian, uniform, etc.).
* The error of the model did not change much from 3500 to 4000 epochs .
* Weight initializations: Tried random zeroes , zeroes with Gaussian distribution.
* Random and Gaussian gave better results, So used Gaussian
* Activation Function: Used Sigmoid and Relu.Sigmoid had better accuracy
* No. of hidden layers:2.
* No. of hidden neurons:5
* Learning rates: best results came from 0.1 (Had lower accuracies for both 0.3 (>0.1) and
0.01(<0.1))
Final Values: Epoch=5000, Learning rate = 0.1, 2 layers, Sigmoid Activation

### Sigmoid function
Accuracy = 89.6%

### Relu 
Accuracy = 57.3%

## Use an 80-20 train-test split to train/evaluate your model, and report the accuracy and F-score for
the test set. ( Results of 5-cross-fold validation)
1. Accuracies: [89.38356164383562, 89.72602739726028, 91.78082191780823,
88.6986301369863, 89.72602739726028]
2. F-Scores: [0.8896797153024911, 0.9013157894736842, 0.9215686274509803,
0.8925081433224755, 0.8863636363636364]
3. Mean Accuracy: 89.863 %
4. Accuracy stddev: 1.151
5. Mean F-Score: 0.898
6. F-score stddev: 0.014
