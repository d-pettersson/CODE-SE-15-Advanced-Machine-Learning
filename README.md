# Exploration in Deep Learning algorithms

This repository contains the semester work for the SE15 Advanced Machine Learning Module.
It is an exploration into the matter of Machine Learning algorithms, and more precisely Deep Learning for image synthesis.

This research is a preliminary work for an upcoming immersive interactive installation. The final outcome for this project (in the semester scope) is the generation of images sequences through interpolation, between two 'random' keyframes, or pre-generated keyframes.
These images sequences can then be converted to videos.

It currently is able to generate random images, random image sequences and keyframed image sequences.

ADD IMAGES

## Installation

### Hardware requirements
- AMD / Intel x64 (<i>Ryzen 7 - 3.6 Ghz, Intel Core i7-9750H - 2.6 Ghz</i>)
- High End GPU (<i>Nvidia Geforce GTX 1080Ti, RTX 2070</i>)
- High capacity hard drive (<i>3Tb</i>)
- Windows 10 / Linux

### Software requirements
- [CUDA 10.0.130](https://developer.nvidia.com/cuda-10.0-download-archive)
- [CUDNN 7.6.5](https://developer.nvidia.com/rdp/cudnn-archive)
- [Anaconda](https://www.anaconda.com/)

### Installation steps (windows)
<i>Note: these steps apply for windows, but they should not differ significantly for linux.</i>

1. Install <b>CUDA</b> and <b>CUDDN</b> - usage of these specific versions (<i>see above</i>) is mandatory
2. Install <b>Anaconda</b>
3. Create a local folder and clone this repo:<br>
``git clone https://github.com/d-pettersson/CODE-SE-15-Advanced-Machine-Learning``
4. Switch to the root folder and create an Anaconda Environment with the requirements:<br>
``conda create -n dl-exploration -f requirements.txt``
5. Activate the environment:<br>
``conda activate dl-exploration``
6. Run Jupyter Notebook in the cmd line and select the 'Generative Deep Learning - Exploration.ipynb' file:<br>
``jupyter notebook &``
7. <b>[OPTIONAL]</b> If the stylegan2 folder is empty or missing, clone this repo inside the <b>src</b> folder (it can also be done from within the notebook):<br>
``git clone https://github.com/skyflynil/stylegan2``
8. <b>[OPTIONAL]</b> The model snapshot is not uploaded on github, it can be either downloaded directly through the notebook or from this link. This file should then be placed inside the <b>src/model_snapshot</b> folder:<br>
``https://drive.google.com/open?id=1-PeMmAWtNlurqDTgZ8mbHbjdIeUE2Ags``
9. <b>[OPTIONAL]</b> If the original dataset is needed, it can be downloaded here:<br>
``https://drive.google.com/open?id=1lusgQA4jvaf_GSWQft2erH0c6t_qvEzi``

## Usage

## Support

## Roadmap

## Project status
