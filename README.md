# delegate-contributions-dp01

This repository is for DP0 delegates to contribute tutorials for DP0.1. 

These tutorials could be Jupyter Notebooks, or markdown-formatted demonstrations of a DP0.1-related analysis with command-line tasks or the Portal Aspect.

Please contribute only tutorials that you have verified to run, and which you agree to maintain and be contacted about.

## How to contribute to this repository.

### Directories

All tutorials must be organized into directories.
An ``example`` directory is provided as an illustration.
Anyone may make a directory for a specific science topic, a specific tool or type of analysis, by DP0.1 working group, etc.
Directory creators must create a README.md file within the folder which identifies them as the directory maintainer and describes the contents of the directory.
Contact the directory creator if you want to contribute content to their directory.
Direct messages between delegates in Community.lsst.org is an appropriate mode of contact.

### Workflow

1. Make a branch for your work, and name it u/(your github username).
2. Add and edit content in your branch until you're ready to share it with everyone.
3. Start a new Pull Request (PR) from your branch to main. Assign another DP0 delegate to review it.
4. Incorporate any comments you recieve during review into your branch's materials.
5. After your reviewer has approved your PR, merge your branch into ``main``.

All delegates will have write access and so it is possible to commit changes directly to ``main``, but this is discouraged.

### Best Practices

Please always:
- document your code for non-experts
- provide links to background information
- clear notebook outputs before committing changes

All tutorials should have a header containing:
 - the author's name
 - the date the tutorial was last tested
 - the goals of the notebook

See the example directory for guidance on formatting notebooks and markdown files.

## Need to learn how to use GitHub?

Git is already installed in the Notebook Aspect of the Rubin Science Platform.

The best place to start in the extensive GitHub documentation is with the <a href="https://docs.github.com/en/get-started/quickstart/set-up-git">quickstart setup guide</a>.
There is also a <a href="https://training.github.com/downloads/github-git-cheat-sheet/">GitHub Cheat Sheet</a> of commonly used commands, and a <a href="https://docs.github.com/en/get-started/quickstart/github-glossary">GitHub Glossary</a>. 

<a href="https://www.youtube.com/watch?v=HVsySz-h9r4">Git Tutorial for Beginners: Command-Line Fundamentals</a> (a YouTube tutorial that includes git command line basics, but if you are not installing Git, you might want to skip a section of it describing the installation). 

<a href="https://medium.com/@christo8989/what-college-students-should-learn-about-git-6bbf6eaac39c">What college students should learn about Git</a> (a medium.com article that includes fundamental git concepts and basic git commands).

<a href="https://github.com/drphilmarshall/GettingStarted">Phil Marshall's notes on "Getting Started with git and GitHub"</a>.

<a href="https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent">Generating a new SSH key and adding it to the ssh-agent</a>, a guide to setting up git credentials so that you can push changes back to your remote repositories.

**See also the <a href="https://github.com/rubin-dp0/delegate-contributions-dp01/blob/main/CheatSheet.txt">GitHub Cheat Sheet</a> provided in this repository.** This cheat sheet was developed by Douglas Tucker for the <a href="https://github.com/LSSTScienceCollaborations/StackClub">LSST Science Collaborations Stack Club</a> and altered to be appropriate for Data Preview 0 by Greg Madejski. 
