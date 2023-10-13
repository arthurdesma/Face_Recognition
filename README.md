
# Modern Face Recognition with Deep Learning

Welcome to the face recognition project! This repository provides a Jupyter notebook assignment that dives deep into the world of modern face recognition using deep learning techniques.

![Face Recognition Pipeline](https://perso.esiee.fr/~najmanl/FaceRecognition/figures/summary.gif)

## Table of Contents

1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Required Packages](#required-packages)
4. [Assignment Overview](#assignment-overview)
5. [Contributing](#contributing)
6. [License](#license)

## Introduction

Have you ever wondered how Facebook can recognize your friends in photographs? As humans, we're naturally wired to recognize faces, but teaching a computer to do the same is a complex task. In this assignment, we'll explore the complete face recognition pipeline, from detecting a face in an image to predicting its identity.

## Getting Started

1. Clone this repository: 
   ```
   git clone [repository-link]
   ```
2. Navigate to the directory and open the provided Jupyter notebook: `TP7_FaceRecognition.ipynb`.
3. Follow the instructions in the notebook to complete the assignment.

## Required Packages

To complete this assignment, you will need the following packages:

- [Numpy](http://www.numpy.org)
- [Keras](https://keras.io)
- [OpenCV](https://opencv.org)
- [Dlib](http://dlib.net)

> **Note**: If you're using Anaconda Navigator, the `dlib` package can be installed from the **conda-forge** channel. On platforms like Google Colab, the required packages are readily available.

## Assignment Overview

In this assignment, you will:

1. **Face Detection**: Identify and locate faces in an image.
2. **Pose Estimation**: Determine the orientation of a face and correct its pose.
3. **Face Encoding**: Extract unique features from a face to distinguish it from others.
4. **Face Recognition**: Compare the features of a face to those in a database and predict the identity.
5. **Personal Dataset**: Build your own face recognition dataset.

## Contributing

Feel free to fork this project and submit pull requests. All contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
