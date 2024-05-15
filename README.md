Abstract— Image forgery detection is crucial for ensuring the authenticity and integrity of digital content. In this paper, we propose a hybrid approach for improving image forgery detection using deep learning techniques. Our method begins 
with rigorous image preprocessing, which includes the application of edge detection, edge linking, and image enhancement techniques such as bilateral filtering. Edge detection identifies abrupt changes in pixel intensity, 
delineating object boundaries within the image. Edge linking connects adjacent edges to form continuous contours, facilitating subsequent analysis. Bilateral filtering enhances image quality while preserving important edges by smoothing 
pixel intensities based on both spatial and intensity differences. 
These preprocessing steps contribute to the refinement of image features and the enhancement of forgery detection accuracy.
Subsequently, we integrate Principal Component Analysis (PCA), Gray-Level Co-occurrence Matrix (GLCM), and DCUNet, a deep learning architecture, to develop a comprehensive framework for forgery detection and enhancement. PCA reduces the dimensionality of image features, GLCM captures 
textural information, and DC-UNet learns high-level representations for image enhancement. By combining these techniques, our approach achieves robust detection and enhancement of forged regions in digital images. 
A crucial aspect of our methodology is the utilization of ground truth images for validation. Ground truth images are obtained through meticulous manual inspection or by utilizing datasets with known authentic images. These images serve as 
reference points for comparing detected forgery regions, enabling accurate evaluation of the detection algorithm's performance.
ur experimental results underscore the efficacy of the proposed approach in accurately detecting and enhancing 
forged regions in digital images. The comprehensive framework shows promise for practical applications in forensic 
analysis and content authentication. Future research directions include exploring advanced deep learning architectures and 
incorporating additional image processing techniques to further improve the accuracy and robustness of forgery 
detection systems.
Keywords—PCA, Gray-Level Co-occurrence Matrix (GLCM), and DC-UNet
