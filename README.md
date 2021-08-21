# molecule-practice
Running through the documentation [here](https://molecule.readthedocs.io/en/latest/getting-started.html).

## Setup
See [here](https://molecule.readthedocs.io/en/latest/installation.html) for details.
```shell
sudo apt update
sudo apt install python3-pip libssl-dev
python3 -m pip install "molecule[docker,lint]"
```

## Creating a new Role
```shell
molecule init role my-new-role --driver-name docker
```
This creates a new Role template in the current directory.