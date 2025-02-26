# rpi4-optee

## Build Default
Run: 
```sh
$git submodule init
$git submodule update
$source poky/oe-init-build-env 
$bitbake core-image-weston
```

## Build RPI Image:
Refer to https://github.com/mdmfernandes/meta-rpi-optee
The meta-rpi optee folder is already here. so no need to reclone it. Just modify conf/bblayers.conf to make necessary changes.

## Adding OPTEE Tests:
Currently OPTEE is built without all the tests. You may need to add more layers to the conf/bblayers.conf file and modify a few files around to make it work.
