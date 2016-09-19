
# A Very Quick Introduction to Git/Github for Julia Users

Julia's package system and Github are very closely intertwined:

- Julia's package management system (METADATA) is a Github repository
- The packages are hosted as Github repositories
- Julia packages are normally referred to with the ending “.jl”
- Repositories register to become part of the central package management by sending a pull request to METADATA.jl
- The packages can be found / investigated at Github.com
- Julia's error messages are hyperlinks to the page in Github

Because of this, it's very useful for everyone using Julia to know a little bit about Git/Github.

## Git Basics

- Git is a common Version Control System (VCS)
- A project is a **repository** (repos)
- After one makes changes to a project, **commit** the changes
- Changes are **pulled** to the main repository hosted online
- To download the code, you **clone** the repository
- Instead of editing the main repository, one edits a **branch**
- To get the changes of the main branch in yours, you **fetch**
- One asks the owner of the repository to add their changes via a **pull request**
- Stable versions are cut to **releases**
- The major online server for git repositories is Github
- Github is a free service
- Anyone can get a Github account
- The code is hosted online, free for everyone to view
- Users can open **Issues** to ask for features and give bug reports to developers
- Many projects are brought together into **organizations** (JuliaMath, JuliaDiffEq, JuliaStats, etc.) 

An example Github repository for a Julia package is is DifferentialEquations.jl: https://github.com/JuliaDiffEq/DifferentialEquations.jl

## Examining a Github Repository

![GithubTop](https://github.com/ChrisRackauckas/JupyterSite/raw/master/assets/GithubTop.PNG "Top of a Github Repository")

Components:

- Top Left: Username/Repository name
- Top Right: The stars. Click this button to show support for the developer!
- Issues Tab: Go here to file a bug report
- Files: These are the source files in the repository


## Examining A Github Repository

![GithubBadges](https://github.com/ChrisRackauckas/JupyterSite/raw/master/assets/GithubBadges.PNG "Badges of a Github Repository")

The badges on a Github repository show you the current state of the repo. From left to right:

- Gitter Badge: Click this to go to a chatroom and directly chat with the developers
- CI Build Badges: This tell you whether the CI tests pass. Click on them to see what versions of Julia the package works for.
- Coverage: This tells you the percentage of the code that the tests cover. If coverage is low, parts of the package may not work even if the CI tests pass.
- Docs Badges: Click on these to go to the package documentation.
