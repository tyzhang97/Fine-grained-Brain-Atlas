# A fine-grained cortical and subcortical parcellation with high flexibility and adaptability.


We propose a novel fine-grained brain parcellation with high flexibility and adaptability.It has the following features:

1. Composed of nearly 9,000 regions at sub-centimeter scale, which can be easily reorganized into other atlases. Performing computation at a fine scale once can reliably fit the results of other atlases, providing a solution to the mapping data or measurements between different atlases.

2. We used equal-size spectral clustering methods (https://github.com/anamabo/Equal-Size-Spectral-Clustering) based on vertex or voxel coordinates to further subdivide the cortical regions of the DK atlas and the subcortical regions of the BN atlas in both surface and volume spaces.

3. It provides fundamental units for analyzing structural, functional, or other multimodal data, supporting any scenario requiring precise region localization.

4. For ease of use, we provide versions in commonly used spaces and resolutions, including fsaverage, fs_LR, MNI152N6, and MNI152 2009c, along with label mapping tables for multiple classic atlases

5. If you wish to compute at other scales, you can reorganize the existing fine-grained atlas based on spatial relationships.

Author: Tongyu Zhang

Contact: tyzhang@ibp.ac.cn

### Parcellation workflow and Visualization of the fine-grained atlas:
![Description](/Fig.1.png)
