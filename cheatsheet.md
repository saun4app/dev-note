

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



#### Managing Channels

```
conda config --add channels new_channel
```

- https://conda.io/docs/user-guide/tasks/manage-channels.html

#### Manage Conda
```
conda info
conda update conda
conda update anaconda
```

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


