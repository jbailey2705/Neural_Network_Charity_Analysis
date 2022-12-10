# Neural_Network_Charity_Analysis
Neural Networks and Deep Learning Models

## Enviroment/Resources
* `Tensorflow v. 2.11`
* `[Colaboratory](https://colab.research.google.com/)`

## Overview
1. Compare the differences of the traditional, regression, and neural machine learning models.
2. Describe the perceptron model and its components.
3. Using TensorFlow, implement neural network models.
4. Explain how different neural network structures change algorithm performance.
5. Preprocess and construct datasets for neural network models.
6. Compare the differences between neural network models and deep neural networks.
7. Implement deep neural network models using TensorFlow.
8. Save trained TensorFlow models for later use.Describe the perceptron model and its components.

## Purpose
A foundation, Alphabet Soup, wants to predict where it should make investments. Goal, use machine learning and neural networks to apply features on a provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. Initial file has **34,000** organizations that provides a list of columns that capture metadata about each organization from past successful fundings.

## Results
1. **What variable(s) are considered the target(s) for your model?**
   We'll check to see if the target is marked as `successful` in the DataFrame, which would indicat that it has been successfully funded by AlphabetSoup.

2. **What variable(s) are considered to be the features for your model?**
   The `IS_SUCCESSFUL` column  was used to feature this dataset.

3. **What variable(s) are neither targets nor features, and should be removed from the input data?**
   Both `EIN` and `NAME` columns **will not** increase the accuracy of the model, they can be removed to improve code efficiency.
   
4. **How many neurons, layers, and activation functions did you select for your neural network model, and why?**
   The `optimized model`, **layer 1** started with `120 neurons` with a relu activation. **Layer 2**, dropped to `80 neurons` and continued with the relu      activation. 
   The `sigmoid activation` appeared to be the better fit for **layers 3** `40 neurons` and layer 4 `20 neurons`.

![Dev3_Code_Model](https://user-images.githubusercontent.com/109354592/206861026-3b075711-3d35-43f6-be86-ad136070df68.png)
![Dev_3_Seq_Model](https://user-images.githubusercontent.com/109354592/206861040-82e494d1-097d-4c57-9978-628496ff9c8f.png)







   
   
