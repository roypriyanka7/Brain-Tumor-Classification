# Brain-Tumor-Classification

<h3>
This repository contains the data, coding files and other resources to replicate the findings of our paper titled "An Ensemble Approach for Advanced Brain Tumor Classification Applying Dual-GAN Mechanism and Feature Extraction Techniques over Highly Imbalanced Data". 
</h3>


### Dataset Description:

- [DS-I: Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
- [DS-II: Brain Tumour Dataset](https://www.kaggle.com/datasets/niranjananehru/brain-tumour-dataset)

### Description of DS-I: 
This dataset is the combined version of figshare, SARTAJ dataset and Br35H. It contains 7033 images of human brain MRI images.

| Class | No. of Samples |
| ------ | ------ |
| glioma | 1621|
| meningioma | 1645|
| pituitary | 1767 |
| no tumor  | 2000|

### Description of DS-II: 
This dataset is created by NIRANJANA NEHRU. The minority class, Craniopharyngioma images has been collected from this dataset.

| Class | No. of Samples |
| ------ | ------ |
| Craniopharyngioma  | 70 |

### Proposed Methodology:

![Methodology](https://github.com/user-attachments/assets/a1aa65cf-6733-4a99-831f-3b85f3c0591d)
<h4> <center> Overview of The Proposed Methodology</center></h4>

We introduce a novel and reliable pipeline leveraging WGAN-GP and Real-ESR GANs with deep feature extraction methods to significantly enhance the accuracy of brain tumor classification from MRI images. Our approach effectively addresses challenges posed by highly imbalanced data and demonstrates strong generalizability, achieving superior accuracy compared to state-of-the-art deep learning models. These results underscore the potential of our proposed mechanism to improve computer-aided early-stage brain tumor diagnosis.


![Explainability with GradCAM](https://github.com/user-attachments/assets/808a700c-a434-4b45-8be2-288895eb48e8)
<h4> <center> Explainability with GradCAM </center></h4>
This study focuses on achieving high classification accuracy while prioritizing stable performance. By incorporating Grad-CAM, it enhances the transparency and interpretability of the overall classification process. This research identifies the most relevant and contributing parts of the input images toward accurate outcomes enhancing the reliability of the proposed pipeline.  

<h4> </h4>

You can cite our research as follows:

```
@article{10.1371/journal.pone.0310748,
    doi = {10.1371/journal.pone.0310748},
    author = {Roy, Priyanka AND Srijon, Fahim Mohammad Sadique AND Bhowmik, Pankaj},
    journal = {PLOS ONE},
    publisher = {Public Library of Science},
    title = {An explainable ensemble approach for advanced brain tumor classification applying Dual-GAN mechanism
              and feature extraction techniques over highly imbalanced data},
    year = {2024},
    month = {09},
    volume = {19},
    url = {https://doi.org/10.1371/journal.pone.0310748},
    pages = {1-21},
    number = {9}
}
```
