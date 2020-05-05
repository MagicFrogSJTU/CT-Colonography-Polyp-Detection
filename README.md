# CT-Colonography-Polyp-Detection
This is about polyp detection in CT images for CT-Colonography as part of my scholar research for master degree.  
The paper hasn't passed peer-review, but it is provided here in case that someone may benefit from it.


## Abstract
Purpose: Typical computer-aided diagnosis (CAD) systems for computed tomography colonography (CTC) consist of two crucial steps, including candidate screening and false positive (FP) reduction. However, simpler solutions with equal or even better performance are always preferred.
Methods: A powerful one-stage framework for polyp detection utilizing the fully convolutional network (FCN) technique is proposed. The stage of FP reduction, the electrical cleansing for the contrast-enhanced fluid and the accurate colon wall modeling are now no longer needed. The root of our work lies in the adaptation of segmentation-specialized FCNs for the task of polyp detection, which mainly comprises three components: 1) a multistep training scheme, 2) an ensemble loss function, and 3) adaptive data transform. The proposed network can be directly trained with the pixel-level polyp segmentation labels, and thus, information on the size, shape and position of the polyps can be seamlessly integrated. Inadequacy of the labeled data, which has long been a problem for the application of 3D CNNs in the field of CAD-CTC, can be largely alleviated.
Results: The proposed method was evaluated using 547 oral contrast-enhanced CT scans with 390 polyps and achieved high by-polyp sensitivity with a low FP rate for both large polyps (>=10 mm) and small polyps (<10 mm). With 1.5 FPs per scan, the by-polyp sensitivity was 99.1%/95.3% for large/small polyps.
Conclusion: The experiment results demonstrate that our proposed framework obtained a superior performance especially on small polyps compared with several state-of-the-art methods.
