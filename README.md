# Chest-XRay-Conditional-GAN

This project utilizes a Conditional Generative Adversarial Network (cGAN) to generate synthetic chest X-ray images for seven different diseases. The goal is to use the generated images to augment real data sets, reducing the cost of data collection and addressing privacy concerns in medical imaging. The model was developed using Tensorflow and Keras, and trained on a dataset of chest X-rays from the NIH. Project results and generated images can be found in the project paper [linked here](https://github.com/brendon-ng/Chest-XRay-Conditional-GAN/blob/main/paper.pdf).

![comparison](https://user-images.githubusercontent.com/40370559/213593021-5bc86fd2-b7a9-4f1b-901c-6ed62d569686.png)
Example of a generated chest x-ray from our cGAN.

![allexamples](https://user-images.githubusercontent.com/40370559/213593032-405c495b-4037-4012-aca4-b1f130f820ea.png)
Example of the same artificial chest x-ray if it was infected by the labeled disease.
