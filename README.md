# Template repository for Jupyter workshops on Surf Research Cloud

## Installation

The participants of this workshop are typically provided with a notebook environment so they don't need to install anything.

## Repository materials

- The workshop material can be edited found in the  **workshop-material folder**. It contains the jupyter notebooks as well as the data used for the workshop.
- The folder **playbooks** is exclusively dedicated for automated transfer of the course materials to the digital workspaces on SURF Research Cloud. It is automatically updated by the GitHub Actions workflow, so no need to make changes to this folder.
- The `environment.yml` file describes the packages that are required to run the notebooks. The file is used to create a python kernel on SURF Research Cloud that has all the packages installed.
- The `.github` folder contains a GitHub Actions workflow that will automatically update the zipped `workshop-material.zip` whenever there are changes to the `workshop-material` folder.

## Contact

[Geo Data Team](https://geo-data-support.sites.uu.nl/)
[Research Engineering team](https://www.uu.nl/research-engineering)
