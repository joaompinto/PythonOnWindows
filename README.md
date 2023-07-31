# PythonOnWindows

My preferred setup for developing Python applications on Windows.

Use the Mambaforge Python distribution because it supports multiple Python versions and it provides an easier way to install many python packages - from the Conda forge project.

## Install instructions

- If you have Python was installed from the Windows Store, **Uninstall** it first
- Install the latest Mambaforge from [Mambaforge-Windows-x86_64.exe](https://github.com/conda-forge/miniforge/releases/latest/download/Mambaforge-Windows-x86_64.exe)
    - Select "Add Mambaforge to my PATH", ignore the "NOT recommend" warning
- In a Terminal window: ```pip install rich ipython```
- If you do not have git installed yet run: ```winget install --id Git.Git```
