# Neural Style Transfer Project

**Neural Style Transfer** is a technique discussed in paper [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) which introduces an artificial system based on a Deep Neural Network that creates artistic images of high perceptual quality. The system uses neural representations to separate and recombine content and style of arbitrary images, providing a neural algorithm for the creation of artistic images. In simple terms, **Neural Style transfer** is a computer vision topic for stylization that takes two images: a content image and a style reference image, and blends them together so that the resulting output image retains the core elements of the content image, but appears to be painted in the style of the style reference image. This stylization heavily depended on the CNN under study and is more customizatable than CycleGAN (according to the blog).

This project main focus is to take advantage of the customization provided by this technique to generate an image that looks as though painted by a famous artist.

**Note:** This project is partially inspired from [TensorFlow's Neural Style Transfer Documentation](https://www.tensorflow.org/tutorials/generative/style_transfer) and **Assignment** in [TensorFlow: Advanced Techniques Specialization - Coursera](https://www.coursera.org/specializations/tensorflow-advanced-techniques). 


## Approach

1. Importing the Data (content and style images).
2. Choosing a model architecture to generate stylized images.
3. Preprocessing the Data.
4. Exploring the Data (optional: for the sake of audience)
5. Creating custom loss functions.
6. Utilizing TensorFlow's Gradient Tape to update the stylized image.
7. Using Adam's optimizer instead of LBFGS (as it also works fine).
8. Saving the results in .gif format.

### Content Images

<p align="center">
    <img src="https://github.com/mhd-danish/portfolio_neural_style_transfer/blob/main/extras/contents.png">
</p>

### Style Images

<p align="center">
    <img src="https://github.com/mhd-danish/portfolio_neural_style_transfer/blob/main/extras/styles.png">
</p>

## Example

Let's take one example to show how the neural style transfer actually works.

### Content Image

<p align="center">
    <img width="200" height="200" src="https://github.com/mhd-danish/portfolio_neural_style_transfer/blob/main/data/content_images/content_img_6.jpg">
</p>

### Style Image

<p align="center">
    <img width="200" height="200" src="https://github.com/mhd-danish/portfolio_neural_style_transfer/blob/main/data/style_images/style_img_2.jpg">
</p>

### Generation

<!-- <p align="center">
    <img src="https://github.com/mhd-danish/porfolio_food_vision/blob/main/images/models.png" alt="Pre-Trained CNN Models">
</p> -->