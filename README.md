# tfnn
Exploring TensorFlow implementations of neural networks.
## notes for installing the conda environment .yml
After executing the `conda create ...` to create the conda environment from the .yml file, the conda installer hung for a bit (after giving the yes/no prompts which usually appear when installing jupyter notebook in a conda environment, there's always 3, 1 followed by 2 more in quick succession). This process hung for at least 10 minutes.

I was going to restart the environment creation and hit Ctrl-C **ONCE** on my keyboard (this was a windows installation) to stop the current process, but this actually caused the hang to move forward and finish the installation (without issue to my knowledge). Hitting Ctrl-C a second time would have caused the process to stop completely, requiring the `conda create ...` command to be rerun in order to install the conda environment.
