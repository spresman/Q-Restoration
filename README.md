# Q-Restoration

## DIC Microscopy
Differential Interference Contrast (DIC) microscopy is an optical microscopy technique that is generally used to enhance the contrast of transparent cells. A DIC microscope works by capturing the variations in intensity and contrast caused by differences in refractive index and thickness of various parts of the cell. The DIC microscope converts this information into a high contrast, topographical appearance. DIC microscopy offers high resolution and contrast, and provides excellent detail visualizations, making it an extremely powerful tool in biological and biomedical research. 

## Artifacts
Although DIC microscopy is an essential tool for imaging transparent specimen, according to Yin et al. (2011), there are several artifacts that can be observed when utilizing the technique. Bright halos can be observed around the cell membranes, skewing the information provided by pixel intensities. 

![Screenshot 2023-07-01 153335](https://github.com/spresman/Q-Restoration/assets/66577070/88932ff7-69ac-41fe-ad87-737f48647221)
Yin et al. (2011) Figure 1a

A "pseudo 3D shadow" artifact can be present, providing false information about the actual topographical structures of the specimen. 

![Screenshot 2023-07-01 153403](https://github.com/spresman/Q-Restoration/assets/66577070/5b8074c0-8649-4731-984f-55ad36d87e01)
Yin et al. (2011) Figure 1b

## This Repository
In this repository, we will be trying to implement the algorithm proposed in the Yin et al. (2011) paper to restore artifact free DIC images. The algorithm restores the images by minimizing a quadratic cost function, and hopefully we can achieve results comparable to those in the original paper. 

## References:
Yin, Z., & Kanade, T. (2011). Restoring Artifact-Free Microscopy Image Sequences. In Proceedings of IEEE International Symposium on Biomedical Imaging: From Nano to Macro (pp. 909-913).
