## Arthropod Taxonomy Orders Object Detection


## Environment Specifications

- Windows 11
- cuda 11.8
- Visual Studio 2022 with standard C++ for desktop development

Now for the specifics of the conda environment: 

- Create a conda environment with python 3.8 specified. Then run the following: 

- conda install pytorch==2.0.1 torchvision==0.15.2 torchaudio==2.0.2 pytorch-cuda=11.8 -c pytorch -c nvidia
- pip install -U openmim
- mim install mmengine
- mim install "mmcv>=2.0.0,<2.1.0"
- cd [your path here]/mmdetection
- pip install -e .


This notebook https://colab.research.google.com/drive/16LG0HZh6LZZIGjM6Mu75M0YJhOOmXx-C?usp=sharing has an updated version of the methods needed to get the environment set up. Unfortunately, I couldn't get the training loop to run on my system or the lab servers. Google colab seems to be able to supply the correct torch and cuda environment for this combination of dependencies.
