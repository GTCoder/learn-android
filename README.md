learn-android
=============

Testing: Emulators vs. Real Devices

Emulators vs. Real Devices for Mobile Application Testing - The Answer Might Surprise You
http://h30499.www3.hp.com/t5/The-Future-of-Testing-Blog/Emulators-vs-Real-Devices-for-Mobile-Application-Testing-The/ba-p/5506993#.U3o2PfldXuM

Mobile testing - emulators or real devices
http://www.cognifide.com/blogs/mobile/mobile-testing-emulators-or-real-devices/


ADB command:

* adb reboot - restart the device



Android Linux command:

* df: list the sizes of the folders

```
shell@android:/ # df
df
Filesystem             Size   Used   Free   Blksize
/dev                   384M    84K   384M   4096
/mnt/asec              384M     0K   384M   4096
/mnt/obb               384M     0K   384M   4096
/system                  1G     1G   177M   4096
/cache                 688M    11M   677M   4096
/efs                    19M     4M    15M   4096
/data                    4G   239M     4G   4096
/storage/sdcard0         4G   239M     4G   4096
```

* grep: grep entries of the output
```
shell@android:/ # ls | grep sys
ls | grep sys
sys
system
```

* cat
** cat filename: display the content of the file to console
```
shell@android:/data/local/tmp # echo "123" > test.txt
echo "123" > test.txt
shell@android:/data/local/tmp # cat test.txt
cat test.txt
123
```


Misc
* #: rooted, $: un-rooted


