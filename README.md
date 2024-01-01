# to create envirnment in jupyter Notbook
python -m venv image

########################################## Creating Envirnment ################################

# to create envirnments in vs_studio
conda create -n gala_groceries python==3.11 -y


################################################ Removing ################################################

# to get all envirnment list
conda env list

# for removing existing environment
conda env remove --name environment_name



################################################# Installing ipykernel ############################################# 

# to install ipykernel package
pip install --user ipykernel

# to install the env as kernel
python -m ipykernel install --user --name=gala_groceries

# List all kernels and grap the name of the kernel you want to remove
jupyter kernelspec list

############################################### Removing Ipykernel ######################################

# Remove it
jupyter kernelspec remove <kernel_name>

################################################ GitHub ######################################################

############################################### or create a new repository on the command line ###################

### echo "# command_test" >> README.md #####

git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/007kakashi/command_test.git
git push -u origin main

########################################### or push an existing repository from the command line ########################

git remote add origin https://github.com/007kakashi/command_test.git
git branch -M main
git push -u origin main
