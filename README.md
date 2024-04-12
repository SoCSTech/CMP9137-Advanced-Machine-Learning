# CMP9137 - Advanced Machine Learning Devcontainer

A template repository for teaching Tensorflow

## Use case

You can use this repository to start developing with Tensorflow. It provides a preconfigured [Development Container](https://containers.dev/) with Tensorflow installed.

## Usage

This is a repository template, ready for you to either *fork* it (being able to pull in changes that happen in this repository later, recommended) or *use this template* to create your own independent repository.

### Option 1: How to *fork* (recommended)

Go to https://github.com/SoCSTech/CMP9137 and click on 

![Fork](.assets/fork.png) 

to create a GitHub Fork in your own GitHub account. Then continue to [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository on your computer. Learn more about GitHub Forks [here](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

### Option 2: How to *use as template*

Go to https://github.com/SoCSTech/CMP9137 and click on 

![usetemplate](.assets/usetemplate.png)

to create a new repository in your own GitHub account. Then continue to [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository on your computer. *Note: This repository is detached from the original one, so any changes in https://github.com/SoCSTech/CMP9137 happening after you created your own repository will have to be manually added.


### Setup your working environment

1. Make sure you have VSCode installed: https://code.visualstudio.com/download
2. Make sure you have the `Docker` and the `Dev Containers` extension in VSCode installed and working: https://code.visualstudio.com/docs/containers/overview and https://code.visualstudio.com/docs/devcontainers/containers
    * ensure docker is working, i.e. try `docker run --rm hello-world` and check it succeeds for your user
3. The docker image used to provide the Development Container is provided by the Docker Container Registry. You do not need to log in to use it.

### Open in VSCode

1. Open your own repository (*forked* or generated from this template) in VSCode: https://code.visualstudio.com/docs/sourcecontrol/intro-to-git (or any other way you prefer), e.g. click on "Clone Respository" in VSCode:
    ![Alt text](.assets/clone.png)

2. VSCode should prompt you that there is a devcontainer configured and ask if you want to reopen in container. Re-open in the container