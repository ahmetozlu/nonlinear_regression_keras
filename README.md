# NON-LINEAR REGRESSION WITH KERAS

This repository focuses training of a neural network for regression prediction using "Keras". Please check [this medium post](https://medium.com/analytics-vidhya/non-linear-regression-with-deep-learning-221584ccc8c2?source=---------2------------------) for all of the theoretical and practical details! ***Please contact if you need professional projects are based non-linear regression with the super high accuracy.***

## Theory

In this study,"[the yacht hydrodynamics data set](http://archive.ics.uci.edu/ml/datasets/Yacht+Hydrodynamics)" was used as a case study and it was reached 0.99 R-square value which is awesome! 

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/85933671-78fa2300-b8e2-11ea-8fb4-eb206d1a3061.png">  
</p>

To implement a neural network for regression, it must to be defined the architecture itself. It is used a simple Multilayer Perceptron (MLP) as shown at the figure below to define the architecture.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/103465554-d5d10d00-4d4d-11eb-9e32-feb73a09eb2c.png" | width="850">  
</p>

And, here is the implementation using Keras:

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/85933731-4f8dc700-b8e3-11ea-8166-a9d97702c4de.png">  
</p>

The approaches and codes that shared in this tutorial can be adopted for any other regression tasks such as "[computer hardware](http://archive.ics.uci.edu/ml/datasets/Computer+Hardware)", "[energy efficiency](http://archive.ics.uci.edu/ml/datasets/Energy+efficiency)" and more!

## Experimental Results

Here are the results from left to right: *plot of training history, plot of actual vs prediction for training set, plot of actual vs prediction for validation set*.

<p align="center">
  <img src="https://user-images.githubusercontent.com/22610163/85932753-8067ff00-b8d7-11ea-9788-a2bfd21427e2.png" | width=275>  
  <img src="https://user-images.githubusercontent.com/22610163/85932752-7fcf6880-b8d7-11ea-9d27-cf675ca7e1e1.png" | width=275>  
  <img src="https://user-images.githubusercontent.com/22610163/85932751-7f36d200-b8d7-11ea-9b33-c4888199d5be.png" | width=275>  
</p>

**[Here is the main python notebook](https://github.com/ahmetozlu/keras-nonlinear-regression/blob/master/keras-nonlinear-regression.ipynb) that explains all of the stuff step by step!**

## Citation
If you use this code for your publications, please cite it as:

    @ONLINE{hse,
        author = "Ahmet Özlü",
        title  = "Non-linear regression using Keras",
        year   = "2020",
        url    = "https://github.com/ahmetozlu/keras-nonlinear-regression"
    }

## Author
Ahmet Özlü

## License
This system is available under the MIT license. See the LICENSE file for more info.
