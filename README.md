# Fair Learning with Private Demographic Data

This repository includes the code  for our [ICML 2020 paper Fair Learning with Private Demographic Data](https://arxiv.org/pdf/2002.11651.pdf) by Hussein Mozannar, Mesrob I. Ohannessian and Nathan Srebro.



Sensitive attributes such as race are rarely available to learners in real world settings as their
collection is often restricted by laws and regulations. We give a scheme that allows individuals
to release their sensitive information privately while still allowing any downstream entity to
learn non-discriminatory predictors. We show how to adapt non-discriminatory learners to work
with privatized protected attributes giving theoretical guarantees on performance.

This repository contains a jupyter notebook to reproduce Figure 1 in our paper, the task is to learn a non-discriminatory predictor on the adult dataset.




## Requirements
The notebook can be easily run on Google Colab.


## Citation

```
@inproceedings{mozannar2020fair,
  title={Fair learning with private demographic data},
  author={Mozannar, Hussein and Ohannessian, Mesrob and Srebro, Nathan},
  booktitle={International Conference on Machine Learning},
  pages={7066--7075},
  year={2020},
  organization={PMLR}
}
```
