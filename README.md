# HorizonDroid

![HorizonDroid](https://github.com/HorizonDroid-13/.github/blob/main/Titania%20Update%20ROM_(0).png)

HorizonDroid
====================

Getting Started
---------------

To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/HorizonDroid-13/manifest.git -b 13 --git-lfs

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch aosp_<devicecodename>-userdebug
    m bacon

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community

### Important Links

- [Telegram channel](https://t.me/horizondroid)
- [Telegram group](https://t.me/HorizonDroidChat)

-----------------------------------------------------------------------------
