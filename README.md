# CM for HTC Myst

WARNING: KERNEL BOOTS, but kernel panic.  Still not useable yet.

To init this repo:

    repo init -u git://github.com/CyanogenMod/android.git -b cm-11.0
    mkdir -p .repo/local_manifests
    wget https://github.com/CMyst/android/raw/cm-11.0/local_manifest.xml -O .repo/local_manifests/local_manifest.xml

To sync source:

    repo sync

To build:

    source build/envsetup.sh
    lunch cm_mystul-userdebug
    mka

Please see the [CyanogenMod Wiki](http://wiki.cyanogenmod.org/) for building instructions.
