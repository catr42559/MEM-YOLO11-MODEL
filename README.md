title:MEM-YOLO11: Enhancing Small Object Detection in UAV Imagery through Multi-Feature Integration

《The Visual Computer》

Our work presents an enhanced YOLO-based model that addresses the challenges of detecting small objects in complex scenarios through novel modules such as the Multi-scale Feature Extraction and Edge Enhancement and the Multi-head Receptive Field Enhancement .
In this study, we propose a comprehensive framework that improves detection accuracy and computational efficiency while reducing parameter redundancy. Our findings offer valuable insights for the field of computer vision, particularly in applications requiring precise small object detection.
（1）A novel Multi-scale Feature Extraction and Edge Enhancement (MFEE) module has been designed. This module extracts features at multiple scales and integrates them effectively, emphasizing the edge information of small targets. By doing so, it enhances the feature representation of small targets, improving their detect ability in complex scenarios.
（2）The ELFR (Effective Learning of Feature Representations) module is introduced. This module generates higher-resolution images from the original input and applies an SPDConv slicing operation to the P2 feature layer. This approach not only reduces the number of parameters but also preserves critical information about small targets more effectively. As a result, the module produces feature maps rich in small target details, enhancing the model's ability to detect and localize small objects.
（3）A Multi-head Receptive Field Enhancement (MRFE) module is designed. This module addresses the spatial and channel redundancies commonly found in standard convolutions, significantly reducing the number of parameters and computational complexity without compromising performance. By enhancing the model's ability to capture diverse receptive fields, the MRFE module improves overall detection accuracy and efficiency.


`MEM-YOLO.yaml` is the configuration file for model training. The `block.py` file contains the functions for the MFEE module, ELFR module, and MRFE module. The `dataset` file stores the download links for the dataset.
