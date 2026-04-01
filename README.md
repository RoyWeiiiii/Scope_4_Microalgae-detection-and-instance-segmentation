# Graphical Abstract
<img width="4000" height="2250" alt="GA_Eco_Info_R2" src="https://github.com/user-attachments/assets/0c8ba5e2-b8e7-404c-bb7c-3fcbf2b9efa7" />

# Translating pixels into identification: Cutting-edge microalgae detection and instance segmentation by leveraging YOLO models 

By **Jun Wei Roy Chong**, Kuan Shiong Khoo, Huong-Yong Ting, Iwamoto Koji, Zengling Ma, Pau Loke Show

This study harnesses the advanced capabilities of the YOLOv11 model to enhance real-time detection and instance segmentation of microalgae species, specifically Chlorella vulgaris FSP-E, Chlamydomonas reinhardtii, and Spirulina platensis. Comprehensive evaluations revealed that the original RGB dataset provided better detection accuracy compared to pre-processed datasets. The YOLOv11-n box detection achieved high accuracy with precision, recall, F1 score, mAP50, and mAP50-95 of 0.860 ± 0.000, 0.871 ± 0.002, 0.865 ± 0.001, 0.916 ± 0.002, and 0.727 ± 0.002, respectively. Nonetheless, YOLOv11-n box instance segmentation demonstrated superior performance with precision, recall, F1 score, mAP50, and mAP50-95 of 0.893 ± 0.006, 0.904 ± 0.009, 0.898 ± 0.002, 0.952 ± 0.001 and 0.810 ± 0.005, respectively. On this dataset and hardware, the YOLOv11 slightly outperformed its predecessors, YOLOv5, YOLOv7, and YOLOv8, in terms of comparable overall performance with lower computational cost and faster inference speed, yet still able to deliver high accuracy results on densely populated microalgae samples. 

**Keywords:** Microalgae; Detection; Instance segmentation; YOLOv7; YOLOv8; YOLOv11

# Folder and files description

**Note:** All experiments were performed in triplicate by running 3 different seed values of Seed=0, Seed=42, and Seed=1337 to ensure reliability of the work

# Google drive (Complete results and data)
For complete results and data can be found in the subsequent link => https://drive.google.com/drive/folders/1snWsnSzZehW-pF3uX65zt4NcGAdU0gUv?usp=sharing

**Section 3.1** => Contains Juptyer notebooks, images (train, val, test), trained results (csv) for YOLOv5-n (nano), YOLOv7-tiny (tiny), YOLOv8-n (nano), and YOLOv11-n (nano) Detection models which describes the "**Microalgae detection performance of different algorithms**". The Google Drive link is as follows: https://drive.google.com/drive/folders/1SuflYLkYU9PlPBTX6Uruapmk5DYnNOXw?usp=sharing

**Section 3.2** => Contains Juptyer notebooks, images (train, val, test), trained results (csv) for YOLOv11-n Detection (Trial 1, 2, 3, 4, and 5) which describes the "**Impact of dataset labelling and number of instances**". The Google Drive link is as follows: https://drive.google.com/drive/folders/11438i9l4H90QnnXHoBuuTwY-k5yo7wYK?usp=sharing

**Section 3.3** => Contains Juptyer notebooks, images (train, val, test), trained results (csv) for YOLOv11-n Detection (RGB [Baseline model], Grayscale, Grayscale with Histogram Equalisation, and Grayscale with Adaptive Equalisation which describes the "**Effect of image pre-processing**". The Google Drive link is as follows: https://drive.google.com/drive/folders/13j8O0nCAdeBi5NBSD-0Dgysg4HZRLj5E?usp=sharing

**Section 3.4** => Contains Juptyer notebooks, images (train, val, test), trained results (csv) for YOLOv11-n Instance Segmentation models, which describes the "**Comparison between detection and instance segmentation techniques**". The Google Drive link is as follows: https://drive.google.com/drive/folders/1SM4GGRcFaFYUwdKVCkfqaMK1qIcSlolY?usp=sharing

**Section 3.5** => Contains Juptyer notebooks, images (train, val, test), trained results (csv) for various YOLOv11 model sizes (YOLOv11-n [nano], YOLOv11-s [small], YOLOv11-m [medium], YOLOv11-l [large], and YOLOv11-x [extra-large]) which describes the "**Impact of model sizes on detection and instance segmentation tasks**". The Google Drive link is as follows: https://drive.google.com/drive/folders/1Kj_eQQJ1MkjflSUYr2svGEOLpGc_C1CO?usp=sharing

**File_1 [Exp_4_Overall_Microalgae_Tabulated_results_R2-1_Submit.xlsx]** => Contains all the results tabulated in Excel format

**File_2 [Exp_4_YOLO_Models_Development_R2-1_Submit.xlsx]** => Contains all the methodology pipeline of model development for YOLOv5, YOLOv7, YOLOv8, and YOLOv11 with Juptyer notebook and Python

# Image Dataset Preparation using Roboflow
The preparation of microalgae (_Chlorella vulgaris_ FSP-E, _Chlamydomonas reinhardtii_, and _Spirulina platensis_) dataset "**Detection**" and "**Instance Segmentation**" labelling/ annotation and image pre-processing techniques (Grayscale, Histogram equalisation, Adaptive equalisation) were performed using the "Roboflow platform. 

**Microalgae Detection Ver 1** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Trial 1-4_RGB Dataset" contains Trial_1_RGB, Trial_2_RGB, Trial_3_RGB, and Trial_4_RGB (discussed under section 3.2 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_trial-1-4_rgb/4 **(**Dataset can be downloaded here**)**

**Microalgae Detection Ver 2** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Baseline model_Augmentation_Image processing Dataset" contains RGB_Baseline model-Trial_5_RGB, Grayscale, Grayscale_Adaptive_Equalisation, Grayscale_Histogram_Equalisation, RGB-IMG-Augmentation, and RGB-BB-Augmentation (discussed under section 3.1, 3.3, and 3,4 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_baseline-model_augmentation_image-processing/11 **(**Dataset can be downloaded here**)**

**Microalgae Instance Segmentation** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Instance_Segmentation Dataset" contains Instance Segmentation_RGB, Instance Segmentation_RGB_IMG_Augmentation, and Instance Segmentation_RGB_BB_Augmentation (discussed under section 3.5 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_instance_segmentation/4 **(**Dataset can be downloaded here**)**

# Referencing and citation
----Not published yet-----
