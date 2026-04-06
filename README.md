## PIXI
Pixi is a fast, modern, and reproducible package management tool for developers of all backgrounds.

### Installation steps
1. How to install on Windows
   Copy and execute the following command in Windows PowerShell and follow the steps to complete the installation.
```
powershell -ExecutionPolicy Bypass -c "irm -useb https://pixi.sh/install.ps1 | iex"
```
2. How to install on Linux/Mac
   Copy and execute the following command in the terminal and follow the steps to complete the installation.
```
curl -fsSL https://pixi.sh/install.sh | sh
```

### Update the PIXI
```
pixi self-update
```

### Remove the cached data
```
pixi clean cache
```

### Create a new Pixi manifest in the current directory
```
pixi init
```

### Create multiple environments
pixi workspace environment add [OPTIONS] <NAME>
```
pixi workspace environment add dev
```

### List environments in a workspace
```
pixi workspace environment list
```

### Activate the environment
```
pixi shell --environment dev
```

### Install/add the dependency in the workspace
```
pixi add numpy
```

### To install the dependencies in the workspace from PyPI
```
pixi add --pypi numpy
```




