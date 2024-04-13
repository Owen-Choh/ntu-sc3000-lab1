# SC3000 AI Lab project
For the lab project in the Aritifical Intelligence module (SC3000), we had to create a reinforment learning agent to balance a pole on a cart.



Multiple model parameter files are included in case of errors when setting up a local environment.

The project is done using Google colab but I have also included set up instructions if you prefer to [install locally](#to-set-up-a-local-environment).

# To set up a local environment

1. Open anaconda prompt

2. cd into the directory of these assignment files

3. Type in this to create the environment: 
`
conda create -n py310 python=3.10
`

4. When prompted, press "y" to proceed with the installation 

5. Then activate the environment by typing
`
conda activate py310
`

6. Finally type in this to install all dependencies
`
pip install -r "requirements.txt"
`

When the installation is complete, open anaconda navigator and change the environment from "base (root)" to "py310" at the top. 

Click on "install" for jupyter notebook if it is not installed yet.

Launch the jupyter app from anaconda navigator and you can run the notebook from there.