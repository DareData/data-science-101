# Data Science 101

Welcome to The Data Science 101 repository.

The welcoming remarks presentation [can be found here](https://drive.google.com/open?id=1KWTDh6a1_68KMNVMDG70wZz0amPs_ijgkysFYsqVfqM).

[Here we have recorded the presentations](https://www.youtube.com/watch?v=0Vg-NaHsSXM&list=PLo3LSRSGRZNH13ooXSVBOnnA4uZtLbOU7) for most of the SLUs that were presented during the bootcamp weekend. Enjoy!

Here is you'll find all information needed to setup your environment and the
workflow you'll use during the course.

1. [Initial Setup](#initial-setup)
    1. [Setup _Git_/_GitHub_](#setup-_git__github_)
    1. [Install _Anaconda_](#install-_anaconda_)
    1. [Setup your Repository](#setup-your-workspace-repository)

## Initial Setup

This is one-time setup. Get it right the first time and you won't have to worry about it again!

## Presentation Videos

[Here you can find videos of the presentations](https://www.youtube.com/playlist?list=PLo3LSRSGRZNH13ooXSVBOnnA4uZtLbOU7)
at the [Batch3 LDSSA](http://lisbondatascience.org) course which is the original source of the material.

### Setup _Git_/_GitHub_

1. Install [_GitHub Desktop_](https://desktop.github.com/).
1. [Sign up](https://github.com/join) for a _GitHub_ account if you don't 
already have one.

### Install _Anaconda_

The work you will be doing during the course makes use of packages to provide
extra functionality.
Installing and managing different versions (that may have subtle changes)
in different operating systems and ensuring everyone gets the same results
is a challenging task.
_Anaconda_ is currently the best solution for this problem.

Go to [_Anaconda_](https://www.anaconda.com/distribution/) for installation 
instructions. **BE SURE to choose "Python 3.7 version".**

**If you are on windows**

Make sure that there are no non-english characters in your username or on the 
path and that you have qt installed. [Here is a reference](https://github.com/ContinuumIO/anaconda-issues/issues/1270) 
on how to address these issues.

### Setup your Workspace Repository

It's good practice to store your work with version control but for this course
it will not be required.


###### Using _GitHub Desktop_

1. Select "File > Clone repository" on the menubar
![Clone menubar](assets/clone.png "Clone form the menubar")
1. Select by URL "DareData/data-science-101"
1. Select and press clone

### Running a Learning Unit

In the `data-science-101` repository that you just cloned there is a sample
learning unit.
It's used to give instructors guidelines to produce the learning units.
We are also using it to ensure that you are able to run and submit a learning 
unit.

So go to the `sample/SLU00 - LU Tutorial` directory.
![Sample learning unit](assets/sample_learning_unit.png "Sample learning unit")


#### Creating a Conda Environment

With each learning unit you will be provided with an `environment.yml` file.
It tells _Anaconda_ all the packages the learning unit depends on and it
will be used to create an _Anaconda_ environment.

An environment is simply an isolated set of packages. 
When you run your code inside an environment you will have access to the 
same version of the packages the instructor used to create the notebooks.

###### Using the Graphical Interface

1. Select "Environments"
1. Select "Import"
![Select environment](assets/anaconda_environment.png "Select environment")
1. Set `slu00` for the name and select the `environment.yml` file in the 
learning unit directory (the one in your `batch3-workspace`).
![Create environment](assets/anaconda_create.png "Create environment")


#### Working on the Learning Unit

All learning units come as a set of Jupyter Notebooks (and some links to
presentations).
Notebooks are documents that can contain text, images and live code that you
can run interactively.

In this section we will launch the Jupyter Notebook application.
The application is accessed through the web browser.

Once you have the application open feel free to explore the sample learning
unit structure.
It will give you a handle on what to expect and what rules the instructors
follow (and the effort they put) when creating a learning unit.

So let's start the Jupyter Notebook app.

###### Using the Graphical Interface

1. Click the play button next to the newly created environment and select
"Open with Jupyter Notebook"
![Anaconda Jupyter](assets/anaconda_jupyter.png "Anaconda Jupyter")


##### The Exercise Notebook

Every learning unit contains an exercise notebook with exercises you will
work on.
So let's have a look at the sample Learning Unit. 
1. On the Jupyter Notebook UI in the browser open the exercise notebook
![Open exercise notebook](assets/jupyter_exercise_notebook.png "Open exercise notebook")
1. Follow the instructions provided in the notebook

Besides the exercises and the cells for you to write solutions you will see
other cells with a series of `assert` statements.
This is how we (and you) will determine if a solution is correct.
If all `assert` statements pass, meaning you dont get an `AssertionError` or
any other kind of exception, the solution is correct.

Once you've solved all of the notebook we recommend the following this simple 
checklist to avoid unexpected surprises.
1. Save the notebook (again)
1. Run "Restart & Run All"
![Restart & Run All](assets/jupyter_clear_and_run.png "Restart & Run All")
1. At this point the notebook should have run without any failing assertions

If you want to submit your notebook before it is all the way done to
check intermediate progress, feel free to.

If you are able to go through the entire process and get a passing grade on 
the sample LU you'll have a good understanding of the same flow that you'll use
for all LUs throughout the course.

