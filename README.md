# K-Arm Backdoor Optimization

This is the official repository of the ICML2021 paper [Backdoor Scanning for Deep Neural Networks through K-Arm Optimization](https://arxiv.org/abs/2102.05123) in PyTorch.

If you find this code is useful for your research, please cite the following:

```
@article{shen2021backdoor,
  title={Backdoor Scanning for Deep Neural Networks through K-Arm Optimization},
  author={Shen, Guangyu and Liu, Yingqi and Tao, Guanhong and An, Shengwei and Xu, Qiuling and Cheng, Siyuan and Ma, Shiqing and Zhang, Xiangyu},
  journal={arXiv preprint arXiv:2102.05123},
  year={2021}
}
```

## Setup Environments
We suggest to use Conda for testing the code on [TrojAI](https://pages.nist.gov/trojai/) datasets. Detailed instruction can be found [here](https://github.com/usnistgov/trojai-example).

### Install Anaconda Python 

[https://www.anaconda.com/distribution/](https://www.anaconda.com/distribution/)

### Setup the Conda Environment

1. `conda create --name trojai-example python=3.8 -y`
2. `conda activate trojai-example`
3. Install required packages into this conda environment

    1. `conda install pytorch=1.7.0 torchvision=0.8.0 torchtext==0.8.0 cudatoolkit=11.0 -c pytorch -c conda-forge` 
    2. `pip install --upgrade trojai`
    3. `conda install jsonpickle`

## Quick Start

To test the code, simply run command

```bash
$ python main.py --result_filepath <resultFilepath> --examples_dirpath <dataDirpath> --model_filepath <modelFilepath>
```


## Contacts 

Guangyu Shen, [shen447@purdue.edu](shen447@purdue.edu)

