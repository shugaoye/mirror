This is the branch for android-x86.
-----------------------------------
The official Git repository is at sourceforge.net: git://git.code.sf.net/p/android-x86/
The mirror in GitHub can be used as well: https://github.com/android-x86-mirror

We can refer to the android-x86 manifest at:
https://github.com/android-x86-mirror/manifest

To create a mirror of android-x86, we can use the below command to initialize a repo:
$ repo init -u https://github.com/shugaoye/mirror -b android-x86 --mirror
You can also create a mirror from GitHub using the below command:
$ repo init -u https://github.com/shugaoye/mirror -b android-x86 -m github.xml --mirror

20160819 - Updated sourceforge URL.
           Need to config file ~/.ssh/config.
           Changed protocol to git.
           Using empty.xml and local_manifests.
           Changed according to https://sourceforge.net/p/android-x86/_list/git.
           Added github.xml.
20160824 - Synced with android-6.0.1_r61.
