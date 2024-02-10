# HorizonDroid

![HorizonDroid](https://github.com/HorizonDroid-13/.github/blob/main/Titania%20Update%20ROM_(0).png)

HorizonDroid
====================

Getting Started
---------------

To get started with the HorizonDroid sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

 Configure git
 Given that repo requires you to identify yourself to sync Android, run the following commands to configure your git identity:
 
 -----------------------------------------------------

    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"

-----------------------------------------------------

Turn on caching to speed up build
Make use of ccache if you want to speed up subsequent builds by running:

    export USE_CCACHE=1
    export CCACHE_EXEC=/usr/bin/ccache

-----------------------------------------------------

and adding that line to your ~/.bashrc file. Then, specify the maximum amount of disk space you want ccache to use by typing this:

    ccache -M 50G

-----------------------------------------------------

Due to their size, some repos are configured for lfs or Large File Storage. To make sure your distribution is prepared for this, run:

    git lfs install

-----------------------------------------------------

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
