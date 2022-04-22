# devcontainer-repository

> A template repository for vscode devcontainers

**Pre-requisites** : you already have a running devcontainer on your development computer. You can use [`jpbourgeon/devcontainer-ts`](https://github.com/jpbourgeon/devcontainer-repository) for a quick start with a typescript-node devcontainer.


1. On github, duplicate this repository from `Use this template` button. It provides you with a basic code workspace and an empty installation script to get started.
1. From within your devcontainer, git clone your newly created project repository in the `workspaces` folder.
1. Customize the shell script named `./devcontainer-install.sh` in the root folder of your local repository. This script should install all the tools and dependencies that your project needs (vscode extensions, CLI, tools, runtimes, global npm packages, etc.). The install script should be kept in version control so that every contributor can set up the same development environment. For the same reason, you should always install exact versions of your tools and dependencies.
1. Run your install script and start coding !