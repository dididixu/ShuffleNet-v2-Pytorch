# shufflenetv2 in Pytorch
- The paper about shufflenetv2: [shufflenet v2](https://arxiv.org/pdf/1807.11164.pdf)
- I implement the shufflenetv2, and test the performance on classification and detection tasks. You can use these codes to train model on your dataset.

## Version
- Python 3.6
- torch 1.1.0
- torchvision 0.3.0
## To do
- [x] Network structure
- [x] Used for Classification
- [ ] Used for Objection detection
## Usage
### For classification
- If you want to test classification demo.
1. Download the project `https://github.com/ZhuYun97/shufflenetv2.git`
2. You should download the [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition).
3. Then, put the dataset into the corresponding location.
### For detection
TBD
## Training own your dataset
### For classification
TBD
### For detection
TBD
## Experiments
I train the model about 5 eopchs, and in each eopch, I test the performance of trained model.
```
Phase train loss: 0.6354673637662616, acc: 0.6564571428571429
Phase val loss: 0.5708242939949035, acc: 0.7146666666666667
Phase train loss: 0.493809922170639, acc: 0.7606285714285714
Phase val loss: 0.5668963393211365, acc: 0.724
Phase train loss: 0.4324655994551522, acc: 0.7994857142857142
Phase val loss: 0.4208303438186646, acc: 0.8048
Phase train loss: 0.38515312327657425, acc: 0.8273714285714285
Phase val loss: 0.37815397882064183, acc: 0.8298666666666666
Phase train loss: 0.3477836193084717, acc: 0.8467428571428571
Phase val loss: 0.34451772966384886, acc: 0.8441333333333333
```
## Dataset
For **classification** dataset: I use a [dataset](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition) from kaggle which contains two classes(cats, dogs).
For detection dataset: TBD
## reference material
- For structure: [shufflenet-v2](https://github.com/ericsun99/Shufflenet-v2-Pytorch)
- For data processing: [process data](https://zhuanlan.zhihu.com/p/29024978)

