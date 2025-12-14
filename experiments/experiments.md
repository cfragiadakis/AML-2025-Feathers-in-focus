experiments:



1\) initial best model:

Image size: 256

Optimizer: Adam

learning\_rate = 1e-4

Batch size = 64

alpha = 0.1

Dropout = no

Sampler = false

scale = 30

train-test: 80/20



2\) Increased image size: 384

Train | loss: 2.1445, acc: 55.22%

Val   | loss: 2.9964, acc: 32.44%

best model (val\_acc=0.3244) (test accuracy: 28.1%)



3\) Increased image size, alpha = 0.2

 Train | loss: 1.0784, acc: 0.8589

 Val   | loss: 2.6796, acc: 0.3931

best model (val\_acc=0.3931) (test accuracy: 32.4%)



4. Increased image size, alpha = 0.3  "1.2architecture\_resnet18\_attributes.pt"

Train | loss: 0.8509, acc: 0.9137

 Val   | loss: 2.6939, acc: 0.3995

best model (val\_acc=0.405)



**5) Increased image size, alpha = 0.4**  **"1.3architecture\_resnet18\_attributes.pt"**

 Train | loss: 1.1114, acc: 0.8627

 Val   | loss: 2.6781, acc: 0.3995

best model (val\_acc=0.3995) **(test accuracy: 34.2%)**



6. Increased image size, alpha = 0.3, ArcFace instead of Standard Cosine Classifier

Train | loss: 1.1406, acc: 0.8551

Val   | loss: 2.7129, acc: 0.3855
best model (val\_acc=0.3854)  (test accuracy: 32.3%)



7\) Increased image size, alpha = 0.5

Train | loss: 1.9221, acc: 0.6156

 Val   | loss: 2.8459, acc: 0.3321

best model (val\_acc=0.33)



8\) Increased image size \& augmentation, alpha = 0.4

 Train | loss: 1.2135, acc: 0.8108

 Val   | loss: 2.6531, acc: 0.3931

best model (val\_acc=0.39) (test accuracy: 33.6%)



9\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3

 Train | loss: 2.5040, acc: 0.4194

 Val   | loss: 2.7969, acc: 0.3321

best model (val\_acc=0.3321) (test accuracy: 25.0%)



10\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10 **"1.4architecture\_resnet18\_attributes.pt"**

Train | loss: 1.5717, **acc: 0.6802**

 Val   | loss: 2.4325, **acc: 0.4351**

best model (val\_acc=0.4351) (test accuracy 34.5%)



11\) Increased image size \& augmentation, alpha = 0.4, train/val 90-10 \& resnet 1/4params

 Train | loss: 2.6233, acc: 0.5188

 Val   | loss: 2.9661, acc: 0.3944

best model (val\_acc=0.3944) (test accuracy: 30.0%)



12\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.5, train/val 90-10

 Train | loss: 1.9544, acc: 0.5584

 Val   | loss: 2.4901, acc: 0.4122

best model (val\_acc=0.4122) (test accuracy: 31.5%)



13\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.5, train/val 80-20, sampler=True

 Train | loss: 2.3601, acc: 0.4392

 Val   | loss: 2.6645, acc: 0.3639

best model (val\_acc=0.3639) (test accuracy: 28.2%)



14\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.4, train/val 80-20, sampler=True

Train | loss: 2.6984, acc: 0.3618

Val   | loss: 3.0080, acc: 0.3041

best model (val\_acc=0.3041)



15. Increased image size \& augmentation, alpha = 0.5, use dropout=0.4, train/val 80-20, sampler=True

 Train | loss: 2.9786, acc: 0.2939

 Val   | loss: 3.0259, acc: 0.2684

best model (val\_acc=0.2684)



16\) Increased image size \& augmentation, alpha = 0.5, use dropout=0.4, train/val 80-20

 Train | loss: 2.6871, acc: 0.3586

 Val   | loss: 2.9058, acc: 0.3130

best model (val\_acc=0.3130)



17\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10 sampler=True

Train | loss: 1.8026, acc: 0.6136

 Val   | loss: 2.5448, acc: 0.4020

best model (val\_acc=0.4020)  (test accuracy: 32.2%)



18\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 80-20 sampler=True

Train | loss: 1.9167, acc: 0.5761

 Val   | loss: 2.5184, acc: 0.3957

best model (val\_acc=0.3957) (test accuracy: 30.4%)



19\) Increased image size \& augmentation, alpha = 0.5, use dropout=0.3, train/val 90-10

Train | loss: 1.9332, acc: 0.6361

 Val   | loss: 2.8184, acc: 0.381

best model (val\_acc=0.381) (test accuracy: 31.4%)





20\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10 sampler=True **"1.11architecture\_resnet18\_attributes.pt"**

 Train | loss: 1.9184, acc: 0.5768

 Val   | loss: 2.4587, acc: 0.4427

best model (val\_acc=0.4427) (test accuracy: 33.6%)





21\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 80-20 sampler=True "1.12architecture\_resnet18\_attributes.pt"

&nbsp;Train | loss: 2.1019, acc: 0.5182

&nbsp;Val   | loss: 2.6478, acc: 0.3715

&nbsp;best model (val\_acc=0.3715) (test accuracy: 28.7%)



22\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 80-20 sampler=True batch\_size=128



&nbsp;Train | loss: 1.7117, acc: 0.6627

&nbsp;Val   | loss: 2.7296, acc: 0.3715

&nbsp;best model (val\_acc=0.3715) (test accuracy: 31.1%)



23\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10 batch\_size=128

&nbsp;Train | loss: 2.3340, acc: 0.4792

&nbsp;Val   | loss: 2.7401, acc: 0.3588

best model (val\_acc=0.3588) (test accuracy: 28.7%)



24\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10 batch\_size=128, sampler=True

Train | loss: 2.5525, acc: 0.3923

 Val   | loss: 2.8656, acc: 0.3410

best model (val\_acc=0.3410)





**FINAL CHOSEN**



1\) Increased image size \& augmentation, alpha = 0.4, use dropout=0.3, train/val 90-10, batch\_size=128, scale=15



1\) Train | loss: 1.9743, acc: 0.5347

&nbsp;Val   | loss: 2.3823, acc: 0.4071

&nbsp;best model (val\_acc=0.4071) (test accuracy: 33.6%)



2\) Train | loss: 1.7640, acc: 0.5904

&nbsp;Val   | loss: 2.7193, acc: 0.3740

best model (val\_acc=0.3740) (test accuracy: 28.6%)



3\) Train | loss: 2.0555, acc: 0.5205

&nbsp;Val   | loss: 2.6189, acc: 0.3715

best model (val\_acc=0.3715) (test accuracy: 30.6%)



4\) Train | loss: 1.6830, acc: 0.6040

&nbsp;Val   | loss: 2.4452, acc: 0.4097

best model (val\_acc=0.4097) (test accuracy: 35.7%)



5\)  Train | loss: 1.6362, acc: 0.6128

&nbsp;Val   | loss: 2.3986, acc: 0.4326

best model (val\_acc=0.4326)





| Run | Train Acc (%) | Val Acc (%) | Test Acc (%) |

| --: | ------------: | ----------: | -----------: |

|   1 |         53.47 |       40.71 |        33.60 |

|   2 |         59.04 |       37.40 |        28.60 |

|   3 |         52.05 |       37.15 |        30.60 |

|   4 |         60.40 |       40.97 |        35.70 |

|   5 |         61.28 |       43.26 |        34.20 |



&nbsp;

* Mean Train Accuracy: 57.25%
* Mean Validation Accuracy: 39.90%
* Mean Test Accuracy: 32.54%
