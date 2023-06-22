# p-patches
A benchmark dataset for planetary and unstructured environments inspired by HPatches-secquences (Balntas et al. 2017).

The dataset was designed for unstructured and planetary scenes aiming to evaluate keypoint detection and description algorithms and architectures. The dataset contains 120 sequences of images from Earth, Mars and Moon. Each sequence is composed of the original image and five different representations of the original image in terms of illumination and viewpoint. More specifically, 60 out of 120 sequences includes the original image and five generated images with intense illumination changes while the remaining 60 sequences contains the original image and five generated images with various viewpoint changes. In each sequence, five transformation matrices determine the ground truth between the original image and each of the five representations. The sequences with illumination changes contains identity matrices, since the only difference among the representations is the illumination.

The original images from earth were captured in a quarry from the area of Crete, Greece  while the images from Mars were collected by a publicly available dataset of NASA. The moon images are artificial rover-based images which generated and released with CC (Creative Commons) license by Keio University in Japan.

To download the dataset follow this link: 

# References
Balntas V, Lenc K, Vedaldi A, Mikolajczyk K, HPatches: A Benchmark and Evaluation of Handcrafted and Learned Local Descriptors, Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017, pp. 5173-5182
