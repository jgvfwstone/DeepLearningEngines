
Installing Python
=================

The simplest and most complete Python can be downloaded from Anaconda:
https://www.anaconda.com/distribution/

To find out where the default version of python is stored, type this to unix shell:

$ which python3

/Users/JimStone/anaconda3/bin/python3

Or, to download the basic Python language go to:

https://www.python.org/

Assuming you have Anaconda, it offers various programs to use with Python, including Python Notebooks.
I use the IPython application called Spyder which can be launched from within Anaconda.

In order to use standard neural network packages, you need to install (usually just one) software platforms:

Pytorch (owned by Facebook)

scikit-learn (funded by various public bodies)

TensorFlow (owned by Google)

Most examples in this book rely on Pytorch.
Both Pytorch and scikit-learn allow fairly easy access to the underlying Python code.

Installing Modules
==============

Install modules pytorch and torchvision:

$ anaconda/bin/conda install pytorch torchvision -c pytorch
(The -c tells conda to look under pytorch online).

To use some graphical examples involving computer games you will need gym:

$ cd PATH  /anaconda3/bin
Use  pip from within anaconda’s own directory to install packages in correct place:
$ conda install gym

If you need to tell pip where to put downloaded files then use the -t flag:
 pip3 -t, --target <dir>          Install packages into <dir>. 

$ pip3 install sklearn




Installing Pytorch
=================
Installing Modules
==============

Install modules pytorch and torchvision:
$ anaconda/bin/conda install pytorch torchvision -c pytorch
The -c tells conda to look under pytorch online

Install gym into anaconda package directly??????
$ cd PATH  /anaconda3/bin
Use  pip from within anaconda’s own directory to install packages in correct place:
$ ./pip install gym


Saving Notebook as Python  Code
===========================

Sometimes an online example is presented as a Jupyter Notebook or Jupyter Lab.
You can save the Python code to run within a Python application (e.g. Spyder).

From within Anaconda’s Jupyter Notebook, find the menu item;
	Download as …
or from Jupyter Lab, find the menu item
	Export Notebook as …
and download to file *.py.

