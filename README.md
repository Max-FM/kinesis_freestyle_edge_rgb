# Kinesis Freestyle Edge RGB
A repository of custom layout and lighting scripts for the Kinesis Freestyle Edge RGB keyboard.

In order to deploy scripts to the v-Drive from your local copy, you can set up a bare remote repository on the v-Drive as follows:
```
git init --bare <path/to/vdrive>
git remote add vdrive <path/to/vdrive>
```
You can then push/pull/fetch/etc. to/from the v-Drive like any regular remote repository, for example:
```
git push vdrive master
git pull vdrive master
git fetch vdrive
```

You could even clone the repository from the v-Drive to another local folder (e.g. if you're working on another machine):
```
git clone <path/to/vdrive>
```

**Note:** Make sure your v-Drive is connected (SmartSet + F8), otherwise the above commands will not work. Also, make sure to safely unmount your v-Drive before disconnecting to avoid any data corruption! Finally, be aware that the v-Drive only has 4MB of space, if your commit history gets too unwieldy, considered truncating it to save on space.
