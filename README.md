# Face-Generation-using-GAN

This project was developed as a part of Udacity's Deep Learning Nanodegree. In this project, i have created a General Advarsarial Networks from scratch using pytorch. 

## Getting Started

Just run all the cells in the ipynb notebook. Tune the hyper parameters for better accuracy.
Get Data from [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

### Prerequisites

* Python 3
* Numpy
* MatPlotLib
* OpenCv
* Pytorch 

### Install

1. Download the project materials from our GitHub repository. You can get download the repository with
  ```
  git clone https://github.com/vickipedia6/Face-Generation-using-GAN.git
  ```
 2. Download anaconda or miniconda based on the instructions in the [Anaconda documentation](https://docs.anaconda.com).
 
 3. Create a new conda environment:
  ```
  conda create --name deep-learning python=3
  ```
 4. Enter your new environment:
  * Mac/Linux: >> ``` source activate deep-learning ```
  * Windows: >>  ```activate deep-learning ```
  
 5. Ensure you have numpy, matplotlib, pandas, and jupyter notebook installed by doing the following:
  ```
  conda install numpy matplotlib jupyter notebook
  ```
 6. Run the following to open up the notebook server:
  ```
  jupyter notebook dlnd_face_generation.ipynb
  ```
 7. Execute all the cells in the code.
 

### Project results

This project has met the following specifications:
* The submission includes all required, complete notebook files.
* All the unit tests in project have passed.
* The function get_dataloader should transform image data into resized, Tensor image types and return a DataLoader that batches all the   training data into an appropriate size.
* Pre-process the images by creating a scale function that scales images into a given pixel range. This function should be used later,     in the training loop.
* The Discriminator class is implemented correctly; it outputs one value that will determine whether an image is real or fake.
* The Generator class is implemented correctly; it outputs an image of the same shape as the processed training data.
* This function should initialize the weights of any convolutional or linear layer with weights taken from a normal distribution with a   mean = 0 and standard deviation = 0.02.
* The loss functions take in the outputs from a discriminator and return the real or fake loss.
* There are optimizers for updating the weights of the discriminator and generator. These optimizers should have appropriate               hyperparameters.
* Real training images should be scaled appropriately. The training loop should alternate between training the discriminator and           generator networks..
* There is not an exact answer here, but the models should be deep enough to recognize facial features and the optimizers should have     parameters that help wth model convergence.
* The project generates realistic faces. It should be obvious that generated sample images look like faces.
* The question about model improvement is answered.

## Losses

### Generator vs Discriminator Loss :

<img src='/download.png' width=500 px>

## Generated Faces

<img src='/generated_faces.png' width=500 px>

## Built With

* Python 3

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* The data comes from [here](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html)

