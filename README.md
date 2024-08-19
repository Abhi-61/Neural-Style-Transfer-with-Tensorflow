# Neural Style Transfer

Neural Style Transfer (NST) is a technique that leverages deep learning to combine the content of one image with the artistic style of another. By utilizing convolutional neural networks (CNNs), NST allows users to generate visually stunning images that merge the content and style of two distinct inputs.

## How It Works:

### Content Representation
The content of the target image is captured by extracting features from a deep layer of the CNN.

### Style Representation
The style of the reference image is encoded by analyzing the correlations between different layers of the CNN.

### Optimization
An initial image, usually a copy of the content image, is iteratively adjusted to minimize the difference in content and style between the generated image and the respective target representations.

### Essence
NST transforms the aesthetic of an image to resemble the artistic style of another while preserving its original content. This technique blends the characteristics of art and imagery through the power of neural networks, allowing for creative and visually striking results.

### Key Components
TensorFlow: This popular open-source machine learning framework is often used to implement NST. TensorFlow provides the tools and infrastructure necessary for building and training neural networks, making it an ideal choice for NST applications.

VGG19 Model: A widely-used CNN architecture for NST is the VGG19 model. Developed by the Visual Geometry Group (VGG) at Oxford, VGG19 is a deep neural network with 19 layers. It is effective in capturing both high-level content and intricate style features, making it a robust choice for image transformation tasks.

##Here are some examples of Neural Style Transfer:

### 1. Cathedral in Van Gogh's art style:

![image](https://github.com/user-attachments/assets/3404677d-9308-4680-9fed-1dbabed9d202) ![image](https://github.com/user-attachments/assets/a245b22f-eadc-4bc5-bc1c-f6a58fdb537f) ![image](https://github.com/user-attachments/assets/44b0c008-5831-41c0-952e-dad6228d7296)

### 2. Dog in Wassily Kandinsky's art style:

![image](https://github.com/user-attachments/assets/d6e82926-b302-49cf-8299-1ef20eee1658) ![image](https://github.com/user-attachments/assets/dcaecd74-cde6-4550-abc7-2107dd743f46) ![image](https://github.com/user-attachments/assets/87c58011-3eee-4809-8c85-afd336a8c0cf)










To run the code yourself, download the notebook and the images in the repository and run each cell in the order given.

Note: To use the images given in the repository, you might have to change the file path for the images when running the relevant code.
