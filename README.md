## TSAI Assignment 5
This repository has a CNN for the MNIST digit classification task. The model uses a series of convolutional blocks, batch normalization, max pooling, and global average pooling to achieve high accuracy on the dataset.

Model Architecture
----------------------------------------------------------------
        Layer (type)               Output Shape         Param #
================================================================


            Conv2d-1           [-1, 16, 26, 26]             160
       BatchNorm2d-2           [-1, 16, 26, 26]              32
              ReLU-3           [-1, 16, 26, 26]               0
            Conv2d-4           [-1, 32, 24, 24]           4,640
       BatchNorm2d-5           [-1, 32, 24, 24]              64
              ReLU-6           [-1, 32, 24, 24]               0
         MaxPool2d-7           [-1, 32, 12, 12]               0
            Conv2d-8           [-1, 32, 12, 12]           1,056
       BatchNorm2d-9           [-1, 32, 12, 12]              64
             ReLU-10           [-1, 32, 12, 12]               0
           Conv2d-11           [-1, 32, 10, 10]           9,248
      BatchNorm2d-12           [-1, 32, 10, 10]              64
             ReLU-13           [-1, 32, 10, 10]               0
           Conv2d-14           [-1, 10, 10, 10]             330
      BatchNorm2d-15           [-1, 10, 10, 10]              20
             ReLU-16           [-1, 10, 10, 10]               0
AdaptiveAvgPool2d-17             [-1, 10, 1, 1]               0
================================================================
Total params: 15,678
Trainable params: 15,678
Train Accuracy: 99.76%
Test Accuracy: 99.40%

#### LOGS
EPOCH: 0
  0%|                                                   | 0/938 [00:00<?, ?it/s]
Loss=0.2535237967967987 Batch_id=937 Accuracy=89.48: 100%|█| 938/938 [00:40<00:0

Test set: Average loss: 0.3875, Accuracy: 9580/10000 (95.80%)

EPOCH: 1
Loss=0.20677337050437927 Batch_id=937 Accuracy=96.60: 100%|█| 938/938 [00:40<00:

Test set: Average loss: 0.1283, Accuracy: 9773/10000 (97.73%)

EPOCH: 2
Loss=0.06631440669298172 Batch_id=937 Accuracy=97.60: 100%|█| 938/938 [00:40<00:

Test set: Average loss: 0.0883, Accuracy: 9785/10000 (97.85%)

EPOCH: 3
Loss=0.028334863483905792 Batch_id=937 Accuracy=98.02: 100%|█| 938/938 [00:42<00

Test set: Average loss: 0.0617, Accuracy: 9839/10000 (98.39%)

EPOCH: 4
Loss=0.22412708401679993 Batch_id=937 Accuracy=98.23: 100%|█| 938/938 [00:43<00:

Test set: Average loss: 0.0779, Accuracy: 9759/10000 (97.59%)

EPOCH: 5
Loss=0.030738109722733498 Batch_id=937 Accuracy=98.43: 100%|█| 938/938 [00:44<00

Test set: Average loss: 0.0398, Accuracy: 9883/10000 (98.83%)

EPOCH: 6
Loss=0.019193187355995178 Batch_id=937 Accuracy=98.62: 100%|█| 938/938 [00:43<00

Test set: Average loss: 0.0460, Accuracy: 9858/10000 (98.58%)

EPOCH: 7
Loss=0.029831532388925552 Batch_id=937 Accuracy=98.73: 100%|█| 938/938 [00:43<00

Test set: Average loss: 0.0374, Accuracy: 9901/10000 (99.01%)

EPOCH: 8
Loss=0.018760716542601585 Batch_id=937 Accuracy=98.97: 100%|█| 938/938 [00:42<00

Test set: Average loss: 0.0358, Accuracy: 9884/10000 (98.84%)

EPOCH: 9
Loss=0.27646204829216003 Batch_id=937 Accuracy=99.10: 100%|█| 938/938 [00:43<00:

Test set: Average loss: 0.0312, Accuracy: 9907/10000 (99.07%)

EPOCH: 10
Loss=0.006538400426506996 Batch_id=937 Accuracy=99.23: 100%|█| 938/938 [00:43<00

Test set: Average loss: 0.0256, Accuracy: 9917/10000 (99.17%)

EPOCH: 11
Loss=0.0067934030666947365 Batch_id=937 Accuracy=99.48: 100%|█| 938/938 [00:43<0

Test set: Average loss: 0.0232, Accuracy: 9923/10000 (99.23%)

EPOCH: 12
Loss=0.02056497521698475 Batch_id=937 Accuracy=99.57: 100%|█| 938/938 [00:42<00:

Test set: Average loss: 0.0217, Accuracy: 9930/10000 (99.30%)

EPOCH: 13
Loss=0.008817212656140327 Batch_id=937 Accuracy=99.72: 100%|█| 938/938 [00:43<00

Test set: Average loss: 0.0214, Accuracy: 9934/10000 (99.34%)

EPOCH: 14
Loss=0.010001949965953827 Batch_id=937 Accuracy=99.76: 100%|█| 938/938 [00:43<00

Test set: Average loss: 0.0206, Accuracy: 9940/10000 (99.40%)

