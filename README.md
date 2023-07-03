# CV-BrainTumor-Detection-Segmentation
Computer Vision framework for Detection, Segmentation and Classification of Brain Tumor.

Using object detection and instance segmentation on MRI scans of the brain offers significant benefits in identifying tumors. 
These techniques provide accurate localization, early detection, aid in treatment planning, and enhance workflow efficiency. Object detection techniques precisely locate tumor regions within MRI scans, providing information about their exact location, boundaries, size, shape, and relationship with surrounding structures. This precise localization enhances the accuracy of diagnosis and subsequent treatment planning. Automated instance segmentation can detect subtle abnormalities in MRI scans that might be missed during manual examination, enabling early detection of brain tumors. Tumor segmentation also allows the creation of three-dimensional models, useful to provide visual representations of tumors in relation to surrounding structures, assisting physicians in treatment planning. This potentially offer insights into potential risks, determine optimal surgical approaches, and guide radiation therapy delivery, improving the precision and effectiveness of treatment interventions.

In this project, I decided to exploit the power of Transfer Learning to develop a supporting tool for Obejct Detection, Instance Segmentation and realted Classification applied to brain tumors for surgeons and radiologists.
The framework exploits YOLOv8x (Extreme, the most powerful version, trained on 30 epochs with early stopping (patience=2) and optimized for Stochastic Gradient Descent after some hyperparameter tuning.

It is important to note that while object detection and instance segmentation provide valuable assistance, their outputs should always be carefully reviewed by medical professionals. The final diagnosis and treatment decisions should be made by experienced healthcare providers who integrate these findings with their clinical expertise.

> The work has been supervised by Hind Azegrouz Attibi, Lead for Edge Inference at INTEL.

