# git-nas-scripts

1. Edit git-nas-param to set your information
2. Execute install.sh (sudo)
3. Execute scripts:

- git-nas-init
  - Init a repository (from ./existing project folder)
- git-nas-clone <remote repository name>
  - Clone a remote repository (from parent folder: creates a project folder)
- git-nas-template <remote repository name> <local project name>
  - Clone a remote repository as a template (without git folder and with a new name)
- git-nas-delete
  - Delete the remote repository and the local .git folder (not the local source files)
- git-nas-list
  - List all remote repository
