

## Anaconda


### Conda

#### Managing packages

```
conda install package_name
while read requirement; do conda install --yes $requirement; done < requirements.txt
conda update package_name
conda list
conda search package_name
```

- https://conda.io/docs/user-guide/tasks/manage-pkgs.html


#### Manage Conda
```
conda info
conda update conda
conda update anaconda
conda update anaconda-navigator
conda update navigator-updater
```

#### Managing Channels

```
conda config --add channels conda-forge 
conda config --append channels conda-forge

conda config --add channels new_channel
conda config --append channels new_channel
```

- https://conda.io/docs/user-guide/tasks/manage-channels.html
- https://conda-forge.org



### Manage Anaconda 

#### Installation

```
bash Anaconda-latest-Linux-x86_64.sh
conda list
```

- https://conda.io/docs/user-guide/install/linux.html

#### Run App

```
anaconda-navigator
spyder
```

### Resources

- https://conda.io/docs/user-guide/index.html


## Vagrant

```
vagrant destroy
```

### clone 
```
vagrant package [name]
```

- https://www.vagrantup.com/docs/cli/package.html


## Docker


- https://dockstation.io/

## Docker Compose

- https://github.com/docker/compose/releases


## Ubuntu

###

```
sudo apt -y update
sudo apt -y upgrade
sudo apt -y dist-upgrade
```

###

Removing unused packages
```
sudo apt autoremove
```

### Error


Error: ENOSPC: no space left on device

```
sudo sysctl fs.inotify.max_user_watches=999999999
sudo tee -a /etc/sysctl.conf
sudo sysctl --system
```

### yarn

```
yarn global add  <package_name>
yarn global remove  <package_name>
yarn global list
yarn upgrade
```

```
export PATH="$PATH:$(yarn global bin)"
```

- https://tecadmin.net/install-yarn-debian/
- https://yarnpkg.com/lang/en/docs/install/#debian-stable


### Snap

```
sudo snap find 
sudo snap install <package_name>
sudo snap list
sudo snap changes
sudo snap refresh <package_name>
udo snap remove <package_name>
```
- https://docs.snapcraft.io/reference/snap-command
- https://docs.snapcraft.io

```
- https://snapcraft.io/
- https://snapcraft.io/store
```

## Dev Tools

- https://www.getpostman.com/


## Nodejs

### Yarn

```
yarn add <package_name>
yarn global add <package_name>
```


- https://yarnpkg.com/lang/en/docs/cli


## Git

- https://www.gitignore.io/
