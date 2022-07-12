# Industrial Intelligence Group

Todo: 折叠

## I. About Us

We are a lab for international academic circle. We focus on the application of intelligent data processing and deep learning algorithms in industry. Our research interests mainly include: theoretical research on neural networks, natural language processing, graphic images, data science and industrial transformation. The lab has many years of research foundation and rich scientific research accumulation in many cutting-edge major hot scientific problems research, and has won many provincial and ministerial level science and technology awards.

Todo: teacher's info

## II. Topics

### Evolutionary Computation 

#### MOEA-with-robustness-enhancement (MOEA-RE)

Uncertainty is an important feature abstracted from real-world applications. Multiobjective optimization problems (MOPs) with uncertainty can always be characterized as robust MOPs (RMOPs). Over recent years, multiobjective optimization evolutionary algorithms (EAs) have demonstrated the success in solving MOPs. However, most of them do not consider disturbance in the design. In order to handling the uncertainty in the optimization problem, we first give a thorough analysis of three important issues on robust optimization. Then, a novel EA called multiobjective optimization EA with robustness enhancement is developed, where the seamless integration of robustness and optimality is achieved by a proposed novel archive updating mechanism applied on the evolutionary process as well as the new robust optimal front building strategy designed to construct the final robust optimal front. Furthermore, the new designed archive updating mechanism makes the robust optimization process free of the enormous computational workload induced from sampling. The experimental results on a set of benchmark functions show the superiority of the proposed design in terms of both solutions' quality under the disturbance and computational efficiency in solving RMOPs.

#### (1) Code

https://github.com/ZhenanHe/MOEA-with-robustness-enhancement-MOEA-RE

#### (2) Publication

[paper](https://ieeexplore.ieee.org/document/9763052/):

> **Z. He, G. G. Yen, and J. Lv, "Evolutionary Multiobjective Optimization With Robustness Enhancement," in IEEE Transactions on Evolutionary Computation, vol. 24, no. 3, pp. 494-507, June 2020, doi: 10.1109/TEVC.2019.2933444.**

### Deep Learning

#### Open Set Signal Classification (OSSC)

Most data-driven signal diagnosis methods are based on closed set assumption that class sets of training and test data are consistent. However, in industrial scenarios, during the running process of the device, the operating environment and condition may change over time, continuing generating data belong to unknown classes with new characteristics and distribution. The unknown classes usually reflect new modes or faults of the device need to be captured. They are unavailable in training phase, contradicting the closed set assumption. Existing methods are inappropriate to this type of open set classification requiring to classify known classes and recognize unknown classes. To address this challenging problem, this paper proposes a generic open set signal classification method. First, we apply Fourier transform to convert the sensor signals from time domain to frequency domain, then data in the time and frequency domains are fused. Next, a variational encoder-classifier network is proposed to classify known classes and learn the distribution of feature space to extract robust latent features. Finally, based on extreme value theory and entropy, a pair of discriminators determine whether samples belong to unknown or not. The experimental results on two vibration signal datasets from bearings and nuclear reactor demonstrate the effectiveness and superiority of our proposed open set signal classification method, especially in practical applications.

![openset_problem.jpg](https://s2.loli.net/2022/06/21/HRQKEFeMiZwAVrD.png)

In the open set scenario, based on the assumption that some classes are unknown in the training set, for each class the algorithm determines a finite region associated with it. If a sample lies in a region of the known class, it is identified to that class. On the other hand, if it lies in a space that is not associated with any known class, it is rejected as an unknown class.

#### (1) Code

https://github.com/ZhenanHe/Open-Set-Signal-Classification-OSSC

#### (2) Publication

[paper](https://ieeexplore.ieee.org/document/9763052/):

> **J. Chen, G. Wang, J. Lv, Z. He, T. Yang and C. Tang, "Open Set Classification for Signal Diagnosis of Machinery Sensor in Industrial Environment," in IEEE Transactions on Industrial Informatics, doi: 10.1109/TII.2022.3169459.**
