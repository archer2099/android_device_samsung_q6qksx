# TWRP Device Tree for Samsung Galaxy Z Fold6 5G (Korean version)

## For Decryption
Not available.

## Clone repo
```bash 
git clone -b android-12.1 https://github.com/archer2099/android_device_samsung_b6qksx device/samsung/q6q
```

## To build 
```bash
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_q6q-eng
mka recoveryimage
```
