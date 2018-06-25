# Deep colorize
A deep learning network to colorize black and white images. The dataset used for the project can be found [here](http://cvcl.mit.edu/database.htm)

# How to run
### Clone the repository using

```git clone https://github.com/Rishabhmishra328/deep_colorize.git```

### Train on Google Colaboratory

1. Visit [Google Colaboratory](https://colab.research.google.com/).

2. Add a new notebook to Google Colaboratory.

3. Upload the [Deep_Colorize.ipynb](https://github.com/Rishabhmishra328/deep_colorize/blob/master/Deep_Colorize.ipynb)

4. Select runtime as GPU to use GPU options through, **Runtime > Change runtime type > Hardware accelerator > GPU**.

5. Run the code. **Runtime > Run all**

When the execution is done, the model and the result will get downloaded to your local machine.

# Model

The top end before the branching is used for feature extraction from the image, which is later seperated to predict the red, green blue channels.

![Model](https://github.com/Rishabhmishra328/deep_colorize/blob/master/colorize_model.png)

# Results

The alpha version results for the network.

![Result](https://github.com/Rishabhmishra328/deep_colorize/blob/master/results.png)

