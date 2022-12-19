# IMD Technologies Pico Board Support Package

To use this manifest, you must first install the `repo` tool:
```sh
$ mkdir ~/bin
$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$ chmod a+x ~/bin/repo
$ PATH=${PATH}:~/bin
```

To create a working environment for the latest release:
```sh
$ mkdir <working directory>
$ cd <working directory>
$ repo init -u https://github.com/imd-tec/imdt-pico-manifest.git -b imdt-linux-hardknott -m imdt-pico-bsp-v1.5.0.xml
$ repo sync
```
