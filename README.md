This paper proposes a new architecture called the Hybrid Autoencoder/Deep Ad-
versarial Ensemble System (HAe/DaES), which combines the strengths of the
Variational Autoencoder (VAE) and Conditional Deep Convolutional Generative
Adversarial Networks (cDCGANs) to generate images in a low-data environment
without the need for class labels. The model leverages the embedded representa-
tion of the data from the VAE as a conditioning variable for the cDCGAN, and
simultaneously uses the discriminator from the cDCGAN to refine the output of
the autoencoder. The proposed architecture outperforms both VAE and cDCGAN
models trained in isolation on a randomly selected subsample of 600 images from
the MNIST dataset.
