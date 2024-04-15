# Bayesian inverse inference of material properties from microstructure images
This notebook contains the code for Bayesian inverse inference based on generative models. The example model is composed of a Vector Quantized Variational Auto-Encoder (VQVAE) and Pixel Convolutional Neural Network (PixelCNN) . 

## Example: dual-phase steel
We demonstrate the applicability of this framework by predicting the mechanical properties of dual-phase steel microstructures.

## Example dataset
We prepare the dataset of artificial dual-phase steel images. The dataset can be downloaded [here](https://drive.google.com/file/d/1MbmGsb0KSwG8yWcFTmTIqi9hzjOwHnph/view?usp=share_link).
If you use the dataset, please cite the following paper.

- S. Noguchi, H. Wang, and J. Inoue, Identification of microstructures critically affecting material properties using machine learning framework based on metallurgists' thinking process, Scientific Reports (2022).

## Authors:
Satoshi Noguchi and Junya Inoue

## References:
- Example by authours
  - S. Noguchi and J. Inoue, Stochastic characterization and reconstruction of material microstructures for establishment of process-structure-property linkage using the deep generative model, Physical Review E (2021).
- VQVAE
  - A. Van Oord, O. Vinyals, and K. Kavukcuoglu, Neural discrete representation learning, in Proceedings of the 31st International Conference on Neural Information Processing Systems (2017).
- PixelCNN
  - A. Van Oord, N. Kalchbrenner, O. Vinyals, L. Espeholt, A. Graves, and K. Kavukcuoglu, Conditional image generation with pixelcnn decoders, in Proceedings of the 30th International Conference on Neural Information Processing Systems (2016)
  - A. Van Oord, N. Kalchbrenner, and K. Kavukcuoglu, Pixel recurrent neural networks, in Proceedings of The 33rd International Conference on Machine Learning (2016).

