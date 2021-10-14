# MI_classification_paper


## Papers
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |
| EEGNet: a compact convolutional neural network for EEG-based brain–computer interfaces | Vernon J Lawhern, et al. | Jul-2018 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/aace8c/pdf) [Code](https://github.com/vlawhern/arl-eegmodels)| 68% (?) | BCIC_IV_2a | CNN |
| Interpretable and lightweight convolutional neural network for EEG decoding: Application to movement execution and imagination | Davide Borra, et al. | May-2020 | Neural Networks | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608020302021) Code| 91.2%     72.8% | HGD     BCIC_IV_2a | CNN |
| Motor Imagery EEG Decoding Method Based on a Discriminative Feature Learning Strategy | Lie Yang, et al. | Jan-2021 | IEEE Transactions on Neural Systems and Rehabilitation Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9327487) Code| 81.85%     85.46% | BCIC_IV_2a (10 fold CV)  BCIC_IV_2b | CNN |
HS-CNN: a CNN with hybrid convolution scale for EEG motor imagery classification | Guanhai Dai, et al. | Jan-2020 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/ab405f/pdf) Code| 91.57%     87.6% | BCIC_IV_2a (legt hand, right hand)  BCIC_IV_2b | CNN |
Motor imagery recognition with automatic EEG channel selection and deep learning | Han Zhang, et al. | Feb-2021 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/ab405f/pdf) Code| 87.2% | Private | CNN |

## Datasets
| Dataset | Subjects | Classes | Channels | Sampling rate | #Training per subject | #Test per subject |
| - | :-:| :-: | :-: | :-: | :-: | :-: | 
| BCIC_IV_2a| 9 | 4 (left hand, right hand, both feet, tongue) | 60EEG 3EOG | 250Hz | 288 | 288 |
| BCIC_IV_2b| 9 | 2 (left hand, right hand) | 3EEG 3EOG | 250Hz | 400 (?) | 320 (?) |
