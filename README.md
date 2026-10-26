# AdvGAN_AdvDiff_implementations
Implementations of different AdvGAN architectures and AdvDiff, with a focus on readability and user-friendliness. 

This is my final project for HKAGE's collaborative advanced education course with City University of Hong Kong on Machine Learning, Generative AI, and Cybersecurity.

The pre-trained [AdvGAN](https://huggingface.co/hepialidae/mnist_advgan) model and the [AdvDiff](https://huggingface.co/hepialidae/ImageNet_AdvDiff_80Epochs) model can be found on Hugging Face.

## How To Use
To train your own AdvGAN or inference ours, download the entire repository, including the models folder. 

Then, enter the following in your command line:
```
cd {repository_host_folder}
python3 main.py
```
Training functions are optimized to load .pth files by default. If you would like to avoid this, delete the models folder.

To train your own AdvDiff or inference ours, modify the settings in the last cell of advdiff_implementation.ipynb accordingly.

## Copyright
This project is licensed under the [PolyForm Noncommercial License 1.0.0](https://polyformproject.org/licenses/noncommercial/1.0.0).
