# kqsrp_missions

Interactive introductions to bioinformatics concepts for Kimberly Querrey summer fellows.

## Mission 1: Laptop set-up

### Install python

Find the python 3.14 installer for your laptop https://www.python.org/downloads/ and follow the steps to install it. 

Once it's installed, open a terminal (Terminal app on MacOS or Powershell on Windows) and type `python`. This should open a python shell. If this fails, update your system path to include the path to the python executable.

### IDE installation

Install vscode: https://code.visualstudio.com/download

### Clone this repository

We will share resources in this repository. "Clone it" (download it) to your laptop so that you have a version you can edit.

```
git clone https://github.com/luisa-cusick/kqsrp_missions.git
```

Change directory into this repository:

```
cd kqsrp_missions
```

### Environment set-up

Set up your virtual environment:

```
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

To confirm your virtual environment is active:
```
which python
```
should point to `venv/bin/python`

If your virtual environment is not active, reactivate it with:

```
source venv/bin/activate
```

### Connect VSCode to your venv

Open VSCode. Open the kqsrp_missions folder, and open the 00_scRNA_data_structures .ipynb file. On the upper right-hand side of the panel, click `select kernel`, and from there, choose venv (which points to the venv we created above). This allows you to import code from all of the packages that we've installed.

## Mission 2: Single Cell Data Structures

If you're interested in reading more about how to draw conclusions from scRNA-seq data, this best practices manual has lots of detailed explanations: https://www.sc-best-practices.org/preamble.html