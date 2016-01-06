# Functionality

Manage your projects right inside Visual Studio Code. Easily access and switch between projects.

# Usage

## Available commands

* **Project Manager: List Projects** List all saved projects and pick one
* **Project Manager: Save Project** Save the current project in the manager

![Commands](images/project-manager-commands.png)

### Save Project

You can save the current project in the manager at any time. You just need to type a name. It even suggest you _automatically_ :)

![Save](images/project-manager-save.png)

## Available settings

* Allow you to choose the sorting of the projects in **List Projects** command. You can choose:

    * **Saved**: The order that you saved the projects
    * **Name**: The name that you typed for the project
    * **Path**: The full path of the project

```
    "projectManager.sortList": "Name"
```

![List](images/project-manager-list-sort-by-name.png)

## TODO List

Here are some ideas that will be added soon:

* **Indicate Code path:** Allow to indicate the full path of `Code app`, in the case that code is not in `PATH`
* **Don't open another Code instance:** Instead of opening another **Code** instance, just switch the current

## Participate

If you have any idea, feel free to create issues and pull requests