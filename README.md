# BRATS Brain Tumor Segmentation

## Abstract

This repository consists of implementations of brain tumor segmentation segmentation algorithms on the images obtained from BRATS challenges. Here, segmentation algorithms in ITK library are employed and then an Attention U-Net based segmentation algorithm is explored.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jathurshan0330/BRATS-Brain-Tumor-Segmentation/blob/master/170248G_BM4301_Brain_Tumor_Segmentation.ipynb)

## Brain Tumor Segmentation Using ITK

The segmentation results of the following  MRI brain slice is reported in terms of Dice coefficient and visual comparison. The whole tumor can be segmented using FLAIR images. Addition to that, tumor segmentation results on T1ce and T2 MRI images are also illustrated. Isolated connected, confidence connected, neighborhood connected, canny edge level set segmentation and fast marching segmentation are the implemented ITK algorithms.

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled.png)

### Isolated Connected

Dice Score: 0.9402

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%201.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%202.png)

### Confidence Connected

Dice Score: 0.9205

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%203.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%204.png)

### Neighborhood Connected

Dice Score: 0.9326

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%205.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%206.png)

### Canny Edge Level Set Segmentation

Dice Score: 0.8494

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%207.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%208.png)

### Fast March Segmentation

Dice Score: 0.8082

FLAIR:

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%209.png)

T1ce:

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2010.png)

T2:

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2011.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2012.png)

## Attention U-Net Based Brain Tumor Segmentation

Dice Score: 0.8669

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2013.png)

### Additional Results

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2014.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2015.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2016.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2017.png)

![Untitled](BRATS%20Brain%20Tumor%20Segmentation%20781fd1aaf07a4c49bee366f8662474a2/Untitled%2018.png)