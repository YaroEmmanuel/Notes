
# PYTHON VIRTUAL ENV

## Installation
```sh
pip install virtualenv
```

## Setup of a virtual environment
```sh
virtualenv [name_of_virtual_env_folder]
```
or
```sh
py -m venv [name_of_virtual_virtual_env_folder]
```

## Activation of the virtual environment
on MacOS/Unix
```sh
source [path_to_the_virtual_env/bin/activate];
```
on Windows
```sh
path_to_the_virtual_env/Scripts/activate.bat
```
or
```sh
path_to_the_virtual_env/Scripts/activate.ps1
```
## Check the current activated venv
```sh
 py -c "import sys; print('Active venv:', sys.prefix if sys.prefix != sys.base_prefix else 'None')"
```

## List the available packages in the virtual environment
```sh
pip list
```

## Export the availables installed packages
```sh
pip freeze --locale > path_to_exporting_file
```

## Desactivate the virtual environment
```sh
deactivate
```

## Load exported installed packages
```sh
pip install -r path_to_exported_file
```
