# PLASSO-ADSPF-tracker

We will upload codes and related information after the paper is published.

Paper Name: RGBT Tracking Based on PLASSO ‎and Quality Aware Fusion of Deep and Handcrafted Features

Object tracking has always been one of the most challenging topics in machine vision. In recent years, trackers ‎have used RGB-T datasets to overcome the limitations of single-modality data. This paper introduces a Prior ‎Least Absolute Shrinkage and Selection Operator (PLASSO)-based cost function optimized by the Alternating ‎Direction Method of Multipliers (ADMM) for a Discriminative Correlation Filter (DCF)-based tracker. Detailed ‎closed-form solutions for these optimization problems are also given in this paper. The proposed PLASSO-based ‎approach Adaptively Determines the Scale, Parameters, and Features of the PLASSO-ADSPF tracker. PLASSO-‎ADSPF first finds the response map in the Fourier domain for the input images and then uses an efficient ‎adaptive function to fuse the results. Based on the response maps, the proposed tracker adaptively and ‎consciously extracts features (handcraft and Deep Features (DF)) to improve the speed of the tracking algorithm. ‎PLASSO-ADSPF extracts DF from the convolution layer output of a modified pre-trained deep network using ‎SoftMax Tsallis Entropy (TsEn) as a proposed cost function in the last layer. Also, a graph is proposed to ‎determine longitudinal and transverse scales independently and accurately. Moreover, a new bounding box ‎regression is proposed based on PLASSO and Cholesky factorization to refine the target box. Extensive ‎experiments have been performed for the PLASSO-ADSPF tracker on five popular datasets. The results show the ‎superiority of the proposed approach compared to the state-of-the-art trackers.‎

![5](https://github.com/mortezaghazali586/PLASSO-ADSPF-tracker/assets/74765009/f0c55cd6-dd8b-466e-906b-9a58471a5fc5)

![6](https://github.com/mortezaghazali586/PLASSO-ADSPF-tracker/assets/74765009/3fcab690-225c-45d1-9872-a63f68cbaf0e)
