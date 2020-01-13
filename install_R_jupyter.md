
For students wishing to install Jupyter on their own laptops, here are instructions for doing so. Please note that, while we will do our best to help you get Jupyter running on your own laptop, in some cases we may be unable to do so due to conflicts with software that you have already installed.

1. [Install Anaconda](https://docs.anaconda.com/anaconda/install/). Download the Python 3.x version. (If you have an existing installation of Anaconda, proceed to step 2.)
2. The Anaconda installer creates an application called "Anaconda Navigator". Open it by using the Launchpad (on OS X) or Start Menu (on Windows).
3. Verify that the package r-essentials is installed:
  a. Click 'Environments' and then the 'Channels button'. In the popup window, click 'Add' and type the character 'r'. Press enter.
  b. Click 'Update Channels' and wait for the status bar that says 'Updating channel configuration' to finish.
  c. Change the dropdown box from 'Installed' to 'All' and type `r-essentials` in the search box.
  d. If the box next to `r-essentials` has an X in it, proceed to step 4. Otherwise, click the box so that it become a green arrow and then click the green button 'Apply' in the lower-right. A window will pop up with a bunch of packages to be installed; again click 'Apply'.
3. Repeat step #3 for the packages `r-irkernel` and `r-tidyverse`.
4. Click the "Launch" button under the icon that says "Jupyter Notebook".
5. A few commands will execute in a terminal window, and then your browser will pop up with the Jupyter interface. This is a listing of your home directory. Navigate down to the folder where you have stored the Jupyter notebook (`.ipynb`) file that you wish to open.
