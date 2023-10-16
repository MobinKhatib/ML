# ML
Introduction to machine learning project and homeworks

Phase 1 :
  Introduction to mixture models
  Expectation Maximization
  EM algorithm for GMM and CMM
  EM algorithm in Real Applications

Phase 2:
  Apply algorithm in phase 1 to infer clean image from corrupted images   

Phase 3:
  Image Denoising:
    Download the MNIST dataset and create a dataloader that adds gaussian          noise to the input images.
    Design and train an AutoEncoder on the MNIST dataset to denoise the         noisy images.
    Visualize original images, their corresponding noisy images and their          reconstructed versions side by side.
    Repeat the previous steps using PCA algorithm.
  Image super resolution and 
  Image Colorization:
    Download the "image super resolution or image colorization (from            unsplash) " dataset and split it's validation set to new validation set     and test set.
    Design and train an AutoEncoder using PyTorch (not TensorFlow) on the       dataset to enhance the resolution of images from low resolution to high     resolution.
    plot learning curve and visualize low resolution images of test set,        their corresponding high resolution images and their reconstructed          versions side by side
