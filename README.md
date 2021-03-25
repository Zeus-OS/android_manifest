Zeus-OS
===========
![Zeus-OS](https://github.com/Lokesh773/RandomStuff/blob/master/ZenX_banner_o3.png)
<p align="center">


Getting Started
---------------
To get started with the Zeus-OS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/develop).


To initialize your local repository, use this command:
------------------------------------------------------

```bash
   repo init -u https://github.com/Zeus-OS/android_manifest.git -b 11.1
```

or you can do a shallow clone if you dont't have much bandwidth

```bash
   repo init -u https://github.com/Zeus-OS/android_manifest.git -b 11.1 --depth=1
```

Shallow clone lets you pull down just the latest commits, not the entire repo history. So if your project has years of history, or history from thousands of commits, you can select a particular depth to pull.

So if we are providing argument of `-- depth 1` to the repo init command it will copy only the latest revision of a repo:

To Sync the source:
----------------

You can just use `repo sync`, but this will save you from lot of terminal spam, data and time.

```bash
repo sync -c -q --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```

Building Environment
---------------

Please note that if you are building on Mac OS X, you are required to install coreutils from MacPorts before you continue.
Initialize the environment with the envsetup.sh script. Note that replacing "source" with a single dot saves a few characters, and the short form is more commonly used in documentation.

```bash
   . build/envsetup.sh
    brunch $device
```
# XDA Template
[![XDA-Template](https://github.com/Lokesh773/RandomStuff/blob/master/XDADevelopers_button.png)](https://github.com/ZenX-OS/XDA)


#Applying for Maintainership
---------------

[![Form](https://github.com/Lokesh773/RandomStuff/blob/master/Submission_button.png)](https://docs.google.com/forms/d/e/1FAIpQLSelSvOc5FmIIZM-hTun_3vQBiv6uS35HLrD9PkDPlbXFWeQpw/viewform)

# Telegram Support 
[![Telegram](https://github.com/Lokesh773/RandomStuff/blob/master/Telegram_button.png)](https://t.me/zenXOSGroup)
