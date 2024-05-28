
# 15-Class Handwritten Digit Pairs Classification by Machine Learning

This is for ECE4200/5420-Fundamentals of Machine Learning final Mini-Project (Cornell University SP24). The overviews of the project and the GitHub repo are as follows:

## Project Overview

The planet of Hexagonia operates in base 6, and the digits they use are 0, 2, 3, 5, 7, 9. They hear of the MNIST dataset from Earth and want to make their own version.

To do so, they ask their residents to each write a random digit. Each resident does so. At night, the Hexagonian children decide to sabotage the entire process. They take each already written digit and write a different digit on top of it, as illustrated below:

![data_sample](/asset/img/data_sample.png "data_sample")

Now each example contains two digits instead of one, giving fifteen distinct possibilities (6 choose 2). The goal is to perform classification on this new dataset.

The correspondence between the digit pairs and the labels is as follows:

```console
{(0, 2): 0,
 (0, 3): 1,
 (0, 5): 2,
 (0, 7): 3,
 (0, 9): 4,
 (2, 3): 5,
 (2, 5): 6,
 (2, 7): 7,
 (2, 9): 8,
 (3, 5): 9,
 (3, 7): 10,
 (3, 9): 11,
 (5, 7): 12,
 (5, 9): 13,
 (7, 9): 14}
```

(Credit: Cornell University SP24 ECE4200-Fundamentals of Machine Learning, in-Class Kaggle Competition Webpage)

## Repo Overview

This MiniProject submission folder contains 5 machine learning implementation - Naive Bayes, Softmax Regression, Kernel SVM, Pure-CNN, CNN-ResNet. All of them can be found in the corresponding folder, and all the code were written in the jupyter notebooks.

To test the code, the dataset ***data.npz.zip*** has to be included and edit the dataset path in the code accordingly.

The corresponding testset predictions are also put in each of the folders.

Specifically, for pure-CNN and CNN-ResNet, they have their own training loss, loss curve, and model stucture.

The highest and finalized submission was from [CNN-ResNet model](https://github.com/666harrypeng/Handwritten-Digit-Pairs-Classification-by-Machine-Learning/tree/main/CNN-ResNet).

The final MiniProject report can be found under [report](https://github.com/666harrypeng/Handwritten-Digit-Pairs-Classification-by-Machine-Learning/tree/main/report).

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. You may view the full license text [here]().

### License Summary

- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made.
- **NonCommercial**: You may not use the material for commercial purposes.
- **NoDerivatives**: If you remix, transform, or build upon the material, you may not distribute the modified material.
