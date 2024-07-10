# Re-visualising Images: Enhancement using Auto-Encoders and Style Transfer
Project Overview

This project focuses on image enhancement using auto-encoders and style transfer techniques. The primary goal is to improve the quality of images by enhancing details and amplifying contrast. The project integrates technical quality enhancement with artistic expression, providing both visually captivating and perceptually refined outputs.

Abstract

Image enhancement algorithms are crucial in fields like imaging, astronomy, computer vision, and multimedia entertainment. This project introduces a novel approach that employs auto-encoders to enhance low-quality images and style transfer for added aesthetic appeal. The auto-encoder network is trained specifically for low-quality inputs, while the style transfer component incorporates artistic styles from reference images. This method offers faster computational processing and a seamless integration of technical and artistic enhancements.

Keywords

Auto-Encoders
Style Transfer
VGG19
CNN
Methodology

Image Enhancement
The image enhancement method is based on an auto-encoder framework. The generator model is trained using low-resolution pictures, implemented as an encoder-decoder network with convolution and pooling layers. The loss function combines perceptual and pixel-wise loss functions to achieve high-quality image enhancement.

Style Transfer
Style transfer techniques are incorporated to add artistic styles to the enhanced images. This is achieved using a pre-trained model from TensorFlow Hub for arbitrary image stylization. The content and style images are processed to produce a final stylized image that balances content and style representations.

Workflow

Image Enhancement: Enhance low-quality images using an auto-encoder framework.
Style Transfer: Apply artistic styles to the enhanced images using a pre-trained model.
Literature Survey

A comprehensive literature review covers recent advancements in image restoration and style transfer using GANs and CNNs. The review highlights various methods, their achievements, challenges, and future directions.

Results and Evaluation

The proposed method is evaluated based on its ability to enhance image quality and apply artistic styles. The results demonstrate significant improvements in image quality and aesthetic appeal compared to existing methods.

Conclusion

This project presents a robust method for image enhancement that combines technical quality and artistic expression. The integration of auto-encoders and style transfer techniques offers a promising approach for various applications in digital art, entertainment, and social media.

Future Work

Future research could explore further enhancements in image quality and style transfer efficiency, as well as application-specific adaptations for different industries.

References

[Sheng et al.]
[Yan et al.]
[Yuan et al.]
[Ledig et al.]
[Armanious et al.]
[Jiachuan Sheng et al.]
[Fu et al.]
[Zhang et al.]
[Xin Deng]
[Shamsolmoali et al.]
