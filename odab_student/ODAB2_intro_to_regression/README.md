# Intro to Regression

The point of this "One Day at Bootcamp" is to bring in beginner level students
and help them get on their journey to data science (hopefully by joining
Metis). This module is made up of several pieces

#### 0_intro_to_machine_learning.pdf

The goal of this piece is to introduce the students to the idea of machine
learning and some of the vocabulary. Focus on introducing the idea of records
and features, and how we can use features to predict labels.

*Estimate: 30 minutes*

#### 1_intro_to_pandas.ipynb

The goal of this piece is to familiarize the students with working with data
in pandas. It focuses on introducing dataframes, data slicing/selection,
getting basic statistics, basic plotting, and filtering. These pieces are
required for the case study. Also good to mention that this can do many things
SQL can like join, groupby, WHERE, etc. 

*Estimate: 45 - 60 minutes*

#### 2_intro_to_regression.ipynb

This notebook walks through the theory behind regression in a very basic
manner. It demonstrates how a line is just a slope and a bias, then shows how
we can just adjust those values then check errors. 

*Estimate: 15-20 minutes for this notebook*

#### 3_intro_to_sklearn.ipynb

This notebook introduces the concepts of the sklearn API such as: instantiate,
fit, and predict. It also demonstrates some of the sklearn documentation as
well as some examples of the power of the toolkit.

*Estimate: 15-20 minutes for this notebook*

#### 4_ames_housing_case_study.ipynb

This notebook uses SkLearn and the Ames housing dataset. A bit of data cleaning and filtering is done. We also
explain some of the common metrics used for regression techniques. The
students then have a chance to get into groups (if time allows) and try to
build the best model they can. If there is time, demonstrations of
RandomForestRegression are shown. As is
functionalizing the model building.

*Estimate: 1.25+ hours on this notebook*

## Material Distribution

The best practice we've found so far is to ZIP the student folder (after
adding any manipulation you want for your specific time teaching) and placing
the zip file onto a Google Drive. The students are then sent the "how to
install" document which you can add the a link to. The document is in the repo
as an example. 

## Goal Take-aways

- Familiarity with Pandas and manipulating data.
- Understanding of the concepts behind regression (error + optimize)
- What is sklearn, what does it do, and how do I do it?
- How do I build a model in SkLearn?
- Why would I want to build a model?
- What are features and labels?
- How can I visualize my results?

## What to watch for...

- WINDOWS. Most students in this class have Windows machines, make sure you
know how to troubleshoot Anaconda in Windows. For example, to launch it you
must open the Anaconda Launcher/Navigator from the Start Menu and leave the
DOS window it opens running. Otherwise the kernel is dead.
- Don't underestimate the amount of time you'll need to get everyone setup.
People will have problem downloading things. Not everyone comes prepared.
- The notebooks will take way longer than you think (and probably even longer
than my estimates, depending on how interactive your class is). Sacrifice the
end material for the beginning material.
