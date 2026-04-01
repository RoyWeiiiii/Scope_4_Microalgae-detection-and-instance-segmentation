# Translating pixels into identification: Cutting-edge microalgae detection and instance segmentation by leveraging YOLO models 
<img width="4000" height="2250" alt="GA_Eco_Info_R2" src="https://github.com/user-attachments/assets/0c8ba5e2-b8e7-404c-bb7c-3fcbf2b9efa7" />


**Keywords:** Microalgae; Detection; Instance segmentation; YOLOv7; YOLOv8; YOLOv11

# Folder and files description

**Section 3.1** => Contains Juptyer notebooks, trained results (csv) for YOLOv5-s (small), YOLOv7 (small), and YOLOv8-n (nano) Detection which describes the "**Microalgae detection performance of different algorithms**".

**Section 3.2** => Contains Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (Trial 1, 2, 3, 4, and 5) which describes the "**Impact of dataset labelling and number of instances**".

**Section 3.3** => Contains Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (RGB [Basaeline model], Grayscale, Grayscale with Histogram Equalisation, and Grayscale with Adaptive Equalisation which describes the "**Effect of image pre-processing**".

**Section 3.4** => Contains Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (RGB [Basaeline model], Image-level (IMG) augmentation, and Bounding-box-level (BB) augmentation) which describes the "**Effect of image augmentation**".

**Section 3.5** => Contains Juptyer notebooks, trained results (csv) for YOLOv8-n Instance Segmentation, YOLOv8-n Instance Segmentation under IMG and BB augmentation, and various YOLOv8 model sizes (YOLOv8-n [nano], YOLOv8-m [medium], and YOLOv8-x [large]) which describes the "**Comparison between detection and instance segmentation techniques**" and "**Effect of model sizes**".

**File [Exp_4_Overall_Microalgae_Tabulated_results.xlsx]** => Contains all the results tabulated in excel format

# Google drive (Complete results and data)
For complete results and data can be found in the subsequent link => https://drive.google.com/drive/folders/1An2Erg8YEtNSpN0moSXQFi5zvhcjUn36?usp=drive_link

**Section 3.1** => Contains trained model runs, Juptyer notebooks, trained results (csv) for YOLOv5-s (small), YOLOv7 (small), and YOLOv8-n (nano) Detection which describes the "**Microalgae detection performance of different algorithms**".

**Section 3.2** => Contains trained model runs, Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (Trial 1, 2, 3, 4, and 5) which describes the "**Impact of dataset labelling and number of instances**".

**Section 3.3** => Contains trained model runs, Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (RGB [Basaeline model], Grayscale, Grayscale with Histogram Equalisation, and Grayscale with Adaptive Equalisation which describes the "**Effect of image pre-processing**".

**Section 3.4** => Contains trained model runs, Juptyer notebooks, trained results (csv) for YOLOv8-n Detection (RGB [Basaeline model], Image-level (IMG) augmentation, and Bounding-box-level (BB) augmentation) which describes the "**Effect of image augmentation**".

**Section 3.5** => Contains trained model runs, Juptyer notebooks, trained results (csv) for YOLOv8-n Instance Segmentation, YOLOv8-n Instance Segmentation under IMG and BB augmentation, and various YOLOv8 model sizes (YOLOv8-n [nano], YOLOv8-m [medium], and YOLOv8-x [large]) which describes the "**Comparison between detection and instance segmentation techniques**" and "**Effect of model sizes**".

# Image Dataset Preparation using Roboflow
The preparation of microalgae (_Chlorella vulgaris_ FSP-E, _Chlamydomonas reinhardtii_, and _Spirulina platensis_) dataset "**Detection**" and "**Instance Segmentation**" labelling/ annotation and image pre-processing techniques (Grayscale, Histogram equalisation, Adaptive equalisation) were performed using the "Roboflow platform. 

**Microalgae Detection Ver 1** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Trial 1-4_RGB Dataset" contains Trial_1_RGB, Trial_2_RGB, Trial_3_RGB, and Trial_4_RGB (discussed under section 3.2 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_trial-1-4_rgb/4 **(**Dataset can be downloaded here**)**

**Microalgae Detection Ver 2** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Detection_Baseline model_Augmentation_Image processing Dataset" contains RGB_Baseline model-Trial_5_RGB, Grayscale, Grayscale_Adaptive_Equalisation, Grayscale_Histogram_Equalisation, RGB-IMG-Augmentation, and RGB-BB-Augmentation (discussed under section 3.1, 3.3, and 3,4 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_detection_baseline-model_augmentation_image-processing/11 **(**Dataset can be downloaded here**)**

**Microalgae Instance Segmentation** => In the Roboflow platform, under the filename: "CJWR_Microalgae_Instance_Segmentation Dataset" contains Instance Segmentation_RGB, Instance Segmentation_RGB_IMG_Augmentation, and Instance Segmentation_RGB_BB_Augmentation (discussed under section 3.5 in the manuscript). Website link open access: https://app.roboflow.com/microalgae-hbwao/cjwr_microalgae_instance_segmentation/4 **(**Dataset can be downloaded here**)**

# Referencing and citation
----Not published yet-----
