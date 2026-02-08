# Project blueprint

This is a blueprint for new git managed js/ts projects with configs for
both [VS Code](https://code.visualstudio.com/) and [Zed](https://zed.dev/).

## Usage

These steps will create the folder for your new project. It should ne exist
beforehand.

The normal steps when using this is to navigate to the parent of your new
project folder and issue these commands:

```sh
git clone https://github.com/tregusti/project-blueprint PROJECT_NAME
cd PROJECT_NAME
```

If you do not want to keep the history of this repo, in your new project,
then also recreate the git repo.

```sh
rm -rf .git
git init
```
