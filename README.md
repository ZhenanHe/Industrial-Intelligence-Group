# Industrial Intelligence Group

## I. About Us

**TODO**

## II. Topics

### A. Open Set Signal Classification (OSSC)

Most data-driven signal diagnosis methods are based on closed set assumption that class sets of training and test data are consistent. However, in industrial scenarios, during the running process of the device, the operating environment and condition may change over time, continuing generating data belong to unknown classes with new characteristics and distribution. The unknown classes usually reflect new modes or faults of the device need to be captured. They are unavailable in training phase, contradicting the closed set assumption. Existing methods are inappropriate to this type of open set classification requiring to classify known classes and recognize unknown classes. To address this challenging problem, this paper proposes a generic open set signal classification method. First, we apply Fourier transform to convert the sensor signals from time domain to frequency domain, then data in the time and frequency domains are fused. Next, a variational encoder-classifier network is proposed to classify known classes and learn the distribution of feature space to extract robust latent features. Finally, based on extreme value theory and entropy, a pair of discriminators determine whether samples belong to unknown or not. The experimental results on two vibration signal datasets from bearings and nuclear reactor demonstrate the effectiveness and superiority of our proposed open set signal classification method, especially in practical applications.

![openset_problem.jpg](https://s2.loli.net/2022/06/21/HRQKEFeMiZwAVrD.png)

In the open set scenario, based on the assumption that some classes are unknown in the training set, for each class the algorithm determines a finite region associated with it. If a sample lies in a region of the known class, it is identified to that class. On the other hand, if it lies in a space that is not associated with any known class, it is rejected as an unknown class.

#### (1) Code

https://github.com/ZhenanHe/Open-Set-Signal-Classification-OSSC

#### (2) Publication

[paper](https://ieeexplore.ieee.org/document/9763052/):

> **J. Chen, G. Wang, J. Lv, Z. He, T. Yang and C. Tang, "Open Set Classification for Signal Diagnosis of Machinery Sensor in Industrial Environment," in IEEE Transactions on Industrial Informatics, doi: 10.1109/TII.2022.3169459.**
