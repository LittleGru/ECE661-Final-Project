# ECE661 Final Project - GANs

This project explores the application of Generative Adversarial Networks (GANs) for synthesizing photorealistic images from random noise. Our study primarily focuses on the implementation and comparison of three advanced GAN models: the original GAN, the Auxiliary Classifier GAN (AC-GAN), and the Wasserstein GAN (WGAN). We aimed to enhance GAN stability and the quality of the generated images, which are crucial for applications in digital media and other innovative fields. Through systematic training over numerous epochs, each model was evaluated based on the Fréchet Inception Distance (FID) scores to quantitatively assess image quality. Our findings reveal that AC-GAN produces higher-quality images due to class conditioning, while WGAN offers improved training stability through its novel loss function, effectively addressing issues such as mode collapse and training oscillation. Additionally, latent space interpolations in AC-GAN demonstrated smooth transitions between generated images, indicating an effective understanding and representation of data. This research underscores the potential of GANs in generating realistic images from mere noise and sets the stage for future applications in more complex datasets and domains.

## Team Members
| Student | Email |
|-----------------|-----------------|
| Zihan Cao | c.zihan@duke.edu |
| Yuxuan Gu | yuxuan.gu@duke.edu |
| Jiazheng Sun | jiazheng.sun@duke.edu |