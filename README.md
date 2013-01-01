Tracks for Android
==================

An Android application for the popular [Tracks](http://www.getontracks.org) todo
list.  Pertinent links:

* [Project Homepage](http://xvx.ca/code/tracks-android)
* [Source Code](http://github.com/adamwg/tracks-android)

Compiling
---------

Be sure to point local.properties at your Android SDK.  Then ant debug should
work.

Compile and install on emulator or attached device
--------------------------------------------------

* cd ~/my-android-projects/tracks-project-folder
* ant debug
* adb install -r bin/Tracks-debug.apk

TODO
----

* Migrate to Holo UI, add ActionBar (file:///home/raphael/bin/android-sdk-linux/docs/design/patterns/actionbar.html) (in progress)
* Use Fragments, great tablet UI (http://www.vogella.com/articles/AndroidFragments/article.html)
* Provide backwards compatibility for Android 2.x (which hasn't the Holo theme on board)
* Add theme switcher to allow bright and dark Holo theme

License
-------

Licensed under the MIT License.  See the LICENSE file.
