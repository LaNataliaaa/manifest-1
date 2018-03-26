Meta ROM

To get started with Meta, you'll need to get familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

Syncing Source
--------------
To initialise local Meta-ROM repositories in your machine:

    repo init -u git:https://github.com/Romproject/manifest.git -b oreo-mr1

Then to sync up:

    repo sync

To Build:

    . build/envsetup.sh && brunch meta_<device>-userdebug
