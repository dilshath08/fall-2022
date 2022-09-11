
# Iris dataset

If you google "iris dataset"...

## Goals

* Introduce a classic Machine/Statistical Learning dataset
* Evaluate documentation, citation/references, reproducibility, attribution, software licenses
* Decide how to use (and not use) the results of a web search

## Results from google

Looking into the details from each of the top links from a google search

* Top link: [UCI ML archive](https://archive.ics.uci.edu/ml/datasets/iris)
  * UCI ML archive is undergoing an update -- [beta site](https://archive-beta.ics.uci.edu/)
    * top link on the beta site is the Iris dataset
  * old data contribution -- 1988
  * older data source -- 1936
    * web link is broken -- not a good sign, but understandable
  * many references to "the literature"
    * some of the links are busted, but you could probably use the link info to find the source
  * look at the data: "iris.data" and "iris.names"
    * "iris.data" is not a CSV file, you have to look at it to see that there are no column headers
    * data dictionary on the main page -- you can guess what's going on
  * "iris.names" 
    * this file has better documentation
    * mentions missing data value
    * some summary statistics that you could calculate to confirm that you grok the dataset
  * SUMMARY: 
    * looks authoritative, if old and clunky
    * worrisome that the links are busted
    * two separate files for data and metadata seems a little old fashioned, but it works
* 2nd link: [wikipedia](https://en.wikipedia.org/wiki/Iris_flower_data_set)
  * No problems with the wikipedia page
  * Nice intro paragraph
  * First image is a scatterplot matrix -- nice
  * Discussion of some analyses -- "typical test case for many statistical classification techniques in ML"
    * this is a hint that it's the statistical perspective
  * R code
    * illustrates typical usage -- second hint that this is a "stastistical perspective"
    * not really clear what's going on with R, but it produces all the scatterplots
    * [statlearning.com online course](https://www.statlearning.com/online-course)
      * has link to [videos](https://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
      * [intro video](https://www.youtube.com/watch?v=5N9V07EIfIg&list=PL5-da3qGB5ICcUhueCyu25slvsGp8IDTa&index=2)
      * worth looking at the beginning of this video, from 0 to 3:36
  * Python code
    * Doesn't produce any plots, but it does show you the data and results of running the code
    * You could verify that you get the same results with UCI dataset
    * Uses basic [datastructures](https://docs.python.org/3/tutorial/datastructures.html) in Python
  * References has links that aren't busted!!
    * You can actually get to the original article!!!
    * The original article is tough to read -- uses Fischer's "linear discriminant analysis"
    * This adds credence to the UCI reference -- and shows that statistics has lot of jargon (SVM, LDA, etc.)
* 3rd link: [scikit-learn](https://scikit-learn.org/stable/auto_examples/datasets/plot_iris_dataset.html)
  * has a link to wikipedia article -- nice
  * 3-D plot of 1st and 2nd eigenvectors -- what's an eigenvector -- statistical jargon?
  * 2-D plot of sepal length vs sepal width
  * deprecation warning from the output???
  * documented code with attribution and a license
  * copyright for the code is "scikit-learn developers" with the BSD license
    * [Software license](https://en.wikipedia.org/wiki/Software_license)
    * BSD is a permissive license -- like the "MIT license"
    * "unlimited permission to use, study, and privately modify the software"
    * "includes only minimal requirements on redistribution"
    * "gives a user the permission to use it as part of closed-source software or under a proprietary software license"
* 4th link: [kaggle](https://www.kaggle.com/uciml/iris?select=Iris.csv)
    * 1 million views, 250K downloads, 5K notebooks -- hmmm, that's a lot of usage
    * link to the original paper -- pdf -- is busted and it's somewhere in .ru domain (Russian Federation) -- WARNING!!
    * the dataset is a modified copy of the original -- WARNING!!!
    * no license or copyright -- public domain -- WARNING!!!
  * [Python code](https://www.kaggle.com/benhamner/python-data-visualizations)
    * uses pandas and seaborn -- okay, so will we at some point
    * uses the altered version of the original dataaset -- that means you're tied to this link for documentation
    * code says: "# current version of seaborn generates a bunch of warnings that we'll ignore" -- WARNING!!
    * at least they have documentation, but what version are they using!? -- WARNING!!!
  * This is the 1st link if you google "visualize the iris dataset"
