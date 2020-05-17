# Python


<br /><br /><br />
## Python Basics
<br /><br />
### 1. Python Installation

Install [Python](https://www.python.org/downloads/)
<br />
### 2. Python Notebook (Jupyter Notebook)
<br />
1. Easier Way (Beginner)

*Install Anaconda if:*
* Want to access most of the packages/dependencies
* Have enough space to store packages/dependencies
* Too lazy to setup environments
<br />

*Install Miniconda if:*
* Want to install individual packages/dependencies by yourself
* Have little space to store packages/dependencies
* Minimal spaces
<br />

**Install [Anaconda](https://www.anaconda.com/)**

**Install [Miniconda](https://docs.conda.io/en/latest/miniconda.html)**

<br /><br />

2. Hard Way (Commandline)

	1. install pip (*pip is installed with python3. For mac, use pip3 in commandline*)

	2. upgrade pip
	```
	pip3 install --upgrade pip
	```

	3. Install notebook
	```
	pip3 install jupyter
	```

	4. launch notebook
	```
	jupyter notebook
	```
<br />

### 3. Virtual Environment
<br />

On mac:
<br />
	1. Create a virtual path
```
python3 -m venv env
```

	*'venv' is the path, 'env' is the folder's name*
