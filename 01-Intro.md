
# 01 -- Intro

## Goals for today

* Introductions
* Course overview
* Intro to Colab (command line, git, github)

## Class notes (Colab notebook)

We'll start next week by working on the exercise in this notebook...

* [01 Class Notes.ipynb](https://colab.research.google.com/drive/1aygGMeMIGx16Y4IPORwDmOyfHCmOcWqC)

## Student responsibilities

Make sure you have your local environment set up...

* python & miniconda -- the latest release installed locally (look at Section 1.4 of McKinney)
* text editor -- vscode or others (e.g., vim) -- not atom (deprecated as of summer 2022 in favor of vscode)
* REPL (read-eval-print-loop) -- make sure you can run code from the command line

## Looking ahead

Next week we'll be using...

* [built-in functions](https://docs.python.org/3/library/functions.html),
* [I/O methods](https://docs.python.org/3/tutorial/inputoutput.html)
* [string methods](https://docs.python.org/3/library/stdtypes.html)
* [matplotlib](https://matplotlib.org/)

## Reading (for next week)

* There's a lot of reading. Some or all of it may be review -- skim the parts that are familiar.
* Focus on the reading necessary for you to to solve the exercise in the class notes.
* [Python for Data Analysis, 3rd Ed](https://wesmckinney.com/book/) (2022) by Wes McKinney
  * [Chapter 1, Preminaries](https://wesmckinney.com/book/preliminaries.html)
    * This is important
    * You should follow the instructions for installing a Python environment with miniconda
* [How to ask a good question](https://stackoverflow.com/help/how-to-ask) -- stackoverflow.com
  * This was mentioned in class -- it's here as a reference

## Reading (looking ahead)

* [Chapter 2. Python language basics, ipython & jupyter](https://wesmckinney.com/book/python-basics.html)
  * This chapter has a lot of detail.
  * Skim the chapter and practice with examples if the content seems new to you or if you want a refresher.
  * Open Colab (or a Jupyter notebook) to practice working with examples.
* [Chapter 3. Built-in data structures, functions and files](https://wesmckinney.com/book/python-basics.html)
  * We'll be applying techniques in this chapter.
  * There's a lot of content -- it's here as a supplementary reference.
* [Whirlwind Tour of Python](https://jakevdp.github.io/WhirlwindTourOfPython/) (2016) by Jake VanderPlas
  * This is a collection of notebooks on github that you can execute in Colab or Jupyter.
  * This is optional reading that you may find helpful -- much of if may be review, but it's still a good reference.

## Syllabus

* Syllabus (in Canvas) -- review the content in detail

## Attribution

* [Northeastern academic integrity policy](https://osccr.sites.northeastern.edu/academic-integrity-policy/)
  * Copy and paste could have legal implications that extend beyond academic integrity (unlikely for us right now).
* [Introduction to licenses](https://observablehq.com/@observablehq/licenses) -- observablehq.com
  * reusing published work, attribution, copyright
* [CapitalOne perspective](https://www.capitalone.com/tech/open-source/open-source-licenses-explained-2021/)
  * An open source lawyer explains code use under various open source licenses

## In-class exercise -- colab intro

* Colab -- https://colab.research.google.com/
  * Colab is Jupyter as a service, with GUI improvements & GPU access (and an underlying business model)
  * Authenticate with your husky.neu.edu
  * Colab and jupyter are for prototyping and in-class exercises, but NOT for code submission.
  * You can share Jupyter notebooks, but editing is not synchronous.  You need to "save" explicitly.
* Verify that students can access their github accounts
  * Show how to "share" a notebook with someone else
  * Practice with markdown and tex
* Accessing the iris dataset
  * Look here: https://github.com/mwaskom/seaborn-data/blob/master/iris.csv
  * Use the "raw" link
  * `!curl -O "https://raw.githubusercontent.com/mwaskom/seaborn-data/master/iris.csv"

## In-class exercise -- github intro

* Verify that students can access their github accounts
* Demonstrate how to clone their gh-classroom repo, modify a file and submit an assignment (on Canvas)
* Asking questions via github
* Personal and private repos
* github tutorials
  * hands on to verify that each student has basic capabilities

## Discussion -- iris dataset

* [iris dataset](./iris_dataset.md)

## Exercise -- penguins

* [penguins](./penguins.md)
