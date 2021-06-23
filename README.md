# Sparse Bayesian Kernel-based Mapping (SBKM)
This repo provides code for our paper "Autonomous Navigation in Unknown Environments with Sparse Bayesian Kernel-based Occupancy Mapping".
Please check out our project website for more details: https://thaipduong.github.io/sbkm.

## Dependencies
Our code is tested with Ubuntu 18.04 and Python 3.7. It depends on the following Python packages: numpy 1.17.4, scipy 1.6.2, pandas 1.1.0, rtree 0.9.4, matplotlib 3.1.0, scikit-learn 0.20.4. Newer versions of these packages might work but have not been tested. 
## Demo
Run ```python sbkm_demo.py``` for a demo with Intel Research Lab dataset

<img src="figs/demo.gif" width="900">

Run ```python collision_checking_demo.py``` for a demo of our collision checking methods for line segments (top) and curves (bottom).
<p float="left">
<img src="figs/check_lines.png" width="900">
<img src="figs/check_curves.png" width="900">
</p>


## Citation
If you find our papers/code useful for your research, please cite our work as follows.

1. T. Duong, M. Yip, N. Atanasov. [Autonomous Navigation in Unknown Environments with Sparse __*Bayesian*__ Kernel-based Occupancy Mapping](https://thaipduong.github.io/sbkm/). In Submission. 2020

 ```bibtex
@misc{duong2020autonomousbayesian,
title={Autonomous Navigation in Unknown Environments with Sparse Bayesian Kernel-based Occupancy Mapping},
author={Duong, Thai and Yip, Michael and Atanasov, Nikolay},
url = {https://thaipduong.github.io/sbkm},
pdf = {https://arxiv.org/pdf/2009.07207.pdf}
eprint={2009.07207},
archivePrefix={arXiv},
primaryClass={cs.RO}
year={2020}
}
```
2.  T. Duong, N. Das, M. Yip, N. Atanasov. [Autonomous Navigation in Unknown Environments using Sparse Kernel-based Occupancy Mapping](https://thaipduong.github.io/kernelbasedmap/). IEEE International Conference on Robotics and Automation (ICRA), 2020.
 
 ```bibtex
@inproceedings{duong2020autonomous,
  title={Autonomous Navigation in Unknown Environments using Sparse Kernel-based Occupancy Mapping},
  author={Duong, Thai and Das, Nikhil and Yip, Michael and Atanasov, Nikolay},
   booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
   year={2020},
   url = {https://thaipduong.github.io/kernelbasedmap},
   pdf = {https://arxiv.org/pdf/2002.01921.pdf}
 }
```
## Acknowledgement
Our code was built on top of the original fast Relevance Vector Machine training (https://github.com/AmazaspShumik/sklearn-bayes) and the Intel Research lab dataset was borrowed from Sparse Bayesian Hilbert Map code (https://github.com/RansML/Bayesian_Hilbert_Maps)
