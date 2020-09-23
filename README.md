# ct-ng-env

Small tool for managing crosstool-ng installations, similiar to python's virtual environment.

## Installation
Clone the repository and link the ```ct-ng-env``` script to one of your PATH's binary directories

## Usage
```
$ ct-ng-env help
ct-ng-env <branch|tag|commit> <path>
```

```
$ mkdir ~/.ct-ng-envs
$ ct-ng-env master ~/.ct-ng-envs/master
$ ct-ng-env ea38601 ~/.ct-ng-envs/ea38601

$ source ~/.ct-ng-envs/master/activate
(ct-ng-master) $ which ct-ng
/home/tekieli/.ct_ng_envs/master/bin/ct-ng
$ deactivate

$ source ~/.ct-ng-envs/ea38601/activate
(ct-ng-ea38601) $ which ct-ng
/home/tekieli/.ct_ng_envs/ea38601/bin/ct-ng
$ deactivate
```
