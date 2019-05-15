# NATTACK: A STRONG AND UNIVERSAL GAUSSIAN BLACK-BOX ADVERSARIAL ATTACK


Data and model can be found here: [data and model](https://1drv.ms/f/s!AlXveXe2-CcAhc9mY5XOfDMJjZIiVQ).
 

Please download the data&&model and unzip them to './cifar-data' and './all_models'
 
 
Below is Table 1 from our paper, where we show the robustness of each accepted defense to the adversarial examples we can construct:



| Defense | Dataset | Distance | Success rate |
|---|---|---|---|
| ADV-TRAIN [Madry et al. (2018)](https://arxiv.org/abs/1706.06083) | CIFAR | 0.031 (linf) | 47.9% |
| ADV-BNN [Liu et al. (2019)](https://arxiv.org/abs/1810.01279) | CIFAR | 0.035 (linf) | 75.3% |
| THERM-ADV [Buckman et al. (2018)](https://openreview.net/forum?id=S18Su--CW)[Madry et al. (2018)](https://arxiv.org/abs/1706.06083) | CIFAR | 0.031 (linf) | 91.2% |
| CAS-ADV [Na et al. (2018)](https://arxiv.org/abs/1708.02582) | CIFAR | 0.031 (linf) | 97.7% |
| ADV-GAN [Wang & Yu (2019)](https://openreview.net/forum?id=S1lIMn05F7) | CIFAR | 0.015 (linf) | 98.3% |
| LID [Ma et al. (2018)](https://arxiv.org/abs/1801.02613) | CIFAR | 0.031 (linf) | 100.0% |
| THERM [Buckman et al. (2018)](https://openreview.net/forum?id=S18Su--CW) | CIFAR | 0.031 (linf) | 100.0% |
| SAP [Dhillon et al. (2018)](https://arxiv.org/abs/1803.01442) | CIFAR | 0.031 (linf) | 100.0% |
| RSE [Liu et al. (2018)](https://arxiv.org/abs/1712.00673) | CIFAR | 0.031 (linf) | 100.0% |
| GUIDED DENOISER [(Liao et al., 2018)](https://arxiv.org/abs/1711.00117) | ImageNet | 0.031 (linf) | 95.5% |
| RANDOMIZATION [Xie et al. (2018)](https://arxiv.org/abs/1711.01991) | ImageNet | 0.031 (linf) | 96.5% |
| INPUT-TRANS [Guo et al. (2018)](https://arxiv.org/abs/1711.00117) | ImageNet | 0.005 (l2) | 100.0% |
| PIXEL DEFLECTION [Prakash et al. (2018)](https://arxiv.org/abs/1801.08926) | ImageNet | 0.031 (linf) | 100.0% |




## Paper

Paper available in [Arxiv](https://arxiv.org/abs/1905.00441). If you feel it helpful, please cite our work.

`@inproceedings{
  Li2019NATTACKLT,
  title={NATTACK: Learning the Distributions of Adversarial Examples for an Improved Black-Box Attack on Deep Neural Networks},
  author={Yandong Li and Lijun Li and Liqiang Wang and Tong Zhang and Boqing Gong},
  year={2019}
}`

## Source code

This repository contains our implemenation of the black-box attack algorithm described in our paper, six defense methods (SAP, LID, RANDOMIZATION, INPUT-TRANS, THERM, and THERM-DAV) borrowed from the code of Anish et al. (2018), two defended models (GUIDED DENOISER and PIXEL DEFLECTION) based on the code of Athalye & Carlini, (2018), and two defended models (RSE and CAS-ADV) from the original papers.

## Note

Please note the paper is still under double-blind review.
