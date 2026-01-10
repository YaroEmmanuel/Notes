
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

## List the available packages in the virtual environment
```sh
pip list
```

## Export the availables installed packages
```sh
pip --locale > path_to_exporting_file
```

## Desactivate the virtual environment
```sh
deactivate
```

## Load exported installed packages
```sh
pip install -r path_to_exported_file
```
