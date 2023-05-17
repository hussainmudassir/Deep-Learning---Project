How to run the code:

Our main execution file is run-project.ipynb.
1. Import all the dependencies.
2. Get the GPU details
3. Load the config for the model params and dataset params.
4. Create a log directory to save the checkpoints such as train, reconstruction and animate.
5. Create generator, discriminator, and kp_detector and load it on the gpu.
6. Load datasets for training and reconstruction/animate.
7. Train the model and see the results in reconstruction/animate.

In order to run, it requires datasets that can be downloaded following steps mentioned by the authors of the paper. 
https://github.com/AliaksandrSiarohin/first-order-model

Losses will saved in log file, and since github does not allow us to push huge files, here is the link. https://drive.google.com/drive/folders/1iDHIRwHjPUOibhrV5_ZLJ0rbDbULfW51?usp=share_link


