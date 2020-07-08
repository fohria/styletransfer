# styletransfer

This code is a cleaned up version of this pytorch tutorial: https://pytorch.org/tutorials/advanced/neural_style_tutorial.html

For an overview and more info check out my blog post about using styletransfer to create "Planet Ghibli"; BBC's Planet Earth styled with Studio Ghibli: https://gamescapad.es/planet-ghibli-neural-style-transfer-planet-earth-studio-ghibli-part1/

## installation

1. Using a new anaconda environment:

```bash
conda create -n styletransfer
conda activate styletransfer
conda install pytorch torchvision -c pytorch
conda install pillow matplotlib
```

if you have a CUDA enabled graphics card, check the [pytorch site](https://pytorch.org) for alternate installation command for pytorch.

2. git clone this repository

3. All you need to do now is change the code around line 230 to point to the style image you want to use. Then put the image(s) you want to style in the input directory. **Important!** Images need to be the same size in pixels!
