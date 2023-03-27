 ### iNSTRUCTIONS ON HOW TO INSTALL PYMC3-3.11.4
 
 ##### 1. OPEN ANACONDA OR TERMINAL PROMPT TO CREATE A NEW ENV TO AVOID CONFLICT DEPENDENCIES
         `conda create --name pymc3_env`
         
 ##### 2. ACTIVATE THE ENVIRONMENT
         `conda activate pymc3_env`

##### 3. Install first the pymc3

* Please note this step is very crucial one mistake say good bye to the env

           `conda install pymc3`
* This will install all the pkgs needed so no need to install them separately, do no try to modify anything.

##### 4. For those who are using jupyter-lab do install the kernel with the following 
            `conda install ipykernel`
            
##### 5. install or activate the kernel
        
        `python -m install --user --name=pymc3_env`
        
* Please note if you do wish to graph your bayesian model you can do it by installing the following
        `conda install -c conda-forge python-graphviz`
        
#### Congratulations you have finally installed pymc3 and ready to work!!! 