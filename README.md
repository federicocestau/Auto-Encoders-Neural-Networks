# Auto-Encoders-Neural-Networks
Autoencoders enable us to distil information by utilising a neural network architecture composed of an encoder and decoder. There are multiple types of autoencoders that vary based on their structure or the problems they are designed to solve.

Autoencoders present an efficient way to learn a representation of your data that focuses on the signal, not the noise. You can use them for a variety of tasks such as:

•	Dimensionality reduction: Undercomplete Autoencoder (AE) — the most basic and widely used type, frequently referred to as an Autoencoder

•	Feature extraction : Sparse Autoencoder (SAE) — uses sparsity to create an information bottleneck

•	Denoising of data/images: Denoising Autoencoder (DAE) — designed to remove noise from data or images

•	New data Generation: Variational Autoencoder (VAE) — encodes information onto a distribution, enabling us to use it for new data generation

While we often use Neural Networks in a supervised manner with labelled training data, we can also use them in an unsupervised or self-supervised way, e.g., by employing Autoencoders.

Autoencoder can distinguish between what’s essential by simultaneously training an encoder and decoder, with the goal of the decoder being the recreation of original data from encoded representation.

•	Autoencoders have Input, Hidden and Output layers similar to that of other types of Neural Networks.

•	Hidden layers of Autoencoders contain two significant parts: Encoder and Decoder.

•	Output nodes within an Autoencoder match the input nodes. Hence, the Autoencoder Neural Network tries to recreate the same feature values that it receives in the Input layer.

Types of Autoencoders: 

•	Undercomplete Autoencoder (the focus of this article) — has fewer nodes (dimensions) in the middle compared to Input and Output layers. In such setups, we tend to call the middle layer a “bottleneck.”

•	Overcomplete Autoencoder — has more nodes (dimensions) in the middle compared to Input and Output layers.
