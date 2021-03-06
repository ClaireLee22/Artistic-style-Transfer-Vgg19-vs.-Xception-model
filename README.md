# Artistic-Style-Transfer-Vgg19-vs.-Xception-model
## Project Overview
### Project Description
Use Vgg19 and Xception pre-trained network to do artistic style transfer which obtain a representation of the style of an input image and apply the style to another image while keeping the original image content recognizable.

### Project Procedure
- Preprocess the image to a 4D tensor
- Build the model
  - Create a input tensor with shape (3, height, width, channels or filters)
  - Load the pre-trained model
    - Vgg19
    - Xception
- Calculate loss
  - content loss
  - style loss
  - total variance loss
- Run the model
- Deprocess the image
- Visualize the generated image

(Optional)If want to keep training,
 - Reload the saved weights
 - Train the model

### Project Results
- Created high-quality artistic images either using Vgg19 or Xception pre-trained network.
- Generated images in richer and saturated color by Vgg19 network.
- Made the generated image look vintage by using Xception network. 
- Project Output

 <img src='gen_img/oil_output.jpg' width='600px'>
 <img src='gen_img/doodle_output.jpg' width='600px'>
 <img src='gen_img/sketch_output.jpg' width='600px'>


## Getting Started
### Prerequisites

This project requires **Python 3.6** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [matplotlib](http://matplotlib.org/)
- [Keras](https://keras.io/)
- [SciPy](https://www.scipy.org/install.html)

### Run
In a terminal or command window, run one of the following commands:

```bash
ipython notebook Artistic style transfer-Vgg19.ipynb
```  
or
```bash
jupyter notebook Artistic style transfer-Vgg19.ipynb
```

This will open the iPython Notebook software and project file in your browser.
