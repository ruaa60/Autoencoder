# Autoencoder & Variational Autoencoder 
Implementations of Autoencoders and Variational Autoencoders using PyTorch.  


###  Autoencoder

Autoencoders learn compressed representations of input data by encoding it into a lower-dimensional latent space and then reconstructing the original input from this compressed representation.  
**Loss Function:** Mean Squared Error (MSE) 

---

###  Variational Autoencoder (VAE)

VAEs are generative models that learn a *probabilistic* mapping to the latent space, allowing generation of new data points.  
**Loss Function:** Reconstruction Loss + KL Divergence 
