# Git init

*by Elian Van Cutsem*

This project is an example used to explain how git works together with Github and Netlify.
Don't hesitate and contact me if you have any questions regarding git, github or other related stuff!

## prerequisites

1. [Github CLI](<https://cli.github.com/>), git CLI or a Git GUI
1. Basic programming knowledge
## Cloning the project

This project can be cloned via HTTPS. To do that just use `git clone https://github.com/ElianVanCutsem/odisee-git-init.git`.

This can also be done via the github CLI, just type `gh repo clone ElianVanCutsem/odisee-git-init`

## Issues

Issues are visible in the Issue subtab above or can be queried via the github CLI by using `gh issue list` and `gh issue view 1`

## Branching

A branch can be created via any git GUI. A branch represents a new line of development and can later be merged together. A branch is typically made for issues or features that take more commits or to achieve parallel feature implementation.

## Committing

When a commit is made, it will compile all added files into a .diff file with what was added or deleted. When it's pushed it'll be visible in the git timeline on the remote.

## Pull requests

Pull requests can be made via the pull requests subtab or via github cli. A pull request is a request to merge two branches.

## Deployment

In this project, we'll use Netlify to run our app. When we push to the master branch an automated build process will start and rebuild the online deployment.

When a pull request is made from another branch to the main branch, Netlify will merge the branches and try a branch deploy. This way we can test out our merged branches as a deployment before we take any definite actions.

## Further

Every tool has it's own features, so don't hesitate to look around and give everything a spin. Only that way you'll figur out what you like and what improves your workflow.