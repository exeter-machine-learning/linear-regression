#Assignment: Linear Regression

In this exercise, you will implement linear regression and get to see it work on data. 

###Using Github and Git

If you have never used Github before I suggest checking out https://try.github.io . Pay particular attention the the section on `git branch` and `git merge`.

###Git Workflow

To try and keep everyone's code organized, we will use a branching workflow to separate code. This means you will never commit to the *master* branch.

To check which branch you are on, run `git branch`. You should **NOT** be on *master*

We will plan on merging in class, until then, only worry about creating your own branch. Please do not commit to the *master* branch or your code will be deleted.


###Installing Xcode Homebrew and Git

If you know you already have Xcode, Homebrew and Git installed feel free to skip this step. If not, pay attention.

* Xcode commandline tools:

        xcode-select --install

* Install Homebrew:

        ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

* Install Git:

        brew install git

### Setup Github 
* Generate a ssh key using your Github email and remember your passphrase: 

        ssh-keygen -t rsa -C "your_email@example.com"

* Copy ssh key into clipboard:

        pbcopy < ~/.ssh/id_rsa.pub

* Add your ssh key to github at https://github.com/settings/ssh
* Verify that it works:

        ssh -T git@github.com

* troubleshoot at https://help.github.com/articles/generating-ssh-keys

###Set Up
* Clone the repo:

        git clone https://github.com/exeter-machine-learning/linear-regression
        cd linear-regression


* Create your branch (Use your lowercase first name as `[branch name]`:

        git branch [branch name]
        git checkout [branch name]
        git branch
        #   master
        # * [branch name]

Now get to work. Before a commit, make sure you are in the branch you created with `git branch`

Email Nik or Jonathan with questions on Xcode, Homebrew, Git, or Github

### Start coding
Instructions on the assignment itself can be found in *ex1.pdf*