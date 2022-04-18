# CS598-FP-HiTANet
`Final Project, CS598 DLH Deep Learning for Healthcare, UIUC`

This repository is a Pytorch implementation of [HiTANet: Hierarchical Time-Aware Attention Networks for Risk Prediction on Electronic Health Records](https://www.kdd.org/kdd2020/accepted-papers/view/hitanet-hierarchical-time-aware-attention-networks-for-risk-prediction-on-e). Part of the code is adapted from the [official implementation](https://github.com/HiTANet2020/HiTANet).


## Requirements

After downloading the ipynb file and sample dataset, you can run the ipynb file to train and test the model.

<!-- ## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 
 -->

## Results

Our model achieves the following performance on the sample of the heart failure dataset:


| Model name         | Accuracy  | Precision | Recall | F1-score | AUC |
| ------------------ |-------|----|----- | --------|------ |
| Our Implementation on Sample Dataset  |0.772 | 0.823 | 0.897 | 0.857 | 0.630  |
| Reported Result on Full Dataset  |0.823 | 0.724 | 0.587 | 0.647 | 0.564  |
<!-- 

## Contributing

>📋  Pick a licence and describe how to contribute to your code repository.  -->
