# Legacy Modules Configuration for EPICS-env

In order to use this repository, one must setup the EPICS environment according to the following site.

https://github.com/jeonghanlee/EPICS-env



## How to install

`INSTALL_LOCATION` must be defined as where your `EPICS_BASE` is. 

```
echo "INSTALL_LOCATION=/home/jeonglee/epics/1.1.1/debian-12/7.0.7/base" > configure/CONFIG_SITE.local
make init
make conf
make build
make symlinks
```

## The follow modules will be installed within EPICS-env

```
pyDevSup
```
