

Manage Multiple Versions of Python:
https://medium.com/macoclock/how-to-install-and-manage-multiple-python-versions-on-macos-ca01a5e398d4

Python 3.7 already installed:
python -V

Upgrade Pip:
python3.7 -m pip install --upgrade pip


List all Python packages:
pip list

List all python versions:
ls -1 /usr/bin/python*

Install Jupyter:
Jupyter - via Self Service
Numpy installed on terminal for pythong 2.7 and 3.7 not working on Jupyter installed via Self Service
Installing Python 3.9 from Self Service








pip3 install --trusted-host pypi.org --trusted-host files.pythonhosted.org numpy
pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org pycurl

pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org pyopenssl


pip install --trusted-host pypi.org --trusted-host files.pythonhosted.org --upgrade pip
pip3 install --trusted-host pypi.org --trusted-host files.pythonhosted.org seaborn






——
still not resolved
it is infact showing numpy as available inside jupyter in !pip list but not able to import

will uninstall jupyter and reinstall from terminal
which -a jupyter
sudo rm -rf /usr/local/bin/jupyter


——
chkaur@LM-BGL-40511498 aiml % pip -V
pip 22.0.4 from /Users/chkaur/.pyenv/versions/3.7.0/lib/python3.7/site-packages/pip (python 3.7)
chkaur@LM-BGL-40511498 aiml % pip3 -V
pip 22.0.4 from /Users/chkaur/.pyenv/versions/3.7.0/lib/python3.7/site-packages/pip (python 3.7)

pip install jupyterlab








—yay issue resolved
pip3 install --trusted-host pypi.org --trusted-host files.pythonhosted.org pandas
 pip3 install --trusted-host pypi.org --trusted-host files.pythonhosted.org matplotlib

