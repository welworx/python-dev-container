# Python DEV Container

Intention of the repo is to speed things up when starting with a new python project by getting a python dev container properly preconfigured.

# How to get started

1. clone repo into new project folder
```
git clone https://github.com/welworx/python-dev-container.git new_project
```
2. switch into folder 
```
cd new_project
```
3. and delete everything except the .devcontaienr folder
```
find . -mindepth 1 -not -name '.devcontainer' -not -path './.devcontainer/*' -exec rm -rf {} +
```
