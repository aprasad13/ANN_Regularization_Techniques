# Deep_Learning_Regularization_Techniques

Deep Learning models have so much flexibility and capacity that **overfitting can be a serious problem**, if the training dataset is not big enough. Sure it does well on the training set, but the learned network **doesn't generalize to new examples** that it has never seen!

We will use regularization in our deep learning models in this notebook and see following:
- Regularization will help us reduce overfitting.
- Regularization will drive our weights to lower values.
- L2 regularization and Dropout are two very effective regularization techniques.

Click on the [Jupiter Notebook](https://github.com/aprasad13/Deep_Learning_Regularization_Techniques/blob/master/Deep_Learning_Regularization.ipynb) to access the detailed Code and Visualizations.

Click to assess the [Dataset](https://github.com/aprasad13/Deep_Learning_Regularization_Techniques/blob/master/data.mat)

**Here are the results of our three models**: 

| Model                                         | Train accuracy  | Test accuracy  | 
| ----------------------------------------      | --------------- | ---------------|
| 3-layer NN without regularization             | 95%             | 91.5%          | 
| 3-layer NN with L2-regularization             | 94%             | 93%            | 
| 3-layer NN with dropout                       | 93%             | 95%            | 

Note that regularization hurts training set performance! This is because it limits the ability of the network to overfit to the training set. But since it ultimately gives better test accuracy, it is helping our system. 
