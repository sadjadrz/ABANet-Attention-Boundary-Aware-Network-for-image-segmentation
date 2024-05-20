ABANet (Attention Boundary-Aware Network for image segmentation)
---
> This repository is the official PyTorch implementation of the paper "[ABANet: Attention boundary-aware network for image segmentation](https://doi.org/10.1111/exsy.13625)"

> [Sadjad Rezvani](https://sadjadrz.github.io/), [Mansoor Fateh](https://scholar.google.com/citations?user=ZHezeMIAAAAJ&hl=en&oi=ao), [Hossein Khosravi](https://scholar.google.com/citations?hl=en&user=htZke-UAAAAJ)

#### Sadjad Rezvani, x, y, z
#### Paper: https://google.com
> Deep learning techniques have attained substantial progress in various face-related tasks, such as face recognition, face inpainting, and facial expression recognition. To prevent infection or the spread of the virus, wearing masks in public places has been mandated following the COVID-19 epidemic, which has led to face occlusion and posed significant challenges for face recognition systems. Most prominent masked face recognition solutions rely on mask segmentation tasks. Therefore, segmentation can be used to mitigate the negative impacts of wearing a mask and improve recognition accuracy. Mask region segmentation suffers from two main problems: there is no standard type of masks that people wear, they come in different colors and designs, and there is no publicly available masked face dataset with appropriate ground truth for the mask region. In order to address these issues, we propose an encoder-decoder framework that utilizes a boundary-aware attention network combined with a new hybrid loss to provide a map, patch, and pixel-level supervision. We also introduce a dataset called MFSD, with 11601 images and 12758 masked faces for masked face segmentation. Furthermore, we compare the performance of different cutting-edge deep learning semantic segmentation models on the presented dataset. Experimental results on the MSFD dataset reveal that the suggested approach outperforms state-ofthe-art, algorithms with 97.623% accuracy, 93.814% IoU, and 96.817% F1-score rate. 

### Network Architecture
![image](https://github.com/sadjadrz/ABANet-Attention-boundary-aware-network-for-image-segmentation/assets/77124662/5a1102dd-5197-4535-907a-0a1fd7ece100)
![image](https://github.com/sadjadrz/ABANet-Attention-boundary-aware-network-for-image-segmentation/assets/77124662/6cbd368d-9cd8-40a9-bde1-6423c1986bab)

### News

### Requirements

```
Python 3.7.11
numpy 1.18.5
scikit-image 0.19.2
pillow 9.0.0
PyTorch 1.10.1
torchvision 0.11.2
Matplotlib=3.2.2
```

create a conda environment: 
```
conda create -n ABANet python=3.7.11 -y
conda active ABANet
pip install torch==1.10.1 torchvision==0.11.2 --extra-index-url https://download.pytorch.org/whl/cu113
Model
```

### Quick Start (training)
1. Clone this repo
```
git clone https://github.com/sadjadrz/ABANet-Attention-boundary-aware-network-for-image-segmentation
```
2. Cd to the directory 'ABANet', run the training or inference process by command: ``python ABANet_train.py``

 
### Results



### License

### Citations

If ABANet-Attention-Boundary-Aware-Network-for-image-segmentation helps your research or work, please consider citing it.
```
@InProceedings{qq,
    author    = {x, y, z, r, t, v},
    title     = {ABANet-Attention-Boundary-Aware-Network-for-image-segmentation},
    booktitle = {},
    month     = {},
    year      = {},
    pages     = {}
}
```

### Contact
If you have any questions, please contact sadjadRezvani@gmail.com.
