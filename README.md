# cob_simulation
## Version
* This is based on the release version ros-indigo-cob-simulation:amd64/trusty **0.6.8**-0trusty-20170809-121612-0800, and incorporated with the changes customized for Robbie & Yuri (cob raw3-6) in Interactive Robotics Group.
  * To mix a release version with customizations:
    * `git clone https://github.com/ipa320/cob_simulation.git`
    * `git checkout 0.6.8`
    * `git remote -v`
    * `git remote rename origin upstream`
    * `git remote add origin <your forked git repo url>`
      * `git remote add origin https://github.com/Shentheman/cob_simulation.git`
    * `git fetch origin`
    * `git checkout -b <your new branch name>`
      * `git checkout -b irg-raw3-6`
    * `git status`
    * `git add -A`
    * `git commit -am <commit messages>`
    * `git push origin master`
