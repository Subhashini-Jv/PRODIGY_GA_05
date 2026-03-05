# Neural Style Transfer

This project demonstrates **Neural Style Transfer**, a deep learning technique that combines the **content of one image** with the **artistic style of another image** to generate a new stylized image.

The implementation uses a **pretrained VGG19 convolutional neural network** to extract image features and optimize an output image that preserves the structure of the content image while adopting the colors and textures of the style image.

## Technologies Used

* Python
* PyTorch
* Torchvision
* Matplotlib
* Google Colab

## Project Workflow

1. Load a **content image** and a **style image**.
2. Use a **pretrained VGG19 model** to extract deep features.
3. Compute **content loss and style loss**.
4. Optimize the generated image to minimize both losses.
5. Produce a final **stylized output image**.

## Output

The generated image retains the **structure of the content image** while applying the **artistic patterns, textures, and colors of the style image**.

## Internship Task

This project was completed as part of the **Prodigy InfoTech Generative AI Internship – Task 05**.
