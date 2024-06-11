# GANs
Deblurring an Image GANs(Generative Adversarial Networks).

Text De-blurring using GANs

Overview
This repository contains code for training a deep learning model to de-blur textual-based images. The model leverages the power of Generative Adversarial Networks (GANs) to enhance the clarity and legibility of blurred text in images.

Dataset
We use a curated dataset of blurred textual-based images for training and evaluation. This dataset comprises a diverse collection of images with varying degrees of blur, ensuring robustness and generalization of the trained model.

Model Architecture
The core of our approach is based on a GAN architecture:

Generator: Takes in a blurred image as input and generates a de-blurred version of the image.
Discriminator: Distinguishes between the de-blurred images produced by the generator and the ground truth sharp images from the dataset.

Getting Started

Clone the repository:

  : git clone https://github.com/yourusername/text-deblurring.git
  
  : cd text-deblurring

Results
We evaluate the performance of our model using standard image quality metrics such as PSNR and SSIM. Additionally, visual inspection of the de-blurred images provides insights into the effectiveness of the model in enhancing text legibility.

Contributing
Contributions to this project are welcome! If you have ideas for improvements or encounter any issues, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
We acknowledge the contributions of the open-source community and the developers of deep learning frameworks that made this project possible.

