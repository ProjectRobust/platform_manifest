# RobustOS

Please read the [AOSP building instructions](https://source.android.com/source/index.html) before proceeding.

Initializing Repository
-----------------------

Repo initialization:

        repo init -u https://github.com/ProjectRobust/platform_manifest -b raijin

Sync repo :

        repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags


Credits
-------
 * [**AOSP**](https://android.googlesource.com)
 * [**LineageOS**](https://github.com/LineageOS)
