# fashion_mnist


We build and compare several CNN architectures by training and testing them on Fashion-MNIST dataset for clothing objects classification. 

------------------------------------------------------------------------

| Model  | Train Set Acc. | Test Set Acc. | Run Time/Epoch |
| ------------- | ------------- | ------------- | ------------- |
| Shallow Net  | 97.6% | 92.5% | 40s |
| Shallow Net (aug) | 94.9% | 92.6% | 60s |
| LeNet5 | 96.3% | 91.1% | 30s |
| Slow Net | 93.9% | 93% | 570s |

--------------------------------------------------------------------

1° Homemade Shallow Net: A very simple CNN with a bit of regularization. Gives the best accuracy score on the train set.

1.5° Shallow Net with augmentation: Gives less overfit. Maybe not the best augmentation parameter setting. But, with more experience, I'd probably get the better feeling for the augmentation parameter tuning, and get better results. 

2° LeNet5: Quick simple (and famous) architecture. Gives the lowest test score, but it's fastest to train.

3° Slow Net: A bit bigger network, gives the highest test score, no overfit, but it's very slow to train (on CPU).

-------------------------------------------------------------------

For more detailed analyses, please refer to the individual notebook files. I also tried to write a demo program for object detection/classification, but I couldn't complete it. However, I left a blueprint, which hopefully I'll be able to fill in, once I gain enough practical experience. 
