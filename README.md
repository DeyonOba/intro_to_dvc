# Introduction to DVC
[DVC][1] (Data Version Control) is an open-source version control system for data science and machine learning projects. It works on GitOps-like principles for tracking versioned data sources and code with a pipeline, tracking experiments, and registering models.

## DVC Installation

I am using Ubuntu Linux OS, but here are the links for [installing](https://dvc.org/doc/install) other operating systems, including Linux.

- [macOS](https://dvc.org/doc/install/macos)
- [Windows](https://dvc.org/doc/install/windows)
- [Linux][2]

Gets the list of the most recent versions of packages from their repository.
```bash
sudo apt update
```
Check for updates
```bash
sudo apt list --upgradable
```
Optional, upgrade packages listed
```bash
sudo apt upgrade
```
In order to use [DVC][1] as a Python package, a Python package manager like `pip`, or `conda` needs to be installed. Ensure the Python package installed is 8.0+ for the latest DVC release.
```bash
python3 --version
```
```bash
pip install dvc
```
```bash
pip show dvc
```

[1]: https://dvc.org/ "DVC"
[2]: https://dvc.org/doc/install/linux "Linux"
