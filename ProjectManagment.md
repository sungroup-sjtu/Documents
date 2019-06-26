## General guidance of version control
1) **Master Branch** - Each repository has a master (default) branch, which is stable and ready for release (deploy). Only the owner can pull changes from other branches to the master branch. 
2) **Working Branches** - One or more working branches may be created for each reporsitory. Generally, a *Developing Branch* is created for new development that may need longer time. Another branch such as *BugFixing* may be used for quick modifications.  
3) **Collaborator** - Each collaborator may clone or fork from the **Working Branch** for your own needs. When the changes are done, files a *Pull Request* to the **Working Branch**, fix any conflicts and accept the request.
4) **Release** - When a release is made, a new branch such as "Release_000" is made in the reporsitory. This branch is for archival purpose, which does not accept any changes. Any new bug fixes should be made to the **working branches**.
5) **Project Board** - this is good for project managment. There is global one, also for each repository there is a local one which is most relevant to the reporsitory. The card can be edited and moved to different catagories.
