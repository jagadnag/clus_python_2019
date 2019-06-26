# clus_python_2019
CLUS LABRST-2678

## Python scripts for network automation lab

### Setting up a Python virtual environment

https://www.digitalocean.com/community/tutorial_series/how-to-install-and-set-up-a-local-programming-environment-for-python-3

* Clone the git repo
  * git clone https://github.com/jagadnag/clus_python_2019.git
* Navigate to the downloaded directory
  * cd xxxxx
* Create a python virtual environment
  * virtualenv venv --python=python2.x or python3.x
* Activate the venv
  * source venv/bin/activate
* Install the python package
  * pip install netmiko
  * pip install napalm
  * pip install jupyter
* Verify the python pip packages
  * pip list
* Run the scripts from terminal
  * python <script_name>.py 
* Run the scripts from jupyter notebook
  * jupyter notebook cl_python_lab.ipynb
* Deactivate the virtual environment 
  * deactivate
  
  
