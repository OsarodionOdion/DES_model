# discrete_event_simulation

## Using Discrete Event Simulation (DES) to help plan purchasing in an organisation 
**Project Goal** - The objective of this project is to build DES models to simulate the steps in purchasing items in an organisation. The SimPy python library is used in creating this model

All completed work for this project is contained in the `PR_simulation.ipynb` file.

Contents of the PR_simulation.ipynb file
-------------------------------------------

* The first section covers the executive summary and information on the model being built
* The Stages in building the Purchase Requisition model describes the steps taken to build the model
* The Purchase Requisition model covers the creation of the final model
* Results and analysis are provided in the other sections

How to use
-----------
* Set input parameters in the Function to launch section 
* Run simulation in the Run Simulation environment sub-section

Launch binder to access Notebook
------------------------------------
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OsarodionOdion/DES_model/HEAD)

The materials used in creating this project have been provided by Prof. Mark Isken, SBA, Oakland University.
The Cookie cutter used in placing this project under version control was created by Prof. Mark Isken, SBA, Oakland University.




Information on using this cookiecutter

Development workflows
=======================

Create new project
----------------------

You've already done this if you are reading this file. You ran:

```bash
cookiecutter gh:Osarodion/cookiecutter-datascience-simple
```

Put project under version control
---------------------------------

Let's get version control set up. You don't absolutely have to do this, but you should. For the local repository, do;

```bash
git init
git add .
git commit -m "Initial commit"
```

For the remote repository, make a github repository named discrete_event_simulation, then do;

```bash
git remote add origin git@github.com:Osarodion/discrete_event_simulation.git
git branch -M main
git push -u origin main
```

Great. Using version control is good.


Folder structure
-----------------

Here's the folder structure that gets created by `cookiecutter-datascience-simple`:

	├── discrete_event_simulation	<- Your notebooks and scripts will live in the main project folder
		│   .gitignore					<- Common file types for git to ignore
		│   README.md					<- The top-level README for developers (you) using this project
		│   template-nb.ipynb			<- A Jupyter notebook template
		│
		├───data						<- Final and intermediate data
		│   └───raw						<- The original, immutable data dump
		│
		├───docs
		│       notes.md				<- Simple markdown template for project notes
		│
		└───output
				readme.md				<- Guidance for using this folder


Documentation
--------------

In this very simple project structure template, we've just included a markdown file with some typical
section headings to use for project notes. Expand as desired. Later in the semester we will learn how to
use Sphinx with restructuredText to write and generate documentation.



