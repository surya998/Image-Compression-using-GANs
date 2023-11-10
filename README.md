# Image-Compression-using-GANs
A Generative Adversarial Network Architecture based technique to compress images and decrease transmission data while maintaining the clarity and quality of the images.

Given the success of GANs in image generation, it is reasonable to explore their potential for image compression. If successful, GAN-based compression techniques could provide an alternative to traditional compression techniques, offering high compression rates while preserving image quality. Furthermore, GAN-based compression could also allow for more efficient transmission of visual data, making it possible to transmit larger amounts of data over networks with limited bandwidth.

Therefore, the motivation for the project "Image Compression Using GANs" is to explore the potential of GANs in image compression and to develop a GAN-based compression technique that offers high compression rates while preserving image quality. We got compression results for 81%, 57%, 32% and 16% of original image size.

We used Flickr-30k dataset from Kaggle to train our models and standard and different category images to test our models using Google colab Nvidia T4 GPU.

Our project aims to reconstruct an image from encoded image that has an SSIM value of >0.95 on average and PSNR values >30.0 on average.

Using this compression technique, the image quality can be further increased with increase in hardaware and number of Convolutional layers used.

Conclusions:

Optimal compression ratios: The experiment suggests that different image categories have varying optimal compression ratios.

Context-specific compression requirements: The results highlight the importance of considering the specific characteristics and content of different image categories when determining the most suitable compression ratio. Anime images, which often contain vibrant colors and intricate details, may require higher compression ratios to maintain visual quality. On the other hand, Astronomical images, which focus on capturing subtle celestial details, may benefit from lower compression ratios.

Subjectivity of compression suitability: The determination of the "most suitable" compression ratio is subjective and depends on the evaluation metric used in the experiment. In this case, the PSNR (Peak Signal-to-Noise Ratio) was used to assess image quality. However, other metrics or subjective human evaluations could yield different results. It's important to consider this subjectivity when interpreting the conclusions.

Potential for customized compression: These findings suggest that GAN-based image compression models have the potential to adapt to different image categories and their specific compression requirements. By training models on specific image domains, it becomes possible to optimize compression ratios for each category, leading to improved visual quality and efficiency.

Practical implications: The study demonstrates the importance of tailoring image compression techniques to the specific characteristics of image categories. By identifying the most suitable compression ratios for different types of images, the study provides insights for developers, researchers, and practitioners working on image compression systems. This knowledge can guide the development of specialized compression algorithms and tools for various applications, including anime platforms, astronomical data analysis, satellite imagery, and scenic photography.

Example for Compression effects on Lena Image:

![2023-11-10 22_04_26-IMAGE COMPRESSION USING GANS (Protected View) - Word](https://github.com/surya998/Image-Compression-using-GANs/assets/76418814/bb1c72cd-3be5-4057-825f-e2bd1297ea34)

