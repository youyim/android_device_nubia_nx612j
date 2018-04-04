## How-to compile it:

To build:

```sh
. build/envsetup.sh
lunch omni_nx612j-eng
make recoveryimage
```

TO flash

```sh
fastboot oem nubia_unlock NUBIA_NX612J
fastboot flash recovery recovery.img
```
