# User API

Repo for the User API.

## About

This repo is designed to be used in a devcontainer. To use this repo effectively, docker and the VS Code devcontainer plugin must be installed. To open this repo in a devcontainer...

1) Start VS Code.
2) Open this folder in VS Code.
3) Open the VS Code command palette (`Ctrl + Shift + P` or View:Command Palette).
4) Search for "Reopen in Container" inside the command palette.
5) Hit `Enter`.

VS Code will start the devcontainer and make sure the right version of Java and Maven are installed. 

The first time this devcontainer is started, docker needs to pull the image (the files needed to actually run the container). On my laptop, it weighs about 1 gigabyte. Make sure you have at least 10 gigabytes of free storage. If your home internet isn't great, I would try to pull the images on campus. If your internet is too slow, pulling the images may not work.

#### Software Versions
| Software | Version  |
|----------|----------|
| Java     | 25.0.4.1 |
| Maven    | 3.10.0   |