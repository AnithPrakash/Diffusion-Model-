# Diffusion-Model

# Abstract 
* To systematically and slowly destroy structure in a data distribution through iterative forward diffusion process
* A reverse diffusion process that restore structure in data, yielding a highly flexible and tractable generative model of the data
* Allow us to rapidly learn, smaple form and evalute probabilities in deep generative models

# Result

*  Over the course of 32 epochs, the forward and backward diffusion model incrementally refines an image from random noise
*  The forward diffusion process gradually adds noise to a data point, while the backward process reverses this, gradually denoising the input to generate a coherent image.

![ddpm_animation](https://github.com/user-attachments/assets/3057ff0e-09dc-4f04-a18a-b68e6e31683e)\

# Process 

*  This iterative approach allows the model to learn the underlying structure of the image and progressively improve its quality with each epoch.

![Screenshot 2024-08-29 125244](https://github.com/user-attachments/assets/4a9b713e-60c9-4c98-a43d-0885ea5c1210)

# Dataset 

* The Sprites 16x16 dataset contains pixel art images, each with a resolution of 16x16 pixels.
* This small size is typical for sprites in video games, making it ideal for studying and developing models that can generate or classify small-scale, low-resolution images

![img 1](https://github.com/user-attachments/assets/3d2961d3-18d4-4ed3-8826-89b6d8724aac)
![img 3](https://github.com/user-attachments/assets/bcc87573-575d-4e12-a475-cf2033f6e320)
![img 5](https://github.com/user-attachments/assets/591f0099-47c2-4dcc-8899-78b855d1a748)

# About 

This process involves leveraging the features and principles derived from the study of Deep Unsupervised Learning using nonequilibrium thermodynamics. By applying these principles within a deep learning framework, we are able to enhance the model's ability to learn and generate patterns or representations. The integration of nonequilibrium thermodynamics into the deep learning platform facilitates more effective and efficient learning, allowing the model to capture complex data distributions and generate accurate outputs. 



