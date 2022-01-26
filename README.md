# DiagnoAce-Automated-Teeth-Segmentation-in-X-ray-Images

The project focuses on presenting a thorough review of segmentation approaches for recognizing picture patterns in dental X-rays that have been published. The primary focus will be to segment the region of dental damage from the enamel and pulp region in the radiographs to identify dental caries and other damage. We believe that the transition from analog to digital radiography will furthermore simplify and accelerate the procedure while also facilitating picture storage, modification (brightness/contrast, image cropping, etc.), and retrieval.

## Methodology:

The overall proposed solution is described as follows:

1.	Collection of the dataset from official sources (Bitewing and Panoramic).
●	Bitewing: Bitewings are one of the most common sets of X-rays. Bitewings show teeth above the gum line and the height of the bone between teeth. Bitewings help diagnose gum disease and cavities between teeth.
●	Panoramic: Panoramic x-ray is a two-dimensional (2-D) dental x-ray examination that captures the entire mouth in a single image, including the teeth, upper and lower jaws, surrounding structures, and tissues.
2.	Application of different Segmentation methods to specify the region of interest. The applied methods are
●	Region-Based Segmentation
●	Threshold Based Segmentation
●	Boundary-Based Segmentation
3.	Application of state-of-the-art neural network architecture “U-Net” for a more precise and faster interpretation.
4.	U-Net localizes and distinguishes the borders by doing classification on every pixel so that the input and the output share the same image size. 
5.	Through U-Net we achieve semantic segmentation, which uses a fully convolutional network for the segmentation.
6.	The output itself is a high-resolution image (typically of the same size as the input image) in which each pixel is classified to a particular class. Thus it is pixel-level image classification.
7.	Integration of the applied models into an interactive dashboard for a clearer Layman understanding.
