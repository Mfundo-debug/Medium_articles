### Follow these steps to avoid conflict dependecies

1. Create a new envinronment Goto your anaconda cmd 

     `conda create -n pymc_env` 

2. Activate your environment

    `conda activate pymc_env`

3. Install from the github

     `pip install git+https://github.com/pymc-devs/pymc3`

4. if you are using jupyterlab, otherwise skip 4 and 5

 `conda install ipykernel`
 
5. install the kernel to the pymc_env

`python -m ipykernel install --user --name=pymc_env`

6. Install the necessary packages

- `pip install pymc` This is for PYMC 5
- `pip instsll numpy pandas, matplotlib, sklearn`
-  `pip install scikit-learn`

* Please Note that these steps are neccesary to run the notebook, otherwise do feel free to contact me, I will do my best to help 


### If you want to remove the kernel do the followng steps

1. Run the kernel list
` jupyter kernelspec list `

2. Find the name of the kernel you want to remove in the list

3. Run the command

`jupyter kernelspec uninstall <kernel_name>`

* Please note this will remove the kernel from jupyterlab and it will be permanently removed 