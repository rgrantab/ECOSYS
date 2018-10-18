# ECOSYS
The ECOSYS model for terrestrial ecosystem biogeochemistry

The code is developed by Professor Robert Grant at University of Alberta.

Jinyun Tang (jinyuntang@lbl.gov) helps maintaining the code on github.


# Download

git clone https://github.com/jinyun1tang/ECOSYS.git

You can also make a fork using the fork button on the upper right corner.

## Be sure to make your own branch or your own fork.
## Please do not merge to the master, use pull request instead.

# Build

Currently, the code is configured with intel compilers, icc and ifort.

* Type

  ./build_ecosys make

* Then follow the output information to locate the executable.

* To clean the build directory, type

  ./build_ecosys clean
* You can use github desktop from https://desktop.github.com to help you
  managing your repo.

# Several useful git commands

* Enter
  git log --graph
will give you a history of the commits.

* Enter
  git status
will list files that are currently tracked or not tracked by git.

* Enter
  git checkout -b your_branch
will make you a branch with name "your_branch"

* Enter
  git push -u origin "your_branch"
will push your branch to remote for the first time.

* You can also create a new branch using the github web tools.

* Enter
  git add files_you_changed
will add the "files_you_changed" to the tracking list.

* Enter
  git commit
will ask you to write a message about what you've done and what you want to others know about (why) the changes are made.

* Enter
  git push origin "your_branch"
will push your changes to your branch.

* Enter
  git pull --ff-only
will do fast forward merge in case your local branch is not synchronized with your remote branch.

* Enter
  git stash
will forget all your changes made in local directory.

* Enter
  git diff
will list your changes that made the code different from the remote.
