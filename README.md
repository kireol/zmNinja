![](http://www.pbase.com/arjunrc/image/160855207.jpg "icon") 

zmNinja is a multi platform (iOS, Android, Windows Desktop, Mac Desktop, Linux Desktop) client for ZoneMinder users.
ZoneMinder is an incredible open source camera monitoring system and is used
by many for home and commercial security monitoring. http://www.zoneminder.com

Video Demo
-------------
Check out a video demo of zmNinja here: https://youtu.be/prtA_mv68Ok

Mobile Platforms
---------------------------
zmNinja is  stable as of today and runs on a variety of Android and iOS platforms.
It also runs on the desktop (see below)

I have active testers today for both Android and iOS. If you want to test:

For Android, you can just download the app [here](https://play.google.com/apps/testing/com.pliablepixels.zmninja). It's in open beta. I'd appreciate if you drop me an email if you download the app so I know who you are.

For iOS, you need to send me an [email](mailto:pliablepixels@gmail.com) with your details.

Note that you should read [this](https://forums.zoneminder.com/viewtopic.php?f=33&t=23073) to understand which version of ZM you need for zmNinja to work.

I can release it to App/Play Store but I'd rather wait for ZM 1.29 to be released so people don't make
my life miserable about missing APIs etc.


Desktop Platforms
-----------------
Treat this as Beta. I'm using the awesome [Electron packager] (http://electron.atom.io) to auto-package my ionic apps to executables.

It may contain bugs. 

These files are hosted on Google Drive - when you click on them, look for the download button (down arrow icon) at the top so you download the ZIP

**Latest version:** 0.87.2D
**Last uploaded:** Nov 20, 2015

Please download binaries for Win 7, Linux or Mac from [here](https://github.com/pliablepixels/zmNinja/releases). 

Please make sure you download the correct ZIP file (32/64 bit)


Key Features (just watch the video already)
--------------------------------------------
* H264 video branch support - if you are using the zoneminder video branch and have recorded videos they will automatically be used (you can disable it in developer settings). If an event has a recorded video, you will see a small video icon at the top of that event entry in events view

* Receive real time push notifications for alarms as they happen. You need to install my [Event Server](https://github.com/pliablepixels/zmeventserver) for this. You can even control monitors you want to be notified of and reporting intervals (if you defined your zones loosely you don't want pings every second, do you?)

* Runs on Android/iOS and now desktops too - in a browser 


* View live monitors and events 

* High speed event scrubbing and control

* Pullup handy views of activities based on time 

* Incredible zoom/pan timeline of alarms

* Control Zoneminder - restart, change states

* Swipe/pan between monitors


Thanks
------
To the zonemider community in general, and the awesome Stack Overflow community.
But specifically, [Andrew Bauer](https://github.com/knnniggett) (knnniggett) - he is a ZoneMinder maintainer and
helped me significantly in getting into ZoneMinder and also continues to help
me with my client goals. 

Important Notes
---------------
* zmNinja needs APIs enabled in ZoneMinder. See https://github.com/pliablepixels/zmNinja/wiki/Configuring-ZoneMinder-with-API

Objective
----------
I wanted to learn how to create a full fledged cross platform app for a long time.
I used this as an excuse to learn Angular JS, phoneGap and ionic and see if one could
use these modern tools to build high performance phonegap apps. I was very pleasantly
surprised -- for a large part, most people who complain about performance  probably
haven't spent time researching how to optimize. 

I'll keep refining it over time as I learn more of AngularJS and stuff.

Running from source
----------------------

Please follow [these](https://github.com/pliablepixels/zmNinja/wiki/Running-zmNinja-from-Source) instructions.

If you want to run zmNinja in an emulator, you will need to install the appropriate emulator tools.

* For iOS, you will need the latest version of XCode (available in the App Store) as well as the npm package `ios-sim`: `npm install -g ios-sim`
* For Android, you will need the latest [Android Studio](https://developer.android.com/sdk/index.html)

Now, you can launch the emulator:

```bash
$ ionic emulate ios
# - OR -
$ ionic emulate android
```


Screenshots:
------------

Menu:

![](http://www.pbase.com/arjunrc/image/160697727/medium.jpg "Menu")

Events List:

![](http://www.pbase.com/arjunrc/image/160697725/medium.jpg "Events List")

Event Quick Scrub:

![]
(http://www.pbase.com/arjunrc/image/160851403/medium.jpg "Events Scrub")

Timeline View:

![]
(http://www.pbase.com/arjunrc/image/160940106/medium.jpg "Timeline zoomout")

![]
(http://www.pbase.com/arjunrc/image/160940104/medium.jpg "Timeline zoomin")


Full Screen Events Footage View (with floating buttons)
![](http://www.pbase.com/arjunrc/image/160697734/medium.jpg "Events View")

Sliding Montage View 1:

![](http://www.pbase.com/arjunrc/image/160697821/medium.jpg "Sliding Montage View")

Sliding Montage View 2 (Different sizes):

![] (http://www.pbase.com/arjunrc/image/160697822/medium.jpg "Sliding Montage View again")


Montage Re-order and show/hide:

![] (http://www.pbase.com/arjunrc/image/160697740/medium.jpg "Montage re-order and hide")


Monitor View:

![](http://www.pbase.com/arjunrc/image/160697737/medium.jpg "Monitor View")

Graphs:

![] (http://www.pbase.com/arjunrc/image/160697738/medium.jpg "Graphs")

Control ZM custom states/start/stop/restart:

![] (http://www.pbase.com/arjunrc/image/160697735/medium.jpg "Control ZM")


Change Monitor Modes:

![] (http://www.pbase.com/arjunrc/image/160697731/medium.jpg "Monitor Modes")


Pan/Tilt/Zoom Mode:

![] (http://www.pbase.com/arjunrc/image/160171688/medium.jpg "PTZ")
