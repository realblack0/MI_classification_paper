# MI_classification_paper


## Review papers
| Title | Author | Date | Publication | Link |
| - | - | - | - | :-:|
| Deep Learning Techniques for Classification of Electroencephalogram (EEG) Motor Imagery (MI) Signals: A Review | Hamdi Altaheri, et al. | Jul-2021 | Neural Computing and Applications | [Paper](https://www.researchgate.net/profile/Hamdi-Altaheri/publication/353327259_Deep_Learning_Techniques_for_Classification_of_Electroencephalogram_EEG_Motor_Imagery_MI_Signals_A_Review/links/60f4a5949541032c6d4da19e/Deep-Learning-Techniques-for-Classification-of-Electroencephalogram-EEG-Motor-Imagery-MI-Signals-A-Review.pdf) | 

## Papers
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |
| Improving the performance of multisubject motor imagery-based BCIs using twin cascaded softmax CNNs | Jing Luo, et al. | Mar-2021 | Journal of Neural Engineering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/abe357/pdf) Code | 78.88% 87.20% | BCIC_IV_2a (left, right hand) BCIC_IV_2b | Plug-and-play Twin-CNN |
| A novel motor imagery EEG decoding method based on feature separation | Lie Yang, et al. | Mar-2021 | Journal of Neural Engineering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/abe39b/pdf) Code | 83.97% (10 fold CV)  86.91% (10 fold CV) | BCIC_IV_2a BCIC_IV_2b | CNN |
| Motor Imagery EEG Decoding Method Based on a Discriminative Feature Learning Strategy | Lie Yang, et al. | Jan-2021 | IEEE Transactions on Neural Systems and Rehabilitation Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9327487) Code| 81.85% (10 fold CV)     85.46% | BCIC_IV_2a  BCIC_IV_2b | CNN |
| EEG-TCNet: An Accurate Temporal Convolutional Network for Embedded Motor-Imagery Network for Embedded Motor-Imagery Brain-Machine Interfaces | Thorir Mar Ingolfsson et al. | Oct-2020 | IEEE International Conference on Systems, Man, and Cybernetics | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9283028) [Code](https://github.com/iis-eth-zurich/eeg-tcnet) | 83.84% | BCIC_IV_2a | CNN |
| MMCNN: A multi-branch multi-scale convolutional neural network for motor imagery classification | Jia, Ziyu, et al. | Sep-2020 | ECML-PKDD 2020 | [Paper](https://www.researchgate.net/profile/Ziyu-Jia-2/publication/349564298_MMCNN_A_Multi-branch_Multi-scale_Convolutional_Neural_Network_for_Motor_Imagery_Classification/links/61a9e6dd50e22929cd41d4d9/MMCNN-A-Multi-branch-Multi-scale-Convolutional-Neural-Network-for-Motor-Imagery-Classification.pdf) [Code](https://github.com/jingwang2020/ECML-PKDD_MMCNN)| 81.4%(5CV) 84.4%(5CV) | BCIC_IV_2a (left hand, right hand) BCIC_IV_2b | CNN |
| Interpretable and lightweight convolutional neural network for EEG decoding: Application to movement execution and imagination | Davide Borra, et al. | May-2020 | Neural Networks | [Paper](https://www.sciencedirect.com/science/article/pii/S0893608020302021) Code| 91.2%     72.8% | HGD     BCIC_IV_2a | CNN |
| Classification of Motor Imagery Task by Using Novel Ensemble Pruning Approach | Muhammad Ammar Ali, et al. | Jan-2020 | IEEE Tansactions of Fuzzy Systems | [Paper](https://ieeexplore.ieee.org/iel7/91/4358784/08648160.pdf) Code | 0.7784(AUC) | BCIC_II_III | SVM |
| A Parallel Multiscale Filter Bank Convoluitonal Neural Networks for Motor Imagery EEG Classification | Hao Wu, et al. | Nov-2019 | froniers in Neuroscience | [Paper](https://www.frontiersin.org/articles/10.3389/fnins.2019.01275/full) Code| 75.8% 84.3% 94.4% | BCIC_IV_2a BCIC_IV_2b HGD | CNN |
| A Multi-Branch 3D Convolutional Neural Network for EEG-Based Motor Imagery Classification | Xinqiao Zhao, et al. | Oct-2019 | IEEE Transactions on Neural Systems and Rehabilitation Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8820089) Code| 64.4(Kappa)  75.015%(10 fold CV) | BCIC_IV_2a | 3D CNN |
| Deep Learning for EEG motor imagery classification based on multi-layer CNNs feature fusion | Syed Umar Amin, et al. | Jul-2019 | Future Generation Computer Systems | [Paper](https://www.sciencedirect.com/science/article/pii/S0167739X19306077) Code | 75.7% 95.4% | BCIC_IV_2a HGD | AE CNN|
| Learning Temporal Information for Brain-Computer Interface Using Convolutional Neural Networks | Siavash Sakhavi, et al. | Nov-2018 | IEEE Transactions on Neural Networks and Learning Systems | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8310961) Code | 74.46% | BCIC_IV_2a | CNN |
| EEGNet: a compact convolutional neural network for EEG-based brain–computer interfaces | Vernon J Lawhern, et al. | Jul-2018 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/aace8c/pdf) [Code](https://github.com/vlawhern/arl-eegmodels)| 68±a% | BCIC_IV_2a | CNN |
| Deep Learning With Convolutional Neural Networks for EEG Decoding and Visualization | Robin Tibor Schirrmeister, et al. | Aug-2017 | Human Brain Mapping | [Paper](https://onlinelibrary.wiley.com/doi/epdf/10.1002/hbm.23730) [Code](https://github.com/robintibor/braindecode/) | 73.7% 93.9% 89.9(Kappa) 72.2% | BCIC_IV_2a HGD BCIC_IV_2b MID | CNN |

## Failed to reproduce 
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |
| A Multibranch of Convolutional Neural Network Models for Electroencephalogram-Based Motor Imagery Classification | Ghadir Ali Altuwaijri and Ghulam Muhammad | Jan-2022 | Biosensors | [Paper](https://www.mdpi.com/2079-6374/12/1/22) Code| 82.01%     95.3% | BCIC_IV_2a  HGD | CNN |
| Motor imagery recognition with automatic EEG channel selection and deep learning | Han Zhang, et al. | Feb-2021 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/ab405f/pdf) Code| 87.2% | Private | CNN SE|
| A Multi-Scale Fusion Convolutional Neural Network Based on Attention Mechanism for the Visualization Analysis of EEG Signals Decoding | Donglin Li, et al. | Dec-2020 | IEEE Transactions on Neural Systems and Rehabilitation Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9256357) Code | 79.90% | BCIC_IV_2a | CNN |
| HS-CNN: a CNN with hybrid convolution scale for EEG motor imagery classification | Guanhai Dai, et al. | Jan-2020 | Journal of Neural Enginnering | [Paper](https://iopscience.iop.org/article/10.1088/1741-2552/ab405f/pdf) Code| 91.57%     87.6% | BCIC_IV_2a (left hand, right hand)  BCIC_IV_2b | CNN |
| Densely Feature Fusion Based on Convolutional Neural Networks for Motor Imagery EEG Classification |Donglin li, et al. | Sep-2019 | IEEE Access | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8840855) Code | 79.90% (CV) | BCIC_IV_2a | CNN |

## Papers to read 
| Title | Author | Date | Publication | Link | Accuracy | Dataset | Model |
| - | - | - | - | :-:| :-: | :-: | :-: |
| SincNet-Based Hybrid Neural Network for Motor Imagery EEG Decoding | Chang Liu, et al. | March-2022 | IEEE Transactions on Neural Systems and Rehabilitation Engineering | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9726162) Code | 74.26% 83.49% | BCIC_IV_2a BCIC_IV_2b | CNN |
| Riemannian embedding banks for common spatial patterns with EEG-based SPD neural networks | Yoon-Je Suh and Byung Hyung Kim | 2021 | AAAI | [Paper](https://www.aaai.org/AAAI21Papers/AAAI-4766.SuhY.pdf) Code | 52.4(mAP) | BCIC_IV_2a | SPDNet |
| Learning EEG topographical representation for classification via convolutional neural network | Meiyan Xu, et al. | Apr-2020 | Pattern Recognition | [Paper](https://www.sciencedirect.com/science/article/pii/S003132032030193X) Code | 84.57% | BCIC_IV_2a | CNN |
| A Novel MI-EEG Imaging With the Location Information of Electrodes | MING-AI LI, et al. | Dec-2019 | IEEE Access | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8944067) Code | 88.87% | BCIC_IV_2a | CNN |
| Multilevel Weighted Feature Fusion Using Convolutional Neural Networks for EEG Motor Imagery Classification | Syed Umar Amin, et al. | Jan-2019 | IEEE Access | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8629079) Code | 74.5% | BCIC_IV_2a | CNN |
| Wavelet Transform Time-Frequency Image and Convolutional Network-Based Motor Imagery EEG Classification | Baoguo Xu, et al. | Dec-2018 | IEEE Access | [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8585027) Code | 92.75% 85.59% | BCIC_III_2 BCIC_IV_2a | CNN |
| Classification of multiple motor imagery using deep convolutional neural networks and spatial filters | Brenda E. Olibas-Padilla, et al. | Nov-2018 | Applied Soft Computing Journal | [Paper](https://www.sciencedirect.com/science/article/pii/S156849461830663X) Code | 78.41% | BCIC_IV_2a | CNN |
| Exploring spatial-frequency-sequential relationships for motor imagery classification with recurrent neural network | Tian-jian Luo, et al. | Sep-2018 | BMC Bioinformatics | [Paper](https://bmcbioinformatics.biomedcentral.com/track/pdf/10.1186/s12859-018-2365-1.pdf) Code | 73.56% 82.75% | BCIC_IV_2a BCIC_IV_2b | RNN |


## Public Datasets
| Dataset | Subjects | Classes | Channels | Sampling rate | #Training per subject | #Test per subject |
| - | :-:| :-: | :-: | :-: | :-: | :-: | 
| BCIC_IV_2a| 9 | 4 (rihgt hand, left hand, both feet, tongue) | 22EEG 3EOG | 250Hz | 288 | 288 |
| BCIC_IV_2b| 9 | 2 (rihgt hand, left hand) | 3EEG 3EOG | 250Hz | 400±a | 320±a |
| HGD(High-Gamma Dataset) | 14 | 4 (right hand, left hand, rest, feet) | 128 ME-EEG | 500Hz | ~880 | ~160 |
