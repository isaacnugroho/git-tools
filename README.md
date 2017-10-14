Bash scripts to work on @mifosio projects.

Configuration Files
-------------------
  * **git-config**: git related configurations  
  * **project-list**: list of repo/project  

Create a copy of these files found at the root project directory to override the default values.

Scripts
-------
  * **init-repo**: initialize repos  
  * **add-upstream**: add mifosio's repo as upstream  
  * **build-all**: build projects  
  * **commit-all** (Param: *"commit message"*): commit and push changes in each repo  
  * **merge-upstream**: merge changes from upstream  
  * **init-git-flow**: init git flow on each repo (using default values)

Initialization
--------------
1. Set base repository and git user in git-config
2. Enlist your project(s) at MY_PROJECTS in project-list
3. Call init-repo to populate projects
4. Call add-upstream to set up upstream to mifosio projects

Miscellaneous
-------------
**README.md**: You're reading it!

Notes
-----
  * Feel free to modify these scripts
  * You may use these scripts for other projects not related to mifosio
