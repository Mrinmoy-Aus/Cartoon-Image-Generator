<h3 align="center">
  <img src="assets/image_generator_icon_web.png" width="300">
</h3>

# Image Generator

Python notebook containing TensorFlow DCGAN implementation. It was trained on a [Simpsons Faces](https://www.kaggle.com/kostastokis/simpsons-faces) dataset.

<br>
<h3 align="center">
  <img src="assets/homer.gif">
</h3>

## DCGAN
Network architecture by [Radford et al., 2015](https://arxiv.org/abs/1511.06434).
<img src="assets/model.png">

## Training
Visualization of training with the following hyperparameteres.
<img src="assets/epochs.gif">

	IMAGE_SIZE = 128
	NOISE_SIZE = 100
	LR_D = 0.00004
	LR_G = 0.0004
	BATCH_SIZE = 64
	EPOCHS = 300
	BETA1 = 0.5
	WEIGHT_INIT_STDDEV = 0.02
	EPSILON = 0.00005


## Results

Cherry-picked generated samples.

<img src="assets/final_grid.png">
