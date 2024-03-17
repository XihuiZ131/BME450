# BME450
BME 450 Machine Learning Project

# Title
Brain Tumor Segmentation
## Team members
Xihui Zhao, Jinyang(Jessie) Du
## Project description
[Datasets]

Dataset 1: Brain Tumor MRI Dataset (by Masoud Nickparvar)
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset
This dataset contains 7023 images of human brain MRI images, which can be classified into four categories: glioma, meningioma, pituitary, and no tumor. 

Dataset 2: Brain MRI Scans for brain tumor classification (Shreya Gupta and VishalAg11)
https://www.kaggle.com/datasets/shreyag1103/brain-mri-scans-for-brain-tumor-classification
This dataset contains 1,311 high-resolution brain MRI scans, which can also be classified into the same four classes as mentioned in dataset 1. Images from Dataset 2 may be combined with Dataset1 for further training and testing.

[Project Description]

Brain tumor refers to the growth of cells in the brain or near it [1]. The type of brain tumors can be classified based on locations (like meningiomas and pituitary tumors [2]) and types of cells they are made of (like glioma [3]). Meningioma begins in the membranes that surround the brain or spinal cord, and it is the most common type of primary brain tumor, accounting for approximately 30% of all brain tumors [4]. Pituitary tumors originate from the pituitary gland, a pea-sized organ in the brain that secretes hormones [5]. Glioma originates in the glial cells that support and surround the neurons in the brain [3].

Magnetic resonance imaging (MRI) is a common technology used to detect brain tumors because of  its higher spatial resolution compared with other imaging tests. Precise brain tumor segmentation and localization are beneficial for diagnosis and treatment. Current manual segmentation of brain tumors is time-consuming, expert-needed, and error-prone. A better computational model is needed for higher accuracy and efficiency.

The primary purpose of this project is to develop and refine a deep learning model that can identify the presence of brain tumors and the type of brain tumor if it presents based on MRI scans. Our algorithm is able to identify brain MRI scans and automatically classify the images into the following categories: meningiomas, pituitary tumors, gliomas, and healthy. The model improves diagnostic capabilities of clinicians and patient outcomes in managing brain tumors.








Reference:
[1] “Brain Tumor,” Mayo Clinic, https://www.mayoclinic.org/diseases-conditions/brain-tumor/symptoms-causes/syc-20350084 (accessed Mar. 17, 2024). 

[2] “Brain tumors and brain cancer,” Johns Hopkins Medicine, https://www.hopkinsmedicine.org/health/conditions-and-diseases/brain-tumor (accessed Mar. 17, 2024). 

[3] “Gliomas,” Johns Hopkins Medicine, https://www.hopkinsmedicine.org/health/conditions-and-diseases/gliomas#:~:text=What%20is%20a%20glioma%3F,astrocytes%2C%20oligodendrocytes%20and%20ependymal%20cells. (accessed Mar. 17, 2024). 

[4] “Meningioma diagnosis and treatment,” National Cancer Institute, https://www.cancer.gov/rare-brain-spine-tumor/tumors/meningioma#:~:text=A%20meningioma%20is%20a%20primary,grade%20meningiomas%20are%20very%20rare. (accessed Mar. 17, 2024). 

[5] S. Banskota and D. C. Adamson, “Pituitary adenomas: From diagnosis to therapeutics,” Biomedicines, vol. 9, no. 5, p. 494, Apr. 2021. doi:10.3390/biomedicines9050494, pituitary tumors, gliomas, and healthy. The model provides clinicians to facilitate diagnostic capabilities and improve patient outcomes in managing brain tumors.
