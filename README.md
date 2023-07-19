# Farapy V2


This is a parent repository containing a few other repositories used to adapt and test models for Farapy V2. The descriptions for each submodule are provided below.

### [mae](https://github.com/youknowitskyle/mae)
This contains the implementation of the final model used for Farapy V2 (MAE-Face). It uses a masked autoencoder pretraining phase where it is trained on a large general dataset of face images. It is then fine-tuned on the downstream task of FAU intensity estimation.

### [farapy-data-tools](https://github.com/youknowitskyle/farapy-data-tools)
This repository contains some data/label processing tools for use with the DISFA and FEAFA+ datasets. The tools allow for generating subject-independent train/test folds following the method of similar FAU recognition/intensity estimation works.

### [ME-GraphAU-unilateral](https://github.com/youknowitskyle/ME-GraphAU-unilateral)
This repository contains an adapted version of [ME-GraphAU](https://github.com/CVI-SZU/ME-GraphAU) for FAU unilateral intensity estimation. It was our initial approach, but ultimately did not provide adequate performance.

### [Pytorch-FAU](https://github.com/youknowitskyle/Pytorch-FAU)
This repository contains the Pytorch implementation of Farapy V1's teacher model.
