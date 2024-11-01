# CV-in-seismography
This is my code for diploma work in usage of CV(specifically U-net architecture) in reverse problem of seismography.

I created synthetic 2d dataset of the top of Earth's crust and run simulations of explosions and recorded measurements from the axelerometers on surface. 

Then I trained U-net model on this dataset, and got decent results. The result is a model that can take measurements of axelerometers and provide data on the structure of what is underneath the surface.

Data and trained model is available here https://drive.google.com/file/d/1K6ur6kBjapHoBMVy3sbydbwR1Vhe2oiw/view?usp=sharing

Unet code are from here: https://github.com/milesial/Pytorch-UNet.git
