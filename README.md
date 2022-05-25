## Awesome resources on Hyperspectral Image Unmixing
A list of hyperspectral image unmixing resources collected by Xiuheng Wang and Min Zhao. **For more details, please refer to our paper: Integration of Physics-Based and Data-Driven Models for Hyperspectral Image Unmixing.** [[Paper](https://arxiv.org/)] [[Bibtex](https://bibbase.org/network/publication/chen-zhao-wang-richard-rahardja-integrationofphysicsbasedanddatadrivenmodelsforhyperspectralimageunmixing-2022)]
**If you find that important resources are not included, please feel free to contact us.**

## Contents

- [Physics-based mixture model](#model)
  - [Survey](#survey)
  - [Examples](#examples)
- [A general formulation of the unmixing problem](#problem)
- [Joint physics-based and data-driven unmixing methods with recent machine learning methods](#deeplearning)
  - [Integrating of physics-based models in deep neural network design](#network)
  - [Deep neural network design inspired by the physical model-based iterative optimization](#iterative)
  - [Integrating loss learnt from data into physics-based inverse problems](#loss)
- [Databases](#data)
- [Toolbox](#toolbox)

<a name="model" />

## Physics-based mixture model

<a name="survey" />

### Survey
1. **Nonlinear unmixing of hyperspectral images: Models and algorithms.** SPM 2013, *N. Dobigeon et al*.
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6678284)] 
2. **A review of nonlinear hyperspectral unmixing methods.** JSTARS 2014, *R. Heylen et al*.
[[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=6816071)] 


<a name="examples" />

### Examples
1. 


<a name="problem" />

## A general formulation of the unmixing problem

<a name="deeplearning" />

## Joint physics-based and data-driven unmixing methods with recent machine learning methods

<a name="network" />

### Integrating of physics-based models in deep neural network design.
1. **EndNet: Sparse autoencoder network for endmember extraction and hyperspectral unmixing.** TGRS 2018, *S. Ozkan et al*.
[[Paper]()] [[Code](https://github.com/savasozkan/endnet)]
2. **uDAS: An untied denoising autoencoder with sparsity for spectral unmixing.** TGRS 2018, *Y. Qu et al*.
[[Paper]()] [[Code](https://github.com/aicip/uDAS)]
3. **DAEN: Deep autoencoder networks for hyperspectral unmixing.** TGRS 2019, *Y. Su et al*.
[[Paper]()] [[Code]()]
4. **Hyperspectral unmixing using a neural network autoencoder.** IEEE Access 2018, *B. Palsson et al*.
[[Paper]()] [[Code](https://github.com/burknipalsson/hu_autoencoders/blob/main/Method_DAEU.ipynb)]
5. **Convolutional autoencoder for spectral–spatial hyperspectral unmixing.** TGRS 2020, *B. Palsson et al*.
[[Paper]()] [[Code](https://github.com/burknipalsson/hu_autoencoders/blob/main/Method_CNNAEU.ipynb)]
6. **Hyperspectral unmixing using deep convolutional autoencoders in a supervised scenario.** JSTARS 2020, *F. Khajehrayeni et al*.
[[Paper]()] [[Code]()]
7. **Nonlinear unmixing of hyperspectral data via deep autoencoder network.** GRSL 2019, *M. Wang et al*.
[[Paper]()] [[Code](https://github.com/zhaomin0101/NAE)]
8. **LSTM-DNN based autoencoder network for nonlinear hyperspectral image unmixing.** JSTSP 2021, *M. Zhao et al*.
[[Paper]()] [[Code]()]
9. **Hyperspectral unmixing for additive nonlinear models with a 3-D-CNN autoencoder network.** TGRS 2022, *M. Zhao et al*.
[[Paper]()] [[Code](https://github.com/zhaomin0101/3DCNN-var)]
10. **Deep autoencoders with multitask learning for bilinear hyperspectral unmixing.** TGRS 2020, *Y. Su et al*.
[[Paper]()] [[Code]()]
11. **Unsupervised hyperspectral unmixing via nonlinear autoencoders.** TGRS 2021, *K. T. Shahid et al*.
[[Paper]()] [[Code]()]
12. **TANet: An unsupervised two-stream autoencoder network for hyperspectral unmixing.** TGRS 2021, *Q. Jin et al*.
[[Paper]()] [[Code](https://github.com/meixiaoguang/TANet)]
13. **Probabilistic generative model for hyperspectral unmixing accounting for endmember variability.**  TGRS 2022, *S. Shi et al*.
[[Paper]()] [[Code](https://github.com/shuaikaishi/PGMSU)]
14. **Deep generative endmember modeling: An application to unsupervised spectral unmixing.** TCI 2019, *R. Borsoi et al*.
[[Paper]()] [[Code](https://github.com/ricardoborsoi/Unmixing_with_Deep_Generative_Models)]
15. **Deep half-siamese networks for hyperspectral unmixing.** GRSL 2020, *Z. Han et al*.
[[Paper]()] [[Code]()]
16. **Dual branch autoencoder network for spectral-spatial hyperspectral unmixing.** GRSL 2021, *Z. Hua et al*.
[[Paper]()] [[Code]()]
17. **Cycu-net: Cycle-consistency unmixing network by learning cascaded autoencoders.** TGRS 2021, *L. Gao et al*.
[[Paper]()] [[Code](https://github.com/hanzhu97702/IEEE_TGRS_CyCU-Net)]
18. **UnDIP: Hyperspectral unmixing using deep image prior.** TGRS 2021, *B. Rasti et al*. 
[[Paper]()] [[Code](https://github.com/BehnoodRasti/UnDIP)]

<a name="iterative" />

### Deep neural network design inspired by the physical model-based iterative optimization
1. [*Our work*] **A plug-and-play priors framework for hyperspectral unmixing.** TGRS 2021, *M. Zhao et al*.
[[Paper]()] [[Code](https://github.com/xiuheng-wang/Plug_and_Play_HSI_unmixing)]
2. **Hyperspectral unmixing via nonnegative matrix factorization with handcrafted and learned priors.** GRSL 2021, *M. Zhao et al*.
[[Paper]()] [[Code]()]
3. **Hyperspectral nonlinear unmixing by using plug-and-play prior for abundance maps** RS 2020, *Z. Wang et al*.
[[Paper]()] [[Code]()]
4. **An ADMM based network for hyperspectral unmixing tasks.** ICASSP 2021, *C. Zhou et al*.
[[Paper]()] [[Code]()]
5. **SNMF-Net: Learning a deep alternating neural network for hyperspectral unmixing.** TGRS 2021, *F. Xiong et al*.
[[Paper]()] [[Code](http://www.xiongfuli.com/cv/code/SNMF.zip)]


<a name="loss" />

### Integrating loss learnt from data into physics-based inverse problems
1. **JMnet: Joint metric neural network for hyperspectral unmixing.** TGRS 2021, *A. Min et al*.
[[Paper]()] [[Code]()]
2. **Adversarial autoencoder network for hyperspectral unmixing.** TNNLS 2021, *Q. Jin et al*.
[[Paper]()] [[Code](https://github.com/meixiaoguang/AAENet)]