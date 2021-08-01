### Based on A clean and readable Pytorch implementation of CycleGAN (https://arxiv.org/abs/1703.10593)

You can run a training session on 30 Monet images using the following Jupiter notebook:

https://drive.google.com/file/d/1T4c3eX4un60XGudMnvktL4pSs691JO2A/view?usp=sharing

It is recommended that you mount your google drive for easier access to the checkpoint at the end of the training.

Kaggle dataset will be downloaded and saved.
The selected 30 Monet images (done by choosing the farthest 30 points, after dimensionality reduction) will be saved.

Model checkpoints will be saved at:

output/netG_A2B.pth

output/netG_B2A.pth

### Evaluation notebook:
https://drive.google.com/file/d/1QxWmf7VrWMstAG9p80qslF2nmzCc-5yx/view?usp=sharing

The evaluation is based on a CycleGAN model which is trained for about 20 hours.

You can view a sample of 30 style transfer pairs and the training graphs (from Tensorboard).

You can also extract pnina.zip file which includes approximately 7000 Monet-style output images
and get the MiFID score.
