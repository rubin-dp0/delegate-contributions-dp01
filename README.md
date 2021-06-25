# delegate-contributions

In this short note, we will show how you can contribute your work for the use of the larger DP0 community.  
Here, we will assume that you are working with a notebook - be it one of the DP0 - provided 
notebooks, or an entirely new one.  If you wish to contribute it - follow the workflow below.  

The recommended way is to edit an existing notebook (or start a new one) in your own instance of Jupyter.  
We recommend doing it in a suitable development branch, which you can subsequently push to the base 
repository, and submit a pull request - this will enable a code review. All delegates will have Write 
access and so can do this; everyone else can push to their fork of the Delegate repository, and submit  
a pull request from there. To exercise this workflow, try modifying Hello_World.ipynb, pushing your 
commit(s) and submitting a Pull Request.  As a good practice, don't forget to clear outputs and save 
before committing your changes!  

If you put together a notebok which you think might be valuable for others to use, please make sure you document it 
well.  In particular, the header of the notebok should include author's name and e-mail address, the goal of the notebook, 
and what are the prerequisites necessary to run the notebook.  We have a template of the notebook which we adopted 
from our Stack Club here: (we will need to copy the notebook at the link below to the current repo, and modify accordingly)
https://github.com/LSSTScienceCollaborations/StackClub/blob/2d16a13c5ef3567e4b1535eb3dcfeb17622558b9/GettingStarted/templates/template_Notebook.ipynb

As an example, we assume here that, working locally on your computer, you prepared a new notebook conforming 
to the standards.  Let's call it yournotebok.ipynb Now, working from the terminal window in yur Jupter instance, 
you need to issue the following commands:  

<here we need to give explicit set of git commands to put the notebook into the repo>

Of course your work might have been using the Rubin Science Portal rather than a notebook, and came up with a nice tutorial 
which might be of use to others.  Examples are:  a step-by-step Portal demo that uses the DC2 data set, or 
a TAP service instructional tutorial which uses the DC2 data set.  Once you have prepared one of those - you can follow the steps abve 
to contribute it to the same repository.  
