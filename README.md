# WaveletDiffusionModel

This repository involves the implementation of the work: "WDT-MD: Wavelet Diffusion Transformers for Microaneurysm Detection in Fundus Images"
The authors proposed: 
- A Wavelet Diffusion Transaformer framework for MA detection (WDT-MD)
  - A noise encoded image conditioning mechanism to avoid "identity mapping" by perturbing image conditions during training,
  - Pseudo-normal pattern synthesis via inpainting to introduce pixel-level supervision. This enables discrimination between MA and other anomalies.
  - A wavelet diffusion transformer architecture that combines global modelling capability of diffusion transformers with multi-scale wavelet analysis to enhance reconstruction of normal retinal features.
