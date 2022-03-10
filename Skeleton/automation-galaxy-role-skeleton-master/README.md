## automation-galaxy-role-skeleton

## Description

`automation-galaxy-role-skeleton` is used to create new ansible roles according to Automation Team standards.

## Requirements

- **ansible-galaxy** command

## Usage

### Clone this project

Clone this project to your projects directory

```shell
mkdir ~/projects
cd ~/projects
git clone https://bitbucket.com/automation-galaxy-role-skeleton.git
```

### Create a new role

```shell
mkdir -p ~/projects/<project_name>/roles
cd ~/projects/<project_name>/roles
ansible-galaxy init --role-skeleton=~/projects/automation-galaxy-role-skeleton/skeleton new-role-name -vvv
```


## License

GPLv3 - GNU General Public License v3.0

© Automation OOGH

## Authors

- [Mohit Yadav](mailto:mohit-yadav@hcl.com)

