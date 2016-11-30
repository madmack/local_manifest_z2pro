#### Local manifest for build Cyanogenmod for Zuk Z2 Pro ####

### How to use:
```
git clone https://github.com/madmack/local_manifest_z2pro.git -b cm-13.0 .repo/local_manifests
repo sync --force-sync
. build/envsetup.sh
lunch cm_z2pro-userdebug
brunch z2pro
```
