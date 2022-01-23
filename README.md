# S22-W4111-HW-1-0: <br> W4111 - Intro to Databases HW0 and HW1

## Introduction

This project is the implementation template for HW 0 and HW 1 for both the
programming and non-programming tracks.

## HW 0 - All Students

You have completed the first step, which is cloning the project template.

__Note:__ You are Columbia students. You should be able to install SW and follow instructions.

_MySQL:_

- Download the installation files for [MySQL Community Server.](https://dev.mysql.com/downloads/).
  - Make sure you download for the correct operating system.
  - If you are on Mac
  make sure you choose the correct architecture. ```ARM``` is for Apple
  silicon. ```x86``` is for other Apple systems.
  - On Windows, you can download and use the MSI.


- Follow the installation instructions for MySQL. There are
[official instructions](https://dev.mysql.com/doc/refman/8.0/en/installing.html)
and many online tutorials.


- Remember your root user ID and password, that you set during
installation. Also, choose "Legacy Authentication" when prompted.
  - If you forget your root user or password, __you are on your own.__ The TAs
  and I will not fix any problems due to forgetting the information. 
  - Also, if you say something like,
  "It did not prompt me for a user ID and password when I instaled ... ..," we will laugh. We will say
  something like, ""Sure. 20 million MySQL installations asked for the information, but it decide to
  not to ask you."
  - If you tell us that you are sure that you are entering the correct user ID and password
  we will laugh. We will say something like, "Which is more likely. That a DATABASE forgot something or"
  you did?"


- You only need to install the server. All other SW packages are optional.

_Anaconda:_

- I strongly recommend uninstalling any existing version of Anaconda. If you choose not to uninstall
previous versions, you may hit issues. You are __on your own__ if you hit issues due to conflicting
versions of Anaconda during the semester.


- Download the most recent version of [Ananconda.](https://docs.anaconda.com/anaconda/install/index.html).


- Follow the installation instructions. Choose "Install for me" when prompted. If you hit a problem
and I find your Anaconda installation in the wrong directory, you are __on your own.__ If you say
something like, "But, it did not give me that option," you can guess what will happen.


_DataGrip:_

- Download [DataGrip.](https://www.jetbrains.com/datagrip/download) Make sure you choose the correct
OS and silicon.


- Follow the installation instructions.


- Apply for a [student license.](https://www.jetbrains.com/community/education/#students) 


- When you receive confirmation of your student license, [set the license](https://www.jetbrains.com/help/datagrip/register.html) information in DataGrip.


## HW0: Non-Programming

### Step 1: Initial Files

1. Create a folder in the project of the form <uni>_src, where <uni> is your UNI
I created an example, which is ```dff9_src.```<br><br>
2. Create a file in the directory `````<uni>_HW0.`````<br><br>
3. Copy the Jupyter notebook file from ```dff9_src/dff9_HW0.ipynb``` into
the directory you created and replace ```dff9``` with your UNI.<br><br>
4. Do the same for dff9_HW0.py

### Step 2: Jupter Notebook


- Start Anaconda.


- Open Jupyter Notebook in Anaconda.


- Navigate to the directory where you cloned the repository, and then go into the folder you created.


- Open the notebook (the file ending in ```.ipynb```).


- The remaining steps in HW0: Non-Programming are in the notebook that you opened.

## HW 0: Programming

- Complete the steps for HW0: Non-Programming. 


- The programming track is not "harder" than non-programming. The initial set up is a
little more work, however.


- Download and install [PyCharm.](https://www.jetbrains.com/pycharm/download) Download
and install the professional edition.


- Follow the
[instructions](https://www.jetbrains.com/help/pycharm/license-activation-dialog.html) to set the license key using the JetBrains account you
used to get the DataGrip licenses.


- Start PyCharm, navigate to and open the project that you cloned from GitHub.


- Follow the [instructions](https://www.jetbrains.com/help/pycharm/conda-support-creating-conda-virtual-environment.html)
for creating a new virtual Conda environment for the project.


- Select the root folder in the project, right click and add a new Python Package named
<UNI>_web_src. My example is dff9_web_src.


- Copy the files from ```dff9_web_src``` into the package you created.


- Follow the [instructions](https://www.jetbrains.com/help/pycharm/installing-uninstalling-and-upgrading-packages.html)
for adding a package to your virtual environment. You should add the package ```flask.```


- Right click on your file ```application.py``` that you copied and select run. You
will see a console window open and this will show a URL. Copy on the URL.


- Open a browser. Paste the URL and append '/health'. My URL looks like
```http://172.20.1.14:5000/health```. Yours may be a little different.

- Hit enter. You should see a health message. Take a screenshot of the browser window
and add the file to the directory. My example is ""
