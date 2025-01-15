# FANet_for_Kvasir_Capsule
Use of the Feedback Attention Network for Polyp Segmentation from Capsule Endoscopy Images

# FANet

FANet, or Feedback Attention Network, is an innovative architecture designed to enhance biomedical image segmentation by utilizing feedback mechanisms during training and inference. Developed by Nikhil Kumar Tomar and colleagues, FANet integrates the predicted mask from a previous training epoch with the current epoch's feature map to apply hard attention across various convolutional layers. This approach enables the network to iteratively refine its predictions, leading to improved segmentation performance. 

A key feature of FANet is its ability to rectify predictions iteratively during testing. By feeding back the output mask from one iteration as input to the next, the network progressively enhances segmentation accuracy. This iterative refinement process allows FANet to adapt to complex biomedical imaging data, capturing both local and global features effectively. 

The architecture has been evaluated on seven publicly available biomedical imaging datasets, demonstrating substantial improvements in segmentation metrics compared to existing state-of-the-art methods. The source code for FANet is available on GitHub, facilitating further research and application in the field. 

In summary, FANet introduces a feedback attention mechanism that leverages information from previous training epochs to iteratively refine segmentation outputs, offering a significant advancement in biomedical image analysis. 

https://ieeexplore.ieee.org/document/9741842

N. K. Tomar et al., “FANET: A Feedback attention Network for improved Biomedical image Segmentation,” IEEE Transactions on Neural Networks and Learning Systems, vol. 34, no. 11, pp. 9375–9388, Mar. 2022, doi: 10.1109/tnnls.2022.3159394. Available: https://doi.org/10.1109/tnnls.2022.3159394

# Kvasir Capsule Seg Dataset

The KvasirCapsule-SEG dataset is an open-access collection specifically curated for polyp segmentation in video capsule endoscopy (VCE). Derived from the larger Kvasir-Capsule dataset, it comprises 55 medically verified polyp frames, each meticulously annotated to include corresponding ground truth masks and bounding box information. 
SIMULA DATASETS

This dataset serves as a valuable resource for developing and evaluating algorithms in medical image segmentation, particularly for applications such as:

Polyp segmentation
Semantic segmentation
Medical image analysis
Semantic meta-learning
Domain generalization
Out-of-distribution detection
Researchers can access the KvasirCapsule-SEG dataset through the following links:

Simula's Official Dataset Page https://datasets.simula.no/kvasir-capsule-seg/

For detailed information about the dataset and its applications, refer to the associated research publication:

D. Jha et al., “NanoNet: Real-Time Polyp Segmentation in Video Capsule Endoscopy and Colonoscopy,” 2021 IEEE 34th International Symposium on Computer-Based Medical Systems (CBMS), pp. 37–43, Jun. 2021, doi: 10.1109/cbms52027.2021.00014. Available: https://doi.org/10.1109/cbms52027.2021.00014



