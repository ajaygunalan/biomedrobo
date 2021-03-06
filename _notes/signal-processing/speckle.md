---
layout: note
title: Speckle Reduction in OCT Images
bibFile: imageProcessing
category: Signal-Processing
permalink: /:categories/:title/

---

### What is speckle?
##### Great Videos

Check the [video](https://www.futurelearn.com/courses/ultrasound-imaging/8/steps/1063646) under section 3.5 Technical description of the images in the course [Ultrasound Imaging](https://www.futurelearn.com/courses/ultrasound-imaging) by the University of Twente.

### What is a kernel?
### What is a wavelet?
### Difference between the averaging and diversity method?
### Four Methods of diversity
  1. Frequency Compounding
  2. Polarization Compounding
  3. Angular Compounding
  4. Spatial Compounding

### What is Compressive Sampling?

<!---
1. Various speckle reduction methods have been proposed in the last decades, and they can be catergorized into two groups filter-based and diffusion-based. The former approach includes Kuan filter, Lee filter, enhanced Lee filter, weighted median filter and adaptive Wiener filter. The latter approach are anisotropic diffusion, anisotropic diffusion, nonlinear complex diffusion filter {% cite Yan2020Speckle %}.

2. Some standard basic image denoising techniques are mean, median and Gaussian filtering. The current state of the art technique across the board is BM4D, a patch based denoising method. Some speckle noise reduction techniques have been developed specifically for OCT volumes based on locally adaptive filtering, soft thresholding of wavelet subbands, neural networks, and a hybrid wavelet-total variation denoising {% cite Shamouilian2019Total %}.


3. First, speckle has a signal-dependent or multiplicative nature, and the statistical modeling of speckle is a challenging task. Second, the appearance of speckle is dependent on the tissue being imaged . So, a machine learning approach to speckle removal may not be robust to change of tissue. Third, traditional noise removal filters often cause false edges or destroy edges. As a result, crucial radiological information about the tissue may be lost or misinterpreted. Some early efforts were based on the median filter, the Wiener filter, and temporal averaging. But none of these methods can preserve anatomical information accurately. Some researchers, on the other hand, have taken a different approach using the wavelet transform. These methods apply wavelet shrinkage techniques. Some of the more recent techniques tackle the problem of speckle reduction by updating partial differential equations in the form of anisotropic diffusion. Given the implementation details of anisotropic diffusion, all of these models are sensitive to the number of iterations. If the number of iterative steps is not tuned properly, the edges in the images are often destroyed. In the authors propose a speckle removing filter that relies on statistics of non-local patches. This method does not depend on diffusion and often result in superior edge preservation. But, use of non-local patches causes poor noise removal in several cases {% cite Paul2019Speckle %}.


4. Angular compounding, frequency compounding, and spatial diversity based design are representative hardware-side methods. On the contrary, those software-side methods are postprocessing techniques, and mainly include the digital filtering and sparse coding mechanisms. while the single-frame methods, including imagedomain methods, and wavelet methods, either suffer from the high-computational cost or the wavelet domain processing artifacts. it is also worth noting that all previous studies assumed that the OCT speckle noise consists mainly of multiplicative noise, and the additive noise. OCT images still suffer from the inherent additive noises in OCT systems. The SNR improvements with those proposed methods are also limited, especially for tissues with high speckle noise contamination. So far, no previous studies have ever evaluated the influences of additive noise to OCT images, to the best of our knowledge {% cite Wang2018Twostep %}.

5. For example, the compounding techniques, which average multiple uncorrelated recordings, are widely used. This class of methods is not preferred because it is time consuming and requires additional imaging system hardware modification. locally adaptive filtering [5], soft thresholding of the wavelet sub-bands, and neural networks have been proposed. "In this paper we propose a novel speckle noise reduction algorithm via solving a convex optimization problem. The objective function to be minimized is defined based on the assumption that the underlying OCT data is a sum of two components: (i ) the clean structures, which are smooth patterns with sharp edges and (ii ) the spatially sparse speckle noise. In the proposed approach, the two components are decomposed and penalized by a unified wavelet-TV regularization and norm, respectively. Morel1 over, the en face fundus information is also considered as a constraint in this optimization problem {% cite Sui2018Speckle %}.

6. Wiener filter, and wavelet filter have been proposed. Of these, use of a wavelet filter is a powerful method to reduce the speckle noise, and this filter is often used in ultrasound images. The model of the speckle noise has a multiplicative nature, and conventional filtering methods are somewhat ineffective against this speckle noise. In 2003, we have developed a denoising method using a wavelet transform for radiographic images. In this paper, we applied the method to OCT images {% cite Murakami2018Speckle %}.

-->
